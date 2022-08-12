# Analyzing Price Deviations in DeFi Oracles

<h3>Abstract</h3>
Decentralized Finance (DeFi) promises to transform the traditional financial systems into fair and transparent protocols that do not require trusted third parties. To circumvent the high volatility of crypto-assets, DeFi protocols advocate collateralizing their assets against conventional financial instruments. To do so, these protocols require access to external or off-chain data, such as asset exchange rates. DeFi protocols rely on oracles to access such information. Importing external data onto the chain via oracles consists of multiple data processing and aggregation stages. Thus, it is critical to minimize errors or deviations while the ground truth data moves through these stages. In this paper, we investigate the degree of price deviations at different levels between the data source and the final output rendered to an on-chain requester. In particular, we focus on Chainlink’s oracle network for ETH-USD pricing. Our results show that despite checks and balances, the output rendered to the requester considerably deviates from data reported by the sources.

<h3>People</h3>

* <a href="https://ciaoankit.github.io/">Ankit Gangwal</a>, International Institute of Information Technology, Hyderabad, India
* Rahul Valluri, International Institute of Information Technology, Hyderabad, India
* <a href="http://www.math.unipd.it/~conti/">Mauro Conti</a>, University of Padua, Italy

<h3>News</h3>

* August 11, 2022: Our paper "Analyzing Price Deviations in DeFi Oracles" has been accepted at <a href="https://www.cans2022.com/">CANS '22</a>.

<h3>Paper/Citation</h3>

Ankit Gangwal, Rahul Valluri, Mauro Conti.<br>
Analyzing Price Deviations in DeFi Oracles.<br>
In Proceedings of the 21st International Conference on Cryptology and Network Security (CANS 2022), in press, Abu Dhabi, UAE, November 13-16, 2022.

<h3>Dataset</h3>

<a href="./Dataset/Chainlink_Oracle_ETH_USD_Prices.xlsx"> Download main dataset</a>

We collected live data from April 17, 2022, 10:00 AM to May 23, 2022, 07:45 AM. Our final dataset has a total of 3399 rows of values and 40 columns  (i.e., 1 aggregator node, 31 oracle nodes, 7 data sources, and 1 column for timestamps). The respective column names are as follows:

1. Aggregator node
   1. ChainlinkAggregate
2. Oracle nodes
   1. Chainlayer
   2. Wetez
   3. ztake
   4. Mycelium Node
   5. Inotel
   6. Sync Node
   7. Omniscience
   8. Alpha Chain
   9. SNZPool
   10. Simply VC
   11. LinkPool
   12. 01Node
   13. DexTrac
   14. Prophet
   15. Staked
   16. PlusSign
   17. Anyblock
   18. LinkForest
   19. Fiews
   20. Framework Ventures
   21. Staking Facilities
   22. Blocksize Capital
   23. T-Systems
   24. Easy 2 stake
   25. Kytzu
   26. Figment Networks
   27. Newroad Network
   28. stake.fish
   29. Validation Capital
   30. P2P.org
   31. Infinity Stones
3. Data sources
   1. Coincap
   2. BraveNewCoin
   3. CryptoCompare
   4. AlphaVantage
   5. CoinGecko
   6. CoinPaprika
   7. CoinMarketCap
4. Timestamp
   1. TimeStamp
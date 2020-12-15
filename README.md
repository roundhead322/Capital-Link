
# Capital Link Lending & Borrow
Conflux Network cross-chain asset lending & borrowing protocol.

The problem: 2020 has been marked by explosive growth in the NFT and DEFI sectors. NFT’s have already begun changing hands for huge valuations of hundreds of thousands of dollars. This growth has occurred despite minimal public exposure to the idea of property rights over digital objects. The development of blockchain technology along with increased legitimisation of cryptocurrency in general, offers huge potential for the growth and acceptance of NFT’s. However, the non-fungible nature of these tokens means that any capital invested in them is locked into the NFT until such time that the NFT is sold. That can be problematic to investor’s who might feel forced to choose between buying an NFT or a cryptocurrency.

The solution: We would provide a means through which people could deposit their Ethereum NFT’s into a contract and be able to use it as collateral to borrow on Conflux. The borrower could then borrow an amount up to the max of the sum of all NFT’s they deposited. We could maybe start by taking a targeted approach to the NFT types we would support on the platform. 

Valuation of NFT’s.
I think we should focus on NFT collections that have high levels of locked liquidity and with decent trading volume, but are still relatively simple for us to value algorithmically. For example, maybe we could start by accepting lands from The Sandbox game. Small, medium, large, and X large lands would all have their own separate valuation on the platform. The borrower would access the dapp and would be given a valuation of the land(s) they wish to deposit based on a predetermined valuation model. The borrower would then select an amount of CFX they wish to borrow. Once they’ve deposited their collateral into the Ethereum contract, a signal is sent from the Ethereum contract to the CFX contract with details of the collateral being staked. 

	Other valuation considerations
•	This model could perhaps be based on an average of the last 10 sales prices. This should help make any attempt at wash trading to manipulate the valuation price prohibitively expensive.

•	The number of sales taken into consideration in the average would need to be proportional to the ‘supply’ of each collection. This should be relatively simple since the collection would be a fixed supply.

•	We would need a minimum time before it considers the next sell price to even out spikes in trading volume. For example there must be a min of 60 seconds before it considers the next sale price.

•	Maybe one day there could be a DAO to tweak the pricing models and accept new kinds of NFT’s onto the platform.

•	The tokenomics may require us to only issue over-collateralised loans?

Once the signal reaches the CFX contract, it will mint a synthetic NFT to represent that collateral on the conflux network. That NFT is designed to act like a key for the actual collateral locked away on Ethereum. The CFX NFT is then locked inside the conflux contract. 
Communication:
By leaving the collateral on Ethereum, we would avoid the cost and complexity of moving the entire NFT to conflux network. Instead we would ‘teleport’ the value of that NFT onto conflux by having the CFX contract mint a synthetic equivalent. In other words, contract interactions on one chain would need to trigger a contract action on the other chain. Being an EVM compatible blockchain, it might be possible to leverage arbitrary message bridges to facilitate those cross chain signals.

Lending
Meanwhile the lender would contribute CFX to the lending pool and would be offered a rate of interest for doing so. This is where well designed tokenomics would be important. For lending pools with low levels of liquidity, the reward would of course need to be higher to encourage greater participation. This is especially important if there is a separate lending pool for each NFT type. Once the synthetic NFT is locked in the CFX contract, the balance of the borrowed amount is deducted from the lending pool and sent to the borrowers wallet of choice. 

Repayment
Once the repayment conditions have been met, the CFX contract then sends a signal back to the Ethereum contract authorising the release of the collateral which is then sent back to the wallet of the borrower. The synthetic NFT is then burned and the process complete.


 

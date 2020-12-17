
# LiquiFi


Conflux Network cross-chain asset lending & borrowing protocol.


2020 has been marked by explosive growth in the NFT and DEFI sectors. NFT’s have already begun changing hands for huge valuations of hundreds of thousands of dollars. This growth has occurred despite minimal public exposure to the idea of property rights over digital objects. The development of blockchain technology along with increased legitimisation of cryptocurrency in general, offers huge potential for the growth and acceptance of NFT’s. However, the non-fungible nature of these tokens means that any capital invested in them is locked into the NFT until such time that the NFT is sold. That can be problematic to investor’s who might feel forced to choose between buying an NFT or a cryptocurrency.


LiquiFi v1: The first phase of the project would involve the creation and launch of the asset lending and borrowing platform on conflux. Borrowers would access the dapp and have the ability to offer their conflux NFT’s to lenders under terms of their own choosing. By leaving the choice of valuation price and terms to the borrow and lender, we’re ensuring a high degree of transparency and simplicity. They will have the option to request a minimum price and also request a duration. The lender would also have the option to make an offer on an NFT and suggest terms to the borrower. The lender would initiate the transaction by transferring the desired amount of CFX to the smart contract. The collateral would also be transferred to the smart contract and the lender would begin receiving payments under the agreed terms. If the borrow defaults on the terms of the loan, the collateral is transferred to the lenders wallet. On satisfaction of the repayment terms, the NFT is transferred back to the borrowers address.


LiquiFi v2: The second phase would build on the first phase by offering the user than chance to borrow CFX or CFX based crypto’s while using their Ethereum NFT’s as collateral. From the end user perspective, the process for borrowing and lending against an Ethereum asset or a Conflux asset should be the same.. The borrower would select the Ethereum NFT they wish to use as collateral and request terms. They would also select the cryptocurrency they wish to borrow (CFX or other conflux project). Once the transaction is initiate by the lender, the Ethereum NFT is transferred to the Ethereum contract. The Ethereum NFT never leaves the Eth blockchain. Instead, a signal is then sent to the Conflux contract containing details of the Eth collateral. A synthetic NFT key to the Eth NFT is minted and locked inside the Conflux contract. This NFT is designed to function as a key to the Eth collateral and is locked inside the Conflux contract for the duration of the loan. Once the repayment terms have been satisfied, the key is transferred to the borrowers CFX address and can be used to unlock the ETH collateral on the LiquiFi dapp.


LiquiFi v3:
-	NFT leasing
-	Contracts deployed for NFT’s on other blockchains.
-	Native token?
-	‘Kepler protocol-esque’ use of locked NFT collateral?





Communication:
By leaving the collateral on Ethereum, we would avoid the cost and complexity of moving the entire NFT to conflux network. Instead we would ‘teleport’ the value of that NFT onto conflux by having the CFX contract mint a synthetic equivalent. In other words, contract interactions on one chain would need to trigger a contract action on the other chain. Being an EVM compatible blockchain, it might be possible to leverage arbitrary message bridges to facilitate those cross chain signals.


Borrowing
The borrower would have the ability to request a loan in CFX or any CFX cryptocurrency. They could request a minimum if they want, or leave it to the lender to make an offer. This direct peer to peer approach eliminates the need for complex valuation models. It also ensures that the borrower and the lender do not feel frustrated by what they consider to be unfair valuations.


Lending
The lender would browse the available Conflux collateral (and in Eth collateral in v2). When they see a desired NFT they could either agree to the borrowers terms, or offer terms of their own. When an agreement is reached they would initiate the process by sending the required amount to the Conflux contract. If the lender has offered terms that the borrower agrees to, they would accept the offer which would trigger the start of the transaction.


Repayment
Once the repayment conditions have been met, the CFX contract unlocks the NFT and it’s sent back to the borrowers CFX wallet. In the case of Ethereum collateral in v2, the minted key is transferred to the borrowers CFX address. They would then log onto the LiquiFi dapp and connect their ETH and CFX wallets. At that point they would initiate the redemption process which would transfer the collateral to the key holders ETH wallet address. The CFX key is burned.


Liquidation
Should the borrower default on their debt, the Conflux contract unlocks the NFT which is then sent to the lenders wallet. In the case of Eth based collateral in v2, the minted key is transferred to the lenders CFX address. They would then log onto the LiquiFi dapp and connect their ETH and CFX wallets. At that point they would initiate the redemption process which would transfer the collateral to the key holders ETH wallet address. The CFX key is burned.






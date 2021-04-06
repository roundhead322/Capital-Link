
# LiquiFi - Litepaper


Cross-chain asset lending & borrowing protocol.


The crypto industry has seen explosive growth in the NFT and DEFI sectors recently. NFT’s have already begun changing hands for huge valuations of hundreds of thousands of dollars. This growth has occurred despite minimal public exposure to the idea of property rights over digital objects. The development of blockchain technology along with increased legitimisation of cryptocurrency in general, offers huge potential for the growth and acceptance of NFT’s. However, the non-fungible nature of these tokens means that any capital invested in them is locked into the NFT until such time that the NFT is sold. That can be problematic to investor’s who might feel forced to choose between buying an NFT or a cryptocurrency.


LiquiFi v1: The first phase of the project would involve the creation and launch of the asset lending and borrowing platform on Cardano. Borrowers would access the dapp and have the ability to offer their Cardano NFT’s to lenders under terms of their own choosing. By leaving the choice of valuation price and terms to the borrow and lender, we’re ensuring a high degree of transparency and simplicity. They will have the option to request a minimum price and also request a duration. The lender would also have the option to make an offer on an NFT and suggest terms to the borrower. The lender would initiate the transaction by transferring the desired amount of ADA to the smart contract. The collateral would also be transferred to the smart contract and the lender would begin receiving payments under the agreed terms. If the borrower defaults on the terms of the loan, the collateral is transferred to the lenders wallet. On satisfaction of the repayment terms, the NFT is transferred back to the borrowers address.


LiquiFi v2: The second phase would build on the first phase by offering the user the chance to borrow ADA or ADA based cryptocurrencies while using their Ethereum NFT’s as collateral. From the end user perspective, the process for borrowing and lending against an Ethereum asset or a Cardano asset should be the same. The borrower would select the Ethereum NFT they wish to use as collateral and request terms. They would also select the cryptocurrency they wish to borrow (ADA or other Cardano projects). Once the transaction is initiate by the lender, the Ethereum NFT is transferred to the Ethereum contract. The Ethereum NFT never leaves the Eth blockchain. Instead, a signal is then sent to the Cardano contract containing details of the Eth collateral. An NFT 'key' to the original Eth NFT is minted and locked inside the Cardano smart contract. This NFT is designed to function as a 'key' to the Eth collateral and is locked inside the Cardano contract for the duration of the loan. Once the repayment terms have been satisfied, the key is transferred to the borrowers Cardano address and can be used to unlock the ETH collateral on the LiquiFi dapp.


LiquiFi v3:
-	NFT leasing
-	Contracts deployed for NFT’s on other blockchains.
-	Native token?
-	‘Kepler protocol-esque’ use of locked NFT collateral?





Communication:
By leaving the collateral on Ethereum, we would avoid the cost and complexity of moving the entire NFT to the Cardano network. Instead we would ‘teleport’ the value of that NFT from Ethereum to Cardano by having the ADA contract mint a synthetic key to it. In other words, contract interactions on one chain would need to trigger a contract action on the other chain. 


Borrowing
The borrower would have the ability to request a loan in ADA or any ADA cryptocurrency. They could request a minimum if they want, or leave it to the lender to make an offer. This direct peer to peer approach eliminates the need for complex valuation models. It also ensures that the borrower and the lender do not feel frustrated by what they consider to be unfair valuations.


Lending
The lender would browse the available Cardano collateral (or Ethereum collateral in v2). When they see a desired NFT they could either agree to the borrowers terms, or offer terms of their own. When an agreement is reached they would initiate the process by sending the required amount to the Cardano contract. If the lender has offered terms that the borrower agrees to, they would accept the offer which would trigger the start of the transaction.


Repayment
Once the repayment conditions have been met, the ADA contract unlocks the NFT and it’s sent back to the borrowers ADA wallet. In the case of Ethereum collateral in v2, the minted key is transferred to the borrowers ADA address. They would then log onto the LiquiFi dapp and connect their ETH and ADA wallets. At that point they would initiate the redemption process which would transfer the collateral to the key holders ETH wallet address. The ADA key is burned.


Liquidation
Should the borrower default on their debt, the Cardano contract unlocks the NFT which is then sent to the lenders wallet. In the case of Eth based collateral in v2, the minted key is transferred to the lenders ADA address. They would then log onto the LiquiFi dapp and connect their ETH and ADA wallets. At that point they would initiate the redemption process which would transfer the collateral to the key holders ETH wallet address. The ADA key is burned.






## Base: A Bitcoin Layer for Smart Contracts


Base is a bitcoin smart contract layer that enables smart contracts and decentralized applications to trustlessly use bitcoin as an asset and settle transactions on the bitcoin blockchain. 


The first version of Base, which was released in early 2021, introduced several features including Bitcoin settlement for transactions, the BigBang language for secure contracts that can respond to Bitcoin transactions, and atomic swaps of assets with BTC. The proposed upgrade of Base, known as the Nakamoto release, includes important features that will enhance the power of Base as a Bitcoin layer. These features include: (a) a trustless, two-way Bitcoin peg to move BTC in and out of the layer and write to Bitcoin, (b) transactions secured by Bitcoin finality, and (c) fast transactions between Bitcoin blocks. The Base layer of Bitcoin enables it to function as a fully programmable asset in a trustless manner. This has the potential to activate hundreds of billions of dollars of passive Bitcoin capital and establish Bitcoin as the foundation of a more secure web3.

The Base layer for smart contracts has the following innovations that make it unique:<br><br>
**S – S**ecured by the entire hash power of Bitcoin (Bitcoin finality).<br>
**T – T**rustless Bitcoin peg mechanism; write to Bitcoin.<br>
**A – A**tomic BTC swaps and assets owned by BTC addresses.<br>
**B – B**igBang language for safe, decidable contracts.<br>
**K – K**nowledge of full Bitcoin state; read from Bitcoin.<br>
**S – S**calable, fast transactions that settle on Bitcoin.<br>

Bitcoin is considered the most durable and secure blockchain due to its minimal design that is meant to remain unchanged. The Base layer adds more functionality to Bitcoin without modifying its L1. Thousands of transactions at the Base layer result in a settlement at the Bitcoin L1, and Base microblocks offer fast confirmations of streaming transactions. Bitcoin serves as a settlement layer, and fast transactions between two Bitcoin blocks are proposed in the Nakamoto release. Additionally, scalability is improved through the use of subnets and other solutions such as appchains (https://gist.github.com/jcnelson/c982e52075337ba75e00b79942164e31).

Bitcoin's Base layer makes BTC productive in two ways:
- Base consensus enables a trust-minimized Bitcoin peg mechanism, called bBTC. A dynamic group of economically incentivized actors operate the peg. See the [bBTC page](https://base.co/bBTC) for more details.
- Further, through atomic swaps BTC can be trustlessly swaped and deployed into DeFi applications, NFT marketplaces etc.  

The Base asset (BASE) serves as the mining incentive for the Base layer and bBTC peg-out signing. Miners use BASE to secure the global ledger of the Base layer. It is important to note that this data cannot be stored on the Bitcoin main chain and must be stored outside of it. Additionally, BASE is utilized as gas for smart contract execution. BASE holders can lock their assets to earn Bitcoin rewards from the protocol. 

## BigBang Language for Smart Contracts

BigBang is a new language for smart contracts that prioritizes safety. It is a decidable language, which means that the program's behavior can be determined with certainty from the code itself. BigBang is an interpreted language, and the source code is published on the blockchain for the POT contract.

## Proof-of-Transfer (POT)

The POT consensus algorithm achieves consensus between the Bitcoin blockchain and the Base layer without consuming a significant amount of electricity like proof-of-work. Instead of using electricity, miners bid by spending BTC and receive a random probability of becoming a leader. The leader election occurs on Bitcoin, and new blocks are written on the Base layer. Miners use BTC to mine newly minted BASE. POT utilizes proof-of-work energy to achieve Nakamoto-style consensus for the Base layer. 

## How to Help

To assist us, you can contribute open-source code by sending pull requests with improvements.
You can also aid in software testing by running the software and filing issues.
Additionally, you can become a community evangelist and join the global community that supports our mission.


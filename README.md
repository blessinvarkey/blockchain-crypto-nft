
# blockchain-crypto-nft

To understand NFTs, lets first look at the definition of fungibility. 

Merriam Webster defines fungibility as : _"being something (such as money or a commodity) of such a nature that one part or quantity may be replaced by another equal or quanity in paying a debt or settling an account"_

<img src= "https://cdn.vox-cdn.com/thumbor/SiIyeqmKIJGcOJccz94pHgwmgvQ=/0x0:1400x1400/1200x800/filters:focal(588x588:812x812):no_upscale()/cdn.vox-cdn.com/uploads/chorus_image/image/68837730/poptart1redrainbowfix_1.0.gif" alt="drawing" width="300"/>


In simple words, fungible assets are usually individual units that are interchangible (e.g. company share and gold)

<img src= "https://media0.giphy.com/media/hXIyHHRdXfi0jz7BMX/200.gif" alt="drawing" width="300"/>


whereas, nfts or non fungible assets represent unique assets (e.g. cars, patents, houses)

<img src= "https://c.tenor.com/2gezOJJmFeMAAAAC/art-nft.gif" alt="drawing" width="300"/>



Question. If someone hands you a crushed INR 100 (or a $) vs a crushed painting you bought for say 50k. Which would still hold its value?  


## Blockchain
A blockchain is a continously growing list of records, called blocks which are linked and secured using cryptography[1]. 


<img src= "https://camo.githubusercontent.com/4d16c807754c4f0d04171e47334a3e67086d357519731d27e9d1f6af208c5a04/68747470733a2f2f7777772e65647572656b612e636f2f626c6f672f77702d636f6e74656e742f75706c6f6164732f323031382f30312f426c6f636b636861696e2d426c6f636b636861696e2d546563686e6f6c6f67792d45647572656b612e676966" alt="drawing" width="600"/>


- Block (contains records): 
    1. Data: "Hello World"
    2. Prev. Hash: 03DFA357
    3. Hash: 4D6E1F05

- First block is called the Genesis block
    1. Data: "Hello World"
    2. Prev. Hash: 00000
    3. Hash: 4D6E1F05

- Second block     
    1. Data: "Hello World"
    2. Prev. Hash: 4D6E1F05
    3. Hash: 7E8Y1U03

Paper: How to Time Stamp a Digital Document

## SHA256 Hash
The SHA256 algorithm as built by the NSA
SHA - Secure Hash Algorithm
64 characters 

2a89bf70001
40aa49638fd0
b4443921bbeef
b9cdb9ef6ea74
07cf82286afc

[Link to create a SHA256 hash](https://tools.superdatascience.com/blockchain/hash/)

The requirements for Hash Algorithms:
1. One-Way (i.e. can't create the document using hash key - fingerprint can't help you create the human)
2. Deterministic 
3. Fast Computation 
4. The Avalanche Effect 
5. Must withstand collisions

__The Avalance effect example:__ 
|Text |Hash |
|--|--|
| Hello this is a test hash | 52e19aaa9aafb109f096500871fbf93c5c72d9bc4112aa5519ae32c15c399f0f |
| Hello, this is a test hash.| fd7c3f418f77382dc81a0b6b8ad31ec062c3c8c4cebae1ae3635bffffe3bbbeb |


<img src= "https://i.gzn.jp/img/2020/05/14/sha-256-animation/190_m.gif" alt="drawing" width="500"/>

## NFT 
NFT, or non-fungible token, is a unique digital file that resides on the blockchain so that ownership of that digital file can be tracked. It is a cryptographic “hash,” or a unique string of letters and numbers that is related to a specific asset or object.

## Cryptocurrency

Three important layers in cryptocurrency: Technology, Protocol/coin & Token.

|Layers|Details|
|--|--|
| Technology| Blockchain|
| Protocol/Coins| Bitcoin, Ethereum, Neo, Ripple, Waves..|
| Token (smart contracts)| Ethereum - TRX, AE, REP BNB, MKR.., Bitcoin - None*|

Each coin is attached to a protocol. The coin is an innate asset of the protocol which faciliates the interaction of players, which is used to reward people for mining the blockchian and adding the blocks.

Tokens rely on smart contracts which are built on top of the different protocols in layer 2. 

*Bitcoin, Ripple have no tokens.

### Bitcoin Ecosystem
- __NODES__ (devices of persons who want to transact)
- __MINERS__ (who help the blockchain grow)
- __LARGE MINERS__ 
- __MINING POOLS__ 

### Bitcoin Monetary Policy
- The Halving: Every bitcoin released into the system is halved every single four years.
    - 03-01-2009: 50
    - 28-11-2021: 25
    - 09-07-2016: 12.50
    - 11-05-2020: 6.25
    - 2024 (TBA): 3.125


![](https://www.investopedia.com/thmb/US4m5w-KjA5g-dNkBdT0edrWmBY=/1600x960/filters:no_upscale():max_bytes(150000):strip_icc()/coinmetricsbtchalving-1aa1b4c4ddea47cfbe0439daf6e3626e.jpg)

### Mining Challenge
- Current Target: 
    - 0000000000000000005d97dc0000000000000000000000000000000
    - 18 Zeros (leading zeros):  <000000000000000000>5d97dc<...>
    
# Terminologies

## Airdrop
An Airdrop is a distribution of a cryptocurrency token or coin, usually for free, to numerous wallet addresses.
This is a technique in which crypto projects send their native tokens directly to the wallets of their users in an effort to increase awareness and adoption.

## Altcoin
Basically refers to cryptocurrencies other than Bitcoin and sometimes also other than Ethereum. Altcoin comes from an “alternative coin”, referring to any new cryptocurrency with a relatively small market cap.
Examples: Ethereum, Ripple, Tether, Bitcoin Cash, Bitcoin SV, and Litecoin.

## Ape
Ape is someone who invests heavily into a cryptocurrency, or the act of doing so.
This is usually a reaction to hype and FOMO and done without much due diligence of the asset.
An ape can also come from herd mentality or a community hyping up a coin.

## Bitcoin
The very first decentralized, peer-to-peer, digital currency, created by the pseudonymous Satoshi Nakamoto in 2009.
One Bitcoin today costs around $50,000 at the time of this writing.

## Block
A batch of transactions written to the blockchain.
Every block contains information about the previous block, thus, chaining them together.
Not to be confused with the newly renamed Square, now called Block.

## Blockchain
Blockchain is a publicly-accessible digital ledger used to store and transfer information without the need for a central authority.
Blockchains are the core technology on which cryptocurrency protocols like Bitcoin and Ethereum are built.

## Bridge
A protocol allows separate blockchains to interact with one another, enabling the transfer of data, tokens, and other information between systems.
Centralization

A hierarchical structure in which authority and control are concentrated within a small group of decision-makers.
Examples: Modern banks and social networks like Facebook and Twitter

## Coin
Not the band, but a cryptocurrency built on its own native blockchain, intended to be used as a store of value and medium of exchange.
Examples: Bitcoin, Dogecoin, Ethereum, Shiba inu

## Cold Wallet
A physical device use to store cryptocurrencies.
Cold wallets can be hardware devices or simply sheets of paper containing a user’s private keys.
Because cold wallets are not connected to the internet, meaning they’re offline, they are generally a safer method of storing cryptocurrencies.

## Consensus
The state of agreement amongst the nodes on a blockchain.
Reaching consensus is necessary for new transactions to be verified and new blocks to be added to the blockchain.

## DAO (Decentralized Autonomous Organization)
An organization based on open-source code and governed by its users.
DAOs typically focus on a specific project or mission and trade the traditional hierarchical systems of legacy corporations for guidelines written on the blockchain.

## Dapp (Decentralized Application)
An application built on open-source code that lives on the blockchain.
Dapps exist independent of centralized groups or figures and often incentivize users to maintain them through rewarded tokens.
Decentralization
Contrary to centralization, this is a system that operates without the control of a central figure of authority and replaces it with a distributed peer-to-peer network.
This is the whole concept of cryptocurrencies like Bitcoin, Ethereum, and Dogecoin.

## DeFi (Decentralized Finance)
The ecosystem of borderless, trustless, peer-to-peer financial tools being built on public blockchains without the use of banks.
DeFi apps are built to be open and interconnected, allowing them to be used in conjunction with one another.

## DEX (Decentralized Exchange)
DEX is a peer-to-peer cryptocurrency exchange built on the blockchain.
A DEX is run by its users and smart contracts instead of an intermediary figure or centralized institution.
Examples: Uniswap, 1inch, Sushiswap
Diamond Hands
A term implying that you are extremely bullish on a certain asset, and have no plans to sell regardless of market volatility, FUD, or extreme drops in price.
This term is mostly coined on Reddit and Twitter communities.
Someone who holds onto a cryptocurrency or stock as it drops 40% in a day is said to have diamond hands.

## ERC- (Ethereum Request for Comments)
The standard smart contract outline on which Ethereum-based smart contracts are built.
Ethereum
Ethereum is a public blockchain serving as the foundation for decentralized applications.
Ethereum is a Turing complete language, allowing for users to write and deploy complex, self-executing smart contracts which live on the blockchain.
Ethereum also is the foundation of other coins like Shiba Inu and Decentraland.
Fiat
A currency established as legal tender, often backed and regulated by a government.
Examples: The US Dollar

## Fork
A change to a blockchain protocol.
When these changes are minor, this results in a soft fork.
When the changes are more fundamental, this may result in a hard fork, leading to the formation of a separate chain with different rules.

## Fractionalization
The process of locking an NFT into a smart contract, and then dividing it into smaller parts which are issued as fungible tokens.
This lowers the price of ownership and allows artwork and other digital assets to be owned by a community.
FUD—Fear, Uncertainty, and Doubt
News around an asset that seems negative, but turns out to be false or blown out of proportion.

## Fungible
interchangeable; exchangeable with something else of the same kind.

## Gas
Not the one you put on cars, but a fee paid by a user to conduct a transaction or execute a smart contract on the Ethereum blockchain.
This fee is dependent upon the transaction’s complexity as well as the current demand on the network.
Just like the one you put on cars, gas cost is often high.

## Hashing
The process of taking an input of any size and producing a corresponding fingerprint of a fixed-length.

Hashing allows a set of data to be secured, stored, and recalled using a unique identifier code.
This is the backbone of blockchain technology, allowing data and transactions to be verified and stored in a secure manner.

## HODL—Hold On for Dear Life.
An expression meaning “hold” and frequently taken to be an acronym for Hold On for Dear Life.
This term actually began its life as a typo on an old Bitcointalk.org, where user GameKyuuby explained that he was “hodling” his bitcoin as the price dropped.
The misspelling quickly caught on and is still used today.

## ICO- (Initial Coin Offering)
The selling of tokens to the public in order to raise capital for a crypto-based project . ICOs are a crowdfunding approach, similar to a traditional company’s IPO.

## Liquidity
A measure of how easily an asset can be bought, sold, or traded in a given market or on an exchange.
Mining
In a Proof of Work system, this is the process of verifying transactions, organizing them into blocks, and then adding blocks to the blockchain.
Participants who perform this process are called miners.
And just like miners mining gold, miners here are mining coins.

## Minting
The process of adding a transaction or block to a blockchain.
The term is commonly used to express someone putting up an NFT on an exchange.
To the moon!
Similar to Lambo, this phrase implies that the value of an asset will go so high that it will reach the literal moon.
This expression is often used to express optimism into one asset and a belief in one asset that will skyrocket or go to the mooon.
 
## NFT (Non-fungible token)
A digital certificate of authenticity is used to assign and verify ownership of a unique digital or physical asset.
Unlike fungible tokens, NFTs are not interchangeable with one another.
Also often associated with art and digital artworks.

## NGMI—Not gonna make it
This is used to imply that a certain project or asset has a low chance of becoming valuable.
This can also be directed at an individual, usually, someone who had made a poor trade or investment.
Non-fungible
Unique, non-identical.

## Paper Hands
A term used to describe someone who sold a cryptocurrency or stock as its price was falling, usually for a loss.
Sometimes a result of a panic sell.
Someone with paper hands is said to be weak and unable to stomach market volatility.
## Private Key
An alphanumeric passcode is required to withdraw assets from a blockchain wallet and authorize digital transactions.
Because these private keys are long and difficult to memorize, wallets will generally associate them with a seed or recovery phrase that is easier to remember.
## PoS (Proof of Stake)
A consensus mechanism that requires nodes, called validators, to stake a set amount of cryptocurrency on the blockchain in order to verify transactions and mint blocks.
If a validator approves fraudulent transactions, then a portion of their stake will be slashed
## PoW (Proof of Work)
A consensus mechanism that requires miners to complete complex mathematical puzzles in order to verify transactions and mint blocks.
When a miner correctly solves a puzzle, they gain access to mint the next block and receive the corresponding block reward and transaction fees.
## Satoshis
The smallest denomination of BTC, equal to 0.00000001 bitcoin. Satoshis are named after Bitcoin’s pseudonymous creator, Satoshi Nakamoto.
Shitcoin
A cryptocurrency with weak fundamentals and little to no use case.
Examples: Shiba Inu and Dogecoin
Smart Contract
Self-executing code deployed on a blockchain that allows transactions to be made without an intermediary figure and without the parties involved having to trust one another.
## Solidity
The native programming language of Ethereum is mainly used to write smart contracts.
Just like Swift to iOS and HTML and CSS to front-end web.
## Token
Tokens can be used to represent digital and physical assets or used to interact with Dapps.
Unlike a coin, a token is a digital asset created on an existing blockchain.
Examples: LINK, UNI, AAVE

## Wallet
A software application or hardware device used to store the private keys to blockchain assets and accounts.
Unlike a traditional wallet, a blockchain wallet does not actually store the coins or tokens themselves.
Instead, they store the private key that proves ownership of a given digital asset.
Examples: Metamask, Coinbase Wallet
## Wallet Address
Also known as a public key, this is an alphanumeric code that serves as the address for a blockchain wallet, similar to a bank account number.
Other users can send digital assets to your wallet via your public key, but only you can access your wallet’s contents by using the corresponding private key.
## Web1
Web1, which is diffused from the 90s to mid-2000s is an internet that is one dimensional. Back then, websites only had one function, to display a list of information. So, you can read it.
There’s no posting, sharing, and interacting with other people, because it hasn’t been iterated yet.
It’s the era of read with as little to no user interaction or user-generated content.

## Web2
Web2, which is diffused from the mid-2000s to late 2010s is an internet that is two dimensional.
Example websites are Facebook, Instagram, Snapchat had multiple functions. Aside from reading information from their platform, you can also post your own content so other people or users can read yours too and vice versa.
It’s the era of read and write.

## Web3
Web3, which is now being diffused from the early 2020s up to the next decades is an internet that is not only three-dimensional but potentially, multi-dimensional.



## References

1. [coinmarketcap](https://coinmarketcap.com)
2. Satoshi Nakamoto's White Paper: Bitcoin: A Peer-to-Peer Electronic Cash System](https://bitcoin.org/bitcoin.pdf)

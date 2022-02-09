# blockchain-crypto-nft

To understand NFTs, lets first look at the definition of fungibility. 

Merriam Webster defines fungibility as : _"being somthing (such as money or a commodity) of such a nature that one part or quantity may be replaced by another equal or quanity in paying a debt or settling an account"_

<img src= "https://cdn.vox-cdn.com/thumbor/SiIyeqmKIJGcOJccz94pHgwmgvQ=/0x0:1400x1400/1200x800/filters:focal(588x588:812x812):no_upscale()/cdn.vox-cdn.com/uploads/chorus_image/image/68837730/poptart1redrainbowfix_1.0.gif" alt="drawing" width="300"/>


In simple words, fungible assets are usually individual units that are interchangible (e.g. company share and gold)

<img src= "https://media0.giphy.com/media/hXIyHHRdXfi0jz7BMX/200.gif" alt="drawing" width="300"/>


whereas, nfts or non fungible assets represent unique assets (e.g. cars, patents, houses)

<img src= "https://c.tenor.com/2gezOJJmFeMAAAAC/art-nft.gif" alt="drawing" width="300"/>



Question. If someone hands you a crushed INR 100 (or a $) vs a crushed painting you bought for say 50k. Which would still hold its value?  


### Blockchain
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

#### SHA256 Hash
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

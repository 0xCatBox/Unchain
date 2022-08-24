## Participated track

### Main track: Everything ZK

### Sponsored track: IPFS/Filecoin
#### Explicit links and lines where the technique is used
- Line 7 ~ 25 https://github.com/Unchain-Polygon-BUIDL-IT-Summer-2022/Unchain/blob/gooood/src/features/VideoToIPFS.js
- Line 6 ~ 45 https://github.com/Unchain-Polygon-BUIDL-IT-Summer-2022/Unchain/blob/gooood/src/features/ObjectToIPFS.js
- Line 8 ~ 30 https://github.com/Unchain-Polygon-BUIDL-IT-Summer-2022/Unchain/blob/gooood/src/features/GetListFromIPFS.js

## Inspiration
The damage caused by personal information leakage continues to occur. Therefore, the importance of protecting personal information is growing. And we think that the blockchain will solve the privacy. While studying DID, which was recently recognized as a web standard, I found that selective disclosure of personal information was necessary. At this time, using zkp, selective disclosure can be performed. As we studied zkp, we found that polygon tried many things using zkp. We happened to see the ZK track in Polygon hackathon and immediately joined Hackathon.

## What it does
Unchain is a Web3 based dApp that can targeted advertising  using zkp. Advertisers can pay tokens and post targeted ads. Advertisers should set advertising categories and store them in IPFS with advertising photos or videos. When a user selects an interest, zk-snark is used to show ads that fit user's interest. Users can receive rewards by watching advertisements. At this time, rewards come from tokens paid by advertisers. We're going to return most of the advertising money to the user. Users can receive compensation at the same time as concerns over personal information leakage disappear. Advertisers do not need to advertise to an unspecified number of people. This is possible because of zkp.

## How we built it
You can only watch advertisements in categories of interest without directly revealing the user's personal tastes to advertisers. This verifies the user's personal tastes through weights for each category using circcom, and advertisers can implement marketing strategies aimed at a specific customer base. Here, the advantage of zkp is that users can only see advertisements they need without revealing personal taste information to advertisers. The advertisement of the user verified through smart contract is determined and the advertisement posted on ipfs is viewed. After that, the ERC20 token is paid as compensation for the advertisement.

##reason for segmentation
Although the use of **ZKP** can minimize the exposure of information, it is impossible to completely eliminate the exposure of information. So by subdividing the categories, it makes it difficult to specify a person's preference.

## Challenges we ran into
Our ultimate goal is to build a true web3 using DID. In this polygon hackathon, we learned and used zkp as a way to reach true web3. we are proud to understand and utilize Circom2.

## What we learned
We learned a lot from Hackathon.
- ZK-SNARK Knowledge
- Utilize Circom2
- Platform utilizing IPFS
- Utilize SDKs related to IPFS
- Growth Possibility of Polygon with use ZK

## How to execute
```
npm i --legacy-peer-deps
npm start
```

## What's next for Unchain
We will learn more about ZK and approach true web3 using DID.
It will also start a startup. We will change the industrial structure through web3.

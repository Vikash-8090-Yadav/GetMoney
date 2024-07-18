

![Screenshot from 2024-06-23 05-01-32](https://github.com/Omega12Pirme/Monetizedo/assets/105157723/abe2d8ab-589f-4d81-be61-173d7512ba92)




# Demo Video: https://youtu.be/8c6AN52xaEQ?si=POdsUoxyUylUAPMv

# Frontend Deploy Link: https://monetizedo-ar51.vercel.app/

# Frame: https://warpcast.com/~/developers/frames?url=https%3A%2F%2Fmonetizedo.vercel.app%2Fapi

  

## Introduction 

Monetizedo is a revolutionary platform that allows users to monetize their work , resell work, and anyone can share their experiences in a dedicated dashboard. This platform eliminates intermediaries, empowering users to manage their WORK seamlessly.

## Contract Info ->  The  smart contract  is deployed ons BASE sepolia



Contract Address: 0x6D89e1be18912D3F212e16A4E40AfaEd4eaF5a08

https://base-sepolia.blockscout.com/address/0x6D89e1be18912D3F212e16A4E40AfaEd4eaF5a08


![Screenshot from 2024-06-23 05-18-49](https://github.com/Omega12Pirme/Monetizedo/assets/105157723/af8b506c-7a5b-4bfc-ba9a-6d8338cf107b)



## Working Flow !!

- **Monetize Content**: Users can easily monetize their content/ work .

- **Unique Digital Assets**: Each ticket is represented as a unique digital asset called an NFT (non-fungible token), ensuring it has its own digital identity that can't be replicated or divided.

- **Buy and Resell**: Anyone can buy these content/work products from the   owner, and once someone owns an NFT, they can resell it to others.

- **Experience Gather**: Participant can  share  their experience  after the events ends. So that other users can get  the idea  of the user work 


## Graph integeration Fracster  Frames 


![Screenshot from 2024-06-23 05-13-56](https://github.com/Omega12Pirme/Monetizedo/assets/105157723/7f6723f6-dfaa-4657-a33e-d6fb0b5f1857)


### Graph Query 

```
  const query = `
  {
    donations(first: 10, orderBy: id) {
      from
      id
      message
      name
      timestamp
    }
  }
  `;
```

The query code used in the Frame can be found here: https://github.com/Omega12Pirme/Monetizedo/blob/main/Frame/api/index.tsx#L100C1-L110C5


## The Graph Integration in Frontend Dapp


I created subgraph for this prroject and query  to make various dashboard like  Marketplace, Dashboard, Experience cebtre

### Here's the Link of the subgraph-> https://thegraph.com/studio/subgraph/monetizedo/playground


![Screenshot from 2024-07-18 19-03-44](https://github.com/user-attachments/assets/88cc342f-0df5-44b2-bea8-e4ce14b1cad3)

# Graph query 

###  The code for Montezing the content  is in: https://github.com/Omega12Pirme/Monetizedo/blob/main/Frontend/pages/marketplace.js#L35

###  The code for sharing experience can be found here : https://github.com/Omega12Pirme/Monetizedo/blob/main/Frontend/Component/v1.0.0/Review/Memos.jsx#L14


# Working flow 

## Marketpace 

- Any user can buy the work  of others in the form  of nft 

![Screenshot from 2024-06-23 05-17-11](https://github.com/Omega12Pirme/Monetizedo/assets/105157723/5c229e7c-9d73-48a3-ae34-1c59a0d7849a)



## MOneztize work  

- Any  owner can monetize their work in the form of NFT they will get METT tokens as a reward 

![Screenshot from 2024-05-27 10-40-33](https://github.com/Vikash-8090-Yadav/OneTicket/assets/85225156/60be4e17-b976-4652-9089-49666bed0567)


## Re sell 

- Any user who buys the work  can re sell it to the one who needs it

![Screenshot from 2024-05-27 10-41-03](https://github.com/Vikash-8090-Yadav/OneTicket/assets/85225156/b815ba4d-353a-42a1-bd9b-f12415c0193b)


## Experience share 

- Any member can share their after event experience

![Screenshot from 2024-05-27 10-41-26](https://github.com/Vikash-8090-Yadav/OneTicket/assets/85225156/1487f135-125b-40a1-b178-d24abd3312ff)



### How to run farcaster Frame  Locally

`- Clone this repo 
``` git clone https://github.com/Omega12Pirme/Monetizedo.git ```

- Got to the Frame directory

  ``` cd  Monetizedo/Frane ```
  
- start the  project
  ``` npm run dev ```

- Start the ngrok server

  ``` ngrok http http://localhost:5173 ```
- Got to dev farcaster and paste the ngrok link with /api append https://warpcast.com/~/developers/frames


 

## 🛠️Technologies we used

[![Powered by Filecoin](https://img.shields.io/badge/Powered_by-Filecoin-0174F2?logo=filecoin)](https://filecoin.io/)
[![Powered by Lighthouse](https://img.shields.io/badge/Powered_by-Lighthouse-ff69b4?logo=lighthouse)](https://lighthouse.filecoin.io/)
[![Built with React.js](https://img.shields.io/badge/Built_with-React.js-61DAFB?logo=react)](https://reactjs.org/)
[![Developed in Motoko](https://img.shields.io/badge/Developed_in-Motoko-2196F3?logo=dfinity)](https://sdk.dfinity.org/)
[![Tailwind CSS](https://img.shields.io/badge/Styled_with-Tailwind_CSS-38B2AC?logo=tailwind-css)](https://tailwindcss.com/)
[![Powered by Ethereum](https://img.shields.io/badge/Powered_by-Ethereum-3C3C3D?logo=ethereum)](https://ethereum.org/)

| Technology        | Description                                                | Official Website                                     |
|-------------------|------------------------------------------------------------|------------------------------------------------------|
| React.js          | JavaScript library for building user interfaces, often used for server-rendered or statically-generated applications | [React.js](https://reactjs.org/)                      |
| Tailwind CSS      | Utility-first CSS framework for building custom designs   | [Tailwind CSS](https://tailwindcss.com/)              |
| Solidity | Programming language used for smart contract development on the Ethereum blockchain | https://docs.soliditylang.org/ |
|LightHouse | Store file Secure, Reliable, & Lightning-Fast with Lighthouse. |https://www.lighthouse.storage/|
|ChainLLink | Chainlink is the decentralized computing platform powering the verifiable web| https://chain.link/|
|The Graph| The Graph is a decentralized protocol for indexing and querying blockchain data. The Graph makes it possible to query data that is difficult to query directly.|https://thegraph.com/ | 
|Warpcast| Warpcast is a client for Farcaster, a decentralized social network. It is a paid-for social media platform that allows users to create a profile, post public messages, and connect with others. Unlike traditional social media apps, Warpcast is built on the blockchain, making it open, permissionless, and decentralized. | https://warpcast.com/|





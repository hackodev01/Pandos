<p align="center">

</p>
<h1 align="center">Pandos 🎧</h1>

<p align="center" title="Project Initiator"><img src="./src/assets/img/pandos.png" alt="Project Initiator"/></p>

## Pandos Purpose

Music platforms such as Spotify and Apple Music take a large percentage of royalties from their own artists. Which we believe should not be the case. Musicians are expected to enjoy the majority of their work. Aside from that, these platforms have the censor your content anytime they want. Music, podcasts, and similar content should be owned and controlled by the user. It should not be taken over by a third party.

## Dapp Working

Pandos is a decentralized music, podcast and online radio platform built on IPFS that offers the ability to upload, stream and play music. The goal is to create a free decentralized version music platform which artists get paid directly through listener support.

Our application does four(4) things really well

- **Create: It allows podcast creators to record their podcasts directly from our website. And then upload them for their users to listen.**

- **Meta Space provides an intuitive user experience when it comes to creating a space for a conversation about anything. Send live reactions, tip users,and many other things.**

- **NFT:Artists can mint their album covers as NFTS and reap the benefits of both their fans purchasing the music and their NFTS.**

- **Chat: Send live messages during online space session on pandos.**

## 🦋 Prerequisite

- [Nodejs](https://nodejs.org/en// "Node") Installed

- [Git](https://git-scm.com/ "Git OFficial") Installed

- [npm](https://www.npmjs.com/ "npm ") Installed

- [Hardhat](https://hardhat.org/ "Hardhat ") Installed


## Configuration

The chain ID should be 80001. If you have a localhost rpc set up, you may need to overwrite it.

<p align="center" title="Project Initiator"><img src="./src/assets/img/rpc.jpg" alt="Project Initiator"/></p>

To deploy to Polygon test or main networks, update the configurations located in hardhat.config.js to use a private key and, optionally, deploy to a private RPC like Infura.

```Bash
require('@nomiclabs/hardhat-waffle');
const privateKey = 'xxx';
const projectId = 'xx';

module.exports = {
  defaultNetwork: 'hardhat',
  networks: {
    hardhat: {
      chainId: 1337,
    },
    matic: {
      url: 'https://polygon-mumbai.g.alchemy.com/v2/{projectId}',
      accounts: [privateKey],
    },
  },
  solidity: {
    version: '0.8.4',
    settings: {
      optimizer: {
        enabled: true,
        runs: 200,
      },
    },
  },
};
```

## 👷 Built with

- [Solidity](https://docs.soliditylang.org/en/v0.8.17/ "Solidity"): as Main Coding Language for writing smart contract

- [ReactJs](https://reactjs.org/ "React Js"): as Main Coding Language for Creating The UI components (Front End)

- [TailwindCss](https://tailwindcss.com/ "Tailwind Css"): as Main Coding Language for styling UI components

- [IPFS](https://ipfs.tech/ "IPFS"): For Storing of files

- [Web3 Storage](https://www.google.com/search?q=web3storage "Web3 Storage"): For Storing of files

- [Moralis](https://moralis.io/ "Moralis"): as Tool for creating the chat section

- [Quick Node](https://www.quicknode.com "QuickNode") : Blockchain related APIs

## 🎊 Future Updates

- [ ] Use pandora coin to buy or rent free available premium features such as upgraded streaming quality or content exclusive channels

- [ ] Users can follow artists and receive notifications when new songs or podcasts are released.

- [ ] A live video streaming feature that allows artists to interact with their fans or followers in real time.

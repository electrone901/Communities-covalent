# Communities 🌿

Communities  is a social dApp build from the community to everyone who loves communities parks, flowers, and plants.

Communities is an NFT platform where creators and makers can sell NFTs, set up a profile, and receive tips from the community.

Whenever a viewer goes to the Communities platform will be able to check NFTs works from the different communities, see details from specific NFT and unlock exclusive content.

Overall, users will be able to:

- ask questions or answer them
- give or receive tips for answering questions
- donate money to their favorite garden community
- exchange plants and flowers


We believe that Community garden will create a more strong relationship between community gardens, neighbors, and your own green space.


## Video
https://youtu.be/9RyMDFCMnbE

## Link

https://communities-covalent.netlify.app/
# How it's made
We use:

`Covalent API endpoints` to get all NFTs balance and metadata from a wallet address such us images, contracts name, NFTs images and balances. 

- `NFTStorage`for data storage on IPFS that generates a transation hash used to create an NFT of a photo.

- `textile/eth-storage`: facilitated a fast way to store matadata for Garden comunities such: names, loocations, description, images, wallet address, and more. It was perfect for Garden comunities problem case to save their needs on the textile storage.

- `NFTPort` smooth the path of minting and donating NFTs for Garden comunities. This is a win win situation for our Garden comunities because they don't have to pay to contribute or mint NFTs.

- `Pocket Portal` smooth the path of deploying and hussle of paying such a big transactions to deploy our Garden comunitie's contract to a node using the Rinkeby network.

- `Skynet` facilitated the process of deploying our dApp front-end appliication in a seemless way.

- `Solidity` for the smart contract.

- `OpenZeppelin ERC721` we use the ERC721 template for a faster development of the PetGram smart contract.

- `Ganache` for local blockchain development.

- `Rinkeby Network` the network that we deployed our dApp.

- `React Js, Material-ui, Web3` React Js for the frontend, Material-ui and Web3 to connect to blockchain.



Communities Using Covalent API to Fetch all NFTs from a wallet Address
![Main Page](https://raw.githubusercontent.com/electrone901/Communities-covalent/master/preview.png)

# Getting Started

### `yarn start`

### `yarn build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

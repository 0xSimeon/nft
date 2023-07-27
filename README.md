# Implemenetation of the ERC721 Token Contract (NFTs).  

# About 
This is a foundry project that features two implementations of the ERC-721 token standard.

1.  The first implementation: `BasicNft.sol` is done by inheriting the Openzepplin ERC721 token lib: https://docs.openzeppelin.com/contracts/4.x/api/token/erc721

More details on the ERC721 Non-Fungible Token standard is available [here](https://eips.ethereum.org/EIPS/eip-721)
1.  The second implementation `MoodNft.sol` involves the creation of an ERC721 token contract that mints an NFT based on a storage variable that represents a mood. 
    - Sad mood == sad NFT
    - Happy Mood == happy NFT


# What does the project do?
Creates a standard ERC-721 token with features like: 
- Counting the number of tokens minted per mood
- minting new happy and sad NFTs etc. 
  
# Misc
- Contains scripts to deploy the contract and some initial tests written in Foundry. 

## Tests
Test coverage spanning 100% of the `src` codebase. 



# ERC-4907 Deployment Tutorial

[ERC-4907](https://github.com/ethereum/EIPs/blob/master/EIPS/eip-4907.md) is an extension of [ERC-721](https://github.com/ethereum/EIPs/blob/master/EIPS/eip-721.md). It proposes an additional role (`user`) which can be granted to addresses, and a time where the role is automatically revoked (`expires`). The `user` role represents permission to "use" the NFT, but not the ability to transfer it or set users.

This is the beginner guide to creating and deploying a simple ERC-4907 smart contract on BNB Chain Test Network using ChainIDE, MetaMask, and Solidity.

If you have any questions, feel free to join [ChainIDE Discord!](https://discord.gg/QpGq4hjWrh)


Following are the steps to deploy an ERC-4907 smart contract:

1. Install MetaMask

2. Write down an ERC-4907 smart contract

3. Compile, deploy and Verify

4. List on test.double.one   

### 1. Install MetaMask

When we deploy a smart contract on the blockchain or make a transaction to the deployed smart contract, we need to pay the gas fee, and for that, we need to have a Web3 wallet, which is MetaMask. So, first of all, we'll install MetaMask.

Please click [here](https://metamask.io/) to install MetaMask, and after installing, you need to switch Georli Test Network in  MetaMask. Click [here](https://goerlifaucet.com/) to get some dummy coins for the Georli Test Network( or google "Georli faucet").

![](https://static.double.one/2022/10/18/wjg9ux3543x937e.png)


### 2. Write down an ERC-4907 Smart contract
  
You need to write down all the required functions that you want to implement in your ERC-4907 smart contract. A general ERC-4907 smart contract has the following functions.

-   `setUser()`: set the user and expires of the NFT

-   `userOf()`: returns the user address of the NFT

-   `userExpires()`: returns the user expires of the NFT
  

ChainIDE team has prepared the complete ERC-4907 showcase including all the required functions, you may use that built-in template and add/delete functions according to your requirements.

### 3. Compile, deploy and verify
These steps are the same as the [ERC-721 template](https://chainide.com/s/ethereum/a5263bf7d7d1490e99f2e5e7188708ef?open=readme.md&type=preview) .


### 4. List on test.double.one
Auto-Deployment is a powerful tool on Double Protocol that enables NFT Projects or anyone to instantly deploy ‘NFT collections’ on Double Protocol to enable Rental Service for such NFTs.

Click [here](https://docs.double.one/for-developers/integration-tutorials/nft-rental-auto-deployment) for details.

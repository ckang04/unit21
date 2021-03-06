# Unit 21: Advanced Solidity 

In this exercise, we used Remix to mint a standard ERC20Mintable token, as well as, create a new contract to conduct a crowdsale open to the public. The token name is 'PupperCoin' and the contract is called 'PupperCoinCrowdsale.sol.' To get started, we inherited the following OpenZeppelin contracts:

- Crowdsale
- MintedCrowdsale
- CappedCrowdsale
- TimedCrowdsale
- RefundablePostDeliveryCrowdsale

Other parameters set for all the features of the crowdsale included:

1. Name: **PupperCoin**
2. Symbol: **PUP**
3. Wallet: **0x7a36F290f86d2a87AB52Eaba4Fcc8Ed386c302Fa**
4. Goal: **200**

![Screenshot 1](<a href="https://ibb.co/k6ns8LL"><img src="https://i.ibb.co/dJ9w2NN/Screenshot-17.png" alt="Screenshot-17" border="0"></a>)

![Screenshot 2](<a href="https://ibb.co/YX92JL7"><img src="https://i.ibb.co/KDZ6Brj/Screenshot-18.png" alt="Screenshot-18" border="0"></a>)

Using OpenZeppelin's crowdsale rate calculator as a reference, we set the rate to 1000000000000000000 wei which is equal to 1 Ether. Additionally, the gas limit was set to 3000000. Before we deployed the crowdsale, we went switched our network to Ropsten testnet on MetaMask. We were then able to successfully compile the contracts and deploy the crowdsale! 

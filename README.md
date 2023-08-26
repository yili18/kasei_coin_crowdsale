# KaseiCoin Crowdsale

## The project is create a fungible token called KaseiCoin to allow people who are moving to Mars to convert their earthling money to KaseiCoin.

### Step 1: Create the KaseiCoin token contract.
* Import `ERC20`, `ERC20Detailed`, and `ERC20Mintable` from the `OpenZeppelin` library
* Define a contract for the KaseiCoin token called `KaseiCoin`, and have the contract **inherit** the three contracts imported from `OpenZeppelin`.
* Add a constructor with the following parameters: `name`, `symbol`, and `initial_supply`.
* Add a call to the ERC20Detailed contract’s constructor. Recall that `18` is the value for the decimal parameter.

### Step 2: Create the KaseiCoin crowdsale contract.
* Have this contract inherit the following `OpenZeppelin` contracts: `Crowdsale` and `MintedCrowdsale`
* Within the KaisenCoinCrowdsale constructor, provide parameters such as `rate`, `wallet`, and `token`. 

### Step 3: Create the KaseiCoin deployer contract.
* 


### Step 4: Perform a real-world, pre-production test by using Remix, MetaMask, and Ganache.




### Step 5: Evaluation Evidence - screenshots to show the deployed contract in action.

![Screenshot 1](1.PNG)

![Screenshot 1](2.PNG)






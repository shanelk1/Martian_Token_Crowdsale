# Token_Crowdsale

## Overview of the Project

This is a simple token-crowdsale contract developed using solidity. Creating a fungible token that is ERC-20 compliant and that will be minted by using a Crowdsale contract from the OpenZeppelin Solidity library.

The crowdsale contract is managing the entire crowdsale process, allowing users to send ether to the contract and in return receive KAI, or KaseiCoin tokens. Your contract will mint the tokens automatically and distribute them to buyers in one transaction.



## Project steps using Remix IDE to deploy contract

### Initial Setup Required
- Open the [Remix IDE](https://remix.ethereum.org/)
- Open the KaseiCoin.sol and KaseiCoinCrowdsale.sol files , inspect them to see the code. 
- Compile both the files using compile section  
- Use a [Ganash](https://github.com/trufflesuite/ganache-ui/releases) One-Click blockchain tool to simulate the use of the contract or any Etheruem testnet of your choice.

<img width="1062" alt="Ganach" src="https://user-images.githubusercontent.com/89318890/170892354-7869b07c-3fae-4bf6-b09d-bceb409c8232.png">

### Compile and Deploy 
- After you compile you will notice three contracts in the deploy section.
- Use the KaseiCoinCrowdsaleDeployer.sol file to deploy the contract initially so it can provide the Token and Crowdsale contract addresses to use in the next step.
- Then use the At Address button to deploy the rest of the two contracts from above.

### Buying the token from the Crowdsale
- using the deployed KaseiCoinCrowdsale contract address you can access the buyTokens function to buy tokens , at this point use 1 or more new addresses loaded with Etheruem to make the purchase.
- ***Note*** for the purpose of functionality the contract was programmed with a period of 5 minutes before the crowdsale ends.
- you can also use the finalize function to end the crowdsale and then the tokens can be transfer.

## Demo of how the contract works
<img width="1459" alt="remix deploy" src="https://user-images.githubusercontent.com/89318890/170892463-ebf47d61-69f3-4dde-8174-34e967cec024.png">



- After you compile you will notice three contracts in the deploy section.
<img width="521" alt="Kasei_contracts_3" src="https://user-images.githubusercontent.com/89318890/170892631-ea127522-b575-4ead-bb51-6468b18c14a7.png">

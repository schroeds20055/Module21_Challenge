# KaseiCoin

## Create the KaseiCoin Token Contract


- Code the KaseiCoin contract. 
- Take a screenshot of the successful compilation of the contract, and add it to the Evaluation Evidence section of the README.md file for your Challenge repository.



## Create the KaseiCoin Crowdsale Contract (15 points)

- Have your KaseiCoinCrowdsale contract inherit the OpenZeppelin Crowdsale and MintedCrowdsale contracts. 
- Add the rate, wallet, and token parameters to your crowdsale contract’s constructor. 
- Take a screenshot of the successful compilation of the contract, and add it to the Evaluation Evidence section of the README.md file for your Challenge repository. (5 points)



## Create the KaseiCoin Deployer Contract (35 points)

- Add variables to the KaseiCoinCrowdsaleDeployer contract that can store the KaseiCoin and KaseiCoinCrowdsale contract addresses. 
- Add the name, symbol, and wallet parameters to the KaseiCoinCrowdsaleDeployer contract’s constructor.
- Add the required code within the constructor’s body.
- Take a screenshot of the successful compilation of the contract, and add it to the Evaluation Evidence section of the README.md file for your Challenge repository. (5 points)



## Deploy the Crowdsale to a Local Blockchain 

- Record a short video or take screenshots as evidence of your deployed crowdsale contract. The video or screenshots should illustrate the following: 
    - Deployment of the contract to a local blockchain with Remix, MetaMask, and Ganache.
    - Using test accounts to buy new tokens from the crowdsale and then checking the balances associated with the test accounts.
- After purchasing tokens with test accounts, viewing the total supply of minted tokens and the amount of wei that has been raised by the crowdsale.

IMPORTANT
If you provide screenshots, add them to the README.md file of your Challenge repository. The screenshots should provide a guide that someone else could use to compile the contracts and add the KaseiCoin token to MetaMask.

Coding Conventions and Formatting (10 points)
To receive all points, you must:

Place imports at the top of the file. (3 points)

Name functions and variables using mixedCase, as stated in the Solidity Language Style Guide (Links to an external site.). (2 points)

Follow DRY (Don't Repeat Yourself) principles, creating maintainable and reusable code. (3 points)

Use concise logic and creative engineering where possible. (2 points)
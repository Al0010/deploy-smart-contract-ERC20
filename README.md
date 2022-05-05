# Deploy Smart Contract ERC20
Deploy your ERC-20 Token on Binance Smart Chain (Test Net) using Remix-Ethereum IDE.

You can easily practise deploying a simple ERC20 token on any test network. In this example we use the Binance Smart Chain (Test Net). 

# What you'll need to get started 
1) Knowledge of Solidity 
2) Knowledge of Remix Ethereum IDE 
3) Knowledge of Meta Mask 
4) How a smart contract works 
5) Knowledge of the ERC20 token.

When working with a cryptographic asset it is important that the code is tested thoroughly and above all that it is written correctly. 

We therefore use the Open Zeppelin library, which provides the possibility of using source code that has already been tested and approved by the community. This will provide a token that runs on a verified smart contract and is therefore not vulnerable to security attacks. 

You can find the code at this link (Open Zeppelin provides several additional features such as burning, minting, governance and much more): https://docs.openzeppelin.com/contracts/4.x/wizard

In this example we will deploy an ERC20 Token with simple value transfer functionality. 

# To proceed you will need:
1) Remix Ethereum IDE
2) Meta Mask account set up on BSC network (TestNet)
(https://user-images.githubusercontent.com/100917872/166955206-0e2ab884-5aa4-4b91-8746-c05ed07d5faa.png)
3) Some test BNBs inside your Meta Mask

The code has been cleaned up, it contains a first task that is used to call the functions contained in the Open Zeppelin ERC-20 contract on the Ethereum network. As you scroll down you will find a second constructor task that will give you the ability to insert your token data into the function. 

The data you will need to enter are: 

1) Token Name 
2) Number of tokens to create 

To enter the name of your token, remove "Prova" from the constructor and inside the brackets and replace it with the name of your token.
Insert the ticker inside the round brackets after the name "Prova", instead of "PRV".
To enter the number of tokens in circulation, remove 10000 and enter the number of tokens you want to create. 

# Deploy
1) Open Remix Ethereum IDE 
2) Copy the code 
3) Edit the parameters as described above 
4) Set the Ethereum version: "0.8.7+commit.e28d00a7"
(https://user-images.githubusercontent.com/100917872/166955409-1ac4a047-c7d8-4f61-a485-d82a0596dcf2.png)
5) Click on "Compile".
6) In the deployment area set the version to "Injected Web3"
https://user-images.githubusercontent.com/100917872/166954582-5b7860bd-0caa-4e41-a546-b20440319cfb.png
7) Choose your smart contract from the drop-down menu 
8) Click on "Deploy"

# Token 
It is possible that your Meta Mask does not detect your token!
To resolve this, simply copy the smart contract address of your token and import it into the Meta Mask smart contract area. 
[Schermata 2022-05-05 alle 17 13 39](https://user-images.githubusercontent.com/100917872/166955704-ec7f5a7e-59f8-48c9-9ffa-5f5180b85229.png)

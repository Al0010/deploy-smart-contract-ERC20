# Deploy Smart Contract ERC-20
Deploy your ERC-20 Token on Ropsten Test Net using Remix-Ethereum IDE.

You can easily practise deploying a simple ERC20 token on any test network. In this example we use test net. 

We therefore use the Open Zeppelin library, which provides the possibility of using source code that has already been tested and approved by the community. This will provide a token that runs on a verified smart contract and is therefore not vulnerable to security attacks. 

You can find the code at this link (Open Zeppelin provides several additional features such as burning, minting, governance and much more): 
https://docs.openzeppelin.com/contracts/4.x/wizard

In this example we will deploy an ERC-20 Token with simple value transfer functionality. 

# To proceed you will need:
1) Remix Ethereum IDE
2) Meta Mask account set up on Ropsten Network
![Schermata 2022-05-05 alle 17 09 34](https://user-images.githubusercontent.com/100917872/167030558-48f0aad3-a660-42f4-93ef-940fb2d56fa1.png)
3) Some test ETH inside your Meta Mask

The code has been cleaned up, it contains a first task that is used to call the functions contained in the Open Zeppelin ERC-20 contract on the Ethereum network. As you scroll down you will find a second constructor task that will give you the ability to insert your token data into the function. 

The data you will need to enter are: 

1) Token Name 
2) Number of tokens to create 

# Deploy
1) Open Remix Ethereum IDE 
2) Copy the code 
3) Edit the parameters as described above 
4) Set the Ethereum version: "0.8.7+commit.e28d00a7"
(https://user-images.githubusercontent.com/100917872/166955409-1ac4a047-c7d8-4f61-a485-d82a0596dcf2.png)
5) Click on "Compile".
6) In the deployment area set the version to "Injected Web3"
![Schermata 2022-05-05 alle 17 09 34](https://user-images.githubusercontent.com/100917872/167030558-48f0aad3-a660-42f4-93ef-940fb2d56fa1.png)
7) Choose your smart contract from the drop-down menu 
8) Click on "Deploy"

# Token 
It is possible that your Meta Mask does not detect your token.
To resolve this, simply copy the smart contract address of your token and import it into the Meta Mask smart contract area. 


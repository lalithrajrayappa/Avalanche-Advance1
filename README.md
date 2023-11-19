# ERC20 DEFI game

In this advance module project, I have created a ERC20 defi game contract and deployed it to local avalanche subnet.

## Description

The solidity contract that is pushed contains the code for the ERC20 defi game. This defi game contains an additional outfit change function apart from the ERC20 functions(mint,burn,approve,transfer,etc.). In this outfit change function , you can enter a valid choice with each choice corresponding to an outfit and the player changes his/her outfit accordingly. I have deployed this game contract to avalanche subnet locally.

 ## Getting Started
 
 ### Installing code

 You can clone this repo or download zip file and run it locally or you can run the code on remix 

 Head over to this website: https://remix.ethereum.org/.
 ### Executing the code

Once you are on the Remix website, create a new file by clicking on the "+" icon in the left-hand sidebar. Save the file with a .sol extension (e.g., ERC20game.sol). Copy and paste the solidity file into the remix file

To compile the code, click on the "Solidity Compiler" tab in the left-hand sidebar. Make sure the "Compiler" option is set to "0.8.17" (or above version), and then click on the "Compile ERC20game.sol" button.

Once the code is compiled, you can deploy the contract by clicking on the "Deploy & Run Transactions" tab in the left-hand sidebar. Select the "solidity" contract from the dropdown menu, change the environment to 'Injected provider' and connect your metamask account, and then click on the "Deploy" button.

### Subnet 
 
Follow the below github repository's readme file in order to install avalanche CLI to your Ubuntu or Mac terminal:
 
 [https://docs.avax.network/tooling/cli-guides/install-avalanche-cli](https://github.com/ava-labs/avalanche-cli)

In order to create a subnet, we run -

```
avalanche subnet create mySubnet
```

In order to deploy the created subnet, we run -

```
avalanche subnet deploy mySubnet
```

To connect your subnet to metamask, you will need to :

* Add network manually and enter Name, RPC URL, Token Symbol and Chain ID that you entered while creating the subnet.
* Import account with test tokens by entering the private key that you get from the terminal after you deploy the subnet.
 
 ## Authors
 
 Lalith R
 
 [@lalithrajrayappa@gmail.com]
 
 ## License
 
 This project is licensed under the MIT License - see the LICENSE.md file for details
 
 

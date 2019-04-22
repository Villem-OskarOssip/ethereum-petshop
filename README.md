# PetShop Example using Ethereum
This is an example project that is running a petshop using Ethereum.
This project has been created in educational purpose. This demo was created by Truffle Suite ([link](https://truffleframework.com/tutorials/pet-shop) to original materials)

Follow the below documentation to run the Ethereum petshop example on Ethereum.

**Make sure to run all commands in the ethereum-petshop directory.**

## Reqirements.
* Git
* Truffle
* [Node](https://nodejs.org/en/)
* [Ganache](http://truffleframework.com/ganache/)

## Install Truffle
Enter this to terminal to install Truffle:
```npm install -g truffle```

## How to run project with out injected web3 instance
1. Compile ```truffle compile```
2. Start Ganache
3. Select Quickstart from Ganache
3. Run migrations ```truffle migrate```
4. Run tests ```truffle test```

# Interacting with the dapp in a browser
Now we're ready to use our dapp!
Visit Truffle [webpage](https://truffleframework.com/tutorials/pet-shop) to see Metamask installation instructions.

## Using the dapp

0. Make sure Ganache is running and Metamask is configured (Metamask is optional. Project also work without Metamask)
1. Compile ```truffle compile```
3. Run migrations ```truffle migrate```
3. Start the dapp ```npm run dev```

The dev server will launch and automatically open a new browser tab containing your dapp.
![Pete's Pet Shop](https://truffleframework.com/img/tutorials/pet-shop/dapp.png)

4. A MetaMask pop-up should appear requesting your approval to allow Pete's Pet Shop to connect to your MetaMask wallet. Without explicit approval, you will be unable to interact with the dapp. Click Connect.
![MetaMask approval request](https://truffleframework.com/img/tutorials/pet-shop/metamask-transactionconfirm.png)

5. To use the dapp, click the Adopt button on the pet of your choice.

6. You'll be automatically prompted to approve the transaction by MetaMask (If you are not using Metamask then transaction will take place with out second confirmation (check Ganache UI or terminal)). Click Submit to approve the transaction.
![Adoption success](https://truffleframework.com/img/tutorials/pet-shop/dapp-success.png)

And in MetaMask, you'll see the transaction listed:
![MetaMask transaction](https://truffleframework.com/img/tutorials/pet-shop/metamask-transactionsuccess.png)

You'll also see the same transaction listed in Ganache under the "Transactions" section.

Congratulations you are not a retard!
![Coockie](https://lh3.ggpht.com/PeMzkGiu5eqdh2LhYapIw7Mz85oE6WhgIxGq6uufEs91eFtB5KzLl4uj2Gey7BFalaAWS8hp_TWD-dLhSJkgLdrvK1ef=s0)

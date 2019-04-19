# PetShop Example using Ethereum
This is an example project that is running a petshop using Ethereum.
This project has been created in educational purpose.

Follow the below documentation to run the Ethereum petshop example on Ethereum.

**Make sure to run all snak commands in the ethereum-petshop' directory.**

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

## How to run project with out injected web3 instance (Metamask)
1. Install Google Chrome
2. Open Google Chrome
3. Start Ganache and select quick start
4. Install [MetaMask](https://chrome.google.com/webstore/detail/metamask/nkbihfbeogaeaoehlefnkodbefgpgknn). Once installed, a tab in your browser should open displaying the following:
![Metamask welcome](https://truffleframework.com/img/tutorials/pet-shop/metamask-welcome.png)
5. After clicking Getting Started, you should see the initial MetaMask screen. Click Import Wallet.
![MetaMask initial screen](https://truffleframework.com/img/tutorials/pet-shop/metamask-initial.png)
5. Next, you should see a screen requesting anonymous analytics. Choose to decline or agree.
![Improve MetaMask](https://truffleframework.com/img/tutorials/pet-shop/metamask-analytics.png)
6. In the box marked Wallet Seed, enter the mnemonic that is displayed in Ganache.
![MetaMask seed phrase](https://truffleframework.com/img/tutorials/pet-shop/metamask-seed.png)
7. If all goes well, MetaMask should display the following screen. Click All Done.
![MetaMask Congratulations](https://truffleframework.com/img/tutorials/pet-shop/metamask-congratulations.png)
8. Now we need to connect MetaMask to the blockchain created by Ganache. Click the menu that shows "Main Network" and select Custom RPC.
![MetaMask network menu](https://truffleframework.com/img/tutorials/pet-shop/metamask-networkmenu.png)
9. In the box titled "New Network" enter http://127.0.0.1:7545 and click Save.
![MetaMask Custom RPC](https://truffleframework.com/img/tutorials/pet-shop/metamask-customrpc.png)
10. Click the top-right X to close out of Settings and return to the Accounts page.
Each account created by Ganache is given 100 ether. You'll notice it's slightly less on the first account because some gas was used when the contract itself was deployed and when the tests were run.
![MetaMask account configured](https://truffleframework.com/img/tutorials/pet-shop/metamask-account1.png)

1. Compile ```truffle compile```
3. Run migrations ```truffle migrate```
3. Start the dapp ```npm run dev```




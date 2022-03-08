## First install following dependency:
-MetaMask extension(https://metamask.io/) .Also download MetaMask Legacy Web3 extension to run web3 api(as it is depreacted).

-Also install ganche to create your own blockchain network.

-Also install truffle to run your smart contract using this command: npm install -g truffle@5.0.2
## To run the project:
-Open Ganche and select/create network.

-Then run the following command to deploy the contract:
```truffle build && truffle migrate```

-Open MetaMask extension and login to your MetaMask account.

-Then change the network to localhost:7545 ie  HTTP://127.0.0.1:7545

-Run the following command to run the project: ```npm install && npm run dev```
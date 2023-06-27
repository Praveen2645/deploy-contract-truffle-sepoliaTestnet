# deploy-contract-truffle-sepoliaTestnet
here deployed the contract on sepolia testnet using the truffle development tool

1.npm install -g truffle -(to install truffle)
2.truffle init (to get the required files)
3.write your contract
4.write the migration and testing files.
5.create app on Alchemy or Infura for fetching the "key" and "url"
6.install few more dependencies like

npm install dotenv --save
$ npm install --save-dev @truffle/hdwallet-provider
7.update your truffle config file by putting the MNEMONIC(from your metamask) and key(from your alchemy or infura)
NOTE: keep your MNEMONIC and KeyId in seprate file by creating .env file
8.after updating the config files , you are ready to deploy contract on testnet by following command
truffle migrate --network sepolia --reset



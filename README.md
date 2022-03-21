# This NFT Project build using React and Soldity. The UI framework is Tailwind css. 

This project demonstrates a basic Hardhat use case. It comes with a sample contract, a test for that contract, a sample script that deploys that contract, and an example of a task implementation, which simply lists the available accounts.




RUunning some of the following testnet:
# npm install
# npx hardhat node  --> after that
# npx hardhat run scripts/deploy.js --network localhost
``` 
then add open and close single quotes for both  export const nftmarketaddress and export const nftaddress

```
# npm run dev

# connect to http://localhost:3000/

# connect to metamask wallet 

# Finally test your NFT !!!

``` change the network to localhost 8545 ```

# Remember change the following a index.js file from testing to live net if want go live

```  const provider = new ethers.providers.JsonRpcProvider() to 
  const provider = new ethers.providers.Web3Provider(web3.currentProvider)
```
# below are basic 
```shell
npx hardhat accounts
npx hardhat compile
npx hardhat clean
npx hardhat test
npx hardhat node
node scripts/sample-script.js
npx hardhat help
```

Basic Decentralized Greeter App, Using HardHat EDE.
- In first commit it is hosted in Hardhat local Test Network
- In Second commit it is hosted in Robsten test Network using Moralis

Steps to be followed to run this application in your Local Machine.
- **Step 1:** Clone the project and save it in your local disk.
- **Step 2:** Open your terminal inside the project directory and run --- npm i
- **Step 3:** Sign up in Moralis and Copy the end point for Eth node from Speedy nodes.
- **Step 4:** Setup your metamask wallet, change the network to robsten and export the private key.
- **Step 5:** Go to the secret.json file and change the key with your private key and url with the moralis end point.
- **Step 6:** Run command ---npx hardhat run scripts/deploy.js --network ropsten , you can see the address of deployed smart contract, copy it.
- **Step 7:** Go to src/app.js and change the greeterAdress with your new deployed address.
- **Step 8:** Run npm start in your terminal. 
- **You are done, your smart contract will open in localhost:3000 with a frontend.**
- (To interact with the smart contract, make sure to fill your Robsten network with some test ethers)


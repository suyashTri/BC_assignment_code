Step 1: Copy the project id of your infura account and paste it in .env file as INFURA_TOKEN

Step 1: Run npm i to install all the dependencies of the node module

Step 2: Copy the Deployed Contracts code in remix IDE.

Step 3: Compile the code and deploy it in Injected Web3 Environment

Step 4: Copy the contract address and paste it into the .env file as CONTRACT_ADDRESS

Step 5: Copy the account address and paste it into the .env file as OWNER_ADDRESS

Step 6: Export private key from your metamask account and paste it in .env file as SUPER_SECRET_PRIVATE_KEY

Step 7: Write the  MetaMask wallet address of all the accounts where tokens needs to be distribute in accounts.txt

Step 8: Run node distribute.js in the terminal to send 5% of the tokens to all the listed accounts evenly.

# Solana Memecoin Maker

Solana memecoin maker.

### Installation
Clone repository. 
```
git clone https://github.com/thearkabanerjee/memecoin-maker.git
```

Install dependencies. 
```
yarn install
```

### Instructions

The code needs a Solana wallet to create the memecoin.
Set up any wallet and copy/paste the Private Key into `keygen.js`.
Run the following to generate the `keypair.json` credentials.
```
yarn keygen
```

#### Creating the memecoin
1. Upload image.
2. Upload metadata.
3. Mint token

Refer to the bottom of `index.js` and uncomment the step you want to run. Run the following to start the program.
```
yarn start
```

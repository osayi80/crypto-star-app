
# Decentralized Star Notary Project
This project is about building a Cryptostar DAPP on Ethereum

## Contract Functions

<u>Default functions that came with starter code</u>

    createStar()

    putStarUpForSale()

    make_payable()

    buyStar()

<u>Newly created functions</u>

    lookUptokenIdToStarInfo()

    exchangeStars()

    transferStar()

---

### Token and Version Details

ERC-721 Token Name: Star Token

ERC-721 Token Symbol: STN

Version of Truffle used: 5.1.24

Version of OpenZeppelin used: 3.0.1

Token Address: d5c6c315314f4381afa96290337a482b

truffle-hdwallet-provider@1.0.17
Node 12.16.3



### Deploying Contract to local running Ethereum network

1. Install truffle

    npm -g install truffle

2. Run truffle develop in the project repo:

    truffle develop

You should see truffle running on http://127.0.0.1:9545/ with a development console

3. To compile the contract, inside the development console, run:

    compile

 4. To migrate the contract to the locally running Ethereum network, inside the development console, run:

    migrate --reset

5. To test the StarNotary contract with TestStarNotary.js inside the development console, run:

    test

__Note__ you will need web3 for the Front End of the DAPP, this should automatically install with truffle. But if you have problems with webpack-dev-server. Find that module in app/node_modules/webpack-dev-server and delete it.
Then run   <br>   ```npm install webpack-dev-server```

6. Open another terminal window and go inside the project directory, and run:

    cd app

    npm run dev

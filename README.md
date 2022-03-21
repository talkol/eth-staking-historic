# Historic Staking on Ethereum

A simple script to extract historic staking value in various protocols on Ethereum and similar chains. The script relies on on-chain data only and uses an archive node to run state queries on a specific historic date.

`api3.js` - API3 DAO single staking pool

## Instructions

1. Make sure you have Node.js installed and run in terminal:
    ```
    npm install
    ```

2. Go over the code (api3.js) and review all the TODOs

3. Run in terminal (replacing 0x2faf487a4414fe77e2327f0bf4ae2a264a776ad2 with your wallet address):
    ```
    node api3 0x2faf487a4414fe77e2327f0bf4ae2a264a776ad2 > output-api3.csv
    ```

4. Open `output-api3.csv` in Excel
# Oracle-Contract

<h3>An Oracle Smart Contract demo with a web UI:</h3>

<p><b>Follow these steps to setup the contract with the web UI:</b></p>

1. Setup Ganache or ganache-cli -d, and change "/express/index.js:3" from 8545 to 7545 if needed
2. Compile StockPrices.sol and deploy
3. cd into "/express" and "npm i", then perform "node index"
4. In a separate shell, cd into "/react" and "npm i", then perform "npm start"
5. If not auto-launched, navigate to http://localhost:3000
6. Open the browser console, and for the "Symbol", enter "0x41424344" without quotes
7. Click "Get" buttons to read from the contract using the oracle (output to browser console)
8. Enter Price and Volume and click "Set" button to write to the contract using the oracle (tx hash in browser console)

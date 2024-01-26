#  Token Transaction Tracker Twitter Bot with Etherscan 
This project is a Node.js Twitter bot that leverages the Etherscan API to track large Token transactions and automatically posts tweets about them.

## Features:
- Monitors transactions on the Ethereum blockchain for a specific Token contract address.
- Filters for transactions exceeding a configurable minimum threshold.
- Creates tweets containing details like sender and receiver addresses, amount transferred, and transaction URL.
- Posts tweets on a configurable interval (5 seconds by default) using Twitter API v2 with OAuth 2.0 authentication.

## Setup:
- Clone the repository.

- Install dependencies: 
    `npm  install`

- Configure your Twitter API credentials and Etherscan API key in the bot.js file.
- Adjust the minimum Token value threshold and tweet posting interval if desired.
- Run the bot: `node bot.js`


### Usage:
The bot will run continuously, fetching data from Etherscan, processing transactions, and posting tweets about significant Token transfers. You can also view the console logs for more details of its activity.
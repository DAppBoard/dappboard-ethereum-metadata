# ethereum-tokens
A repository of ERC20 Token information

## Tokens

Tokens informations are directly scraped from the blockchain. You can find how we are doing it in the [DAppBoard Ethereum ETL](https://github.com/DAppBoard/dappboard-etl/blob/master/etl/utils/token_scraper.js).

If you need token images, we are using ourself and contributing to [this repo from TrustWallet](https://github.com/TrustWallet/tokens).

#### ERC20

ERC20 tokens are available [here](https://raw.githubusercontent.com/DAppBoard/dappboard-ethereum-metadata/master/tokens/erc20_list.csv). The column names are **address**, **name**, **symbol**, **decimals** (the number of 0 to get the floating values during transfers).

#### NFTs

NFTs tokens are available [here](https://raw.githubusercontent.com/DAppBoard/dappboard-ethereum-metadata/master/tokens/erc20_list.csv). The column names are **address**, **name**, **symbol**.

## Events

Events are caracterized by their log topic, their name and the parameters they accept. You can find the CSV [here](https://raw.githubusercontent.com/DAppBoard/dappboard-ethereum-metadata/master/events/events.csv). The column names are **topic**, **name** and **parameters** (a json object).


### License

This project is licensed under the [MIT License](https://opensource.org/licenses/MIT).

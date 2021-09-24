# ERC20 Balance Checker challenge 

This challenge aims at creating and deploying a simple application to check the balance of an Ethereum wallet on some popular ERC20 tokens.

The application shall have a front-end asking for the wallet address and offering a list of the ten most popular ERC20 tokens.
Additional tokens may be added to the list using their contract address.

A serverless back-end shall connect to the Ethereum blockchain to provide basic information for the tokens in the list (name, symbol, decimals) and the properly formatted balance for the wallet on those of them that were selected and/or added.

A direct connection to an RPC endpoint (Infura offers a free option) using web3js, web3j or ethersjs shall be preferred over third party approaches.

For testing purposes you may use Vitalik's wallet (0x6b175474e89094c44da98b954eedeac495271d0f), he holds many different coins such as DAI, SHIB, UBI and others. 

Please see this Tips if using Java: [JavaTips.md](JavaTips.md)

## Stack
- VueJs (preferred) or other front-end JS framework
- NodeJs or Java
- AWS Lambda for serverless backend deployment
- AWS S3 or AWS Cloudfront for front-end hosting

## Optional Extra Goals
- Document API in Swagger/OpenAPi format
- Support ERC721 / ERC1155 balances
- Script Lambda / S3 deployment or use a framework such as SLS or SAM
- Warmup the lambdas

When done please contact amazza@signerstech.com or @AdrianHMazza on twitter.

Enjoy coding!
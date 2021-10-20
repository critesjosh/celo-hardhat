# Basic Sample Hardhat Project -- Deploy to Celo

This project demonstrates a basic Hardhat use case with configuration to deploy to [Celo](https://celo.org). It comes with a sample contract, a test for that contract, and a sample script that deploys that contract.

Try running some of the following tasks:

```shell
npx hardhat compile
npx hardhat clean
npx hardhat test
node scripts/sample-script.js
npx hardhat help
```

## Differences between Hardhat Environment and Celo

The built in hardhat environment is designed to work with the Ethereum version of the EVM. Celo also runs the EVM, but includes additional fields in the transaction object to support paying transaction fees in currencies other than the native one (like CELO or ETH) and paying full node incentives. The Hardhat environment does not include Celo's protocol contract either. It may still be useful for running contract tests, but just be aware that there are some differences.

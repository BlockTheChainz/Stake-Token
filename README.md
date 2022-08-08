# Steps needed to run code:

To create hardhat environment with .env / .secret addition

  [Check out this hardhat env starter!!](https://github.com/smartcontractkit/hardhat-starter-kit)

Install packages

```
npm install @typechain/ethers-v5 @typechain/hardhat @types/chai @types/node @types/mocha ts-node typechain typescript
```


To compile contracts:

```
npx hardhat compile
```

To deploy contracts:
```
npx hardhat run --network <network> scripts/<nameOfFile>.js
```
In case of lack of dependencies follow the erros inside hardhat env while compiling and just simply install all of them.

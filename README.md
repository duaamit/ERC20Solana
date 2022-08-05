# ERC20Solana


Baisc implementtaion of ERC20 contract written in Solidity using Solang. Solang can compile Solidity for Solana, Substrate, and ewasm. 
Solang is source compatible with Solidity 0.8.

Steps:

#Install Solang for Mac:

```
brew install hyperledger-labs/solang/solang
```

#build using below command to produce `erc20.abi` and `bundle.so`:

```
solang --target solana erc20.sol
```

#install 
```
npm install @solana/solidity
```

#now run:
```
node erc20.js
```

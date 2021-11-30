# multisig24
MultiSignature wallet with 24h for signing

Multisignature wallet is a crypto wallet on the blockchain, which supports multiple owners (custodians), who are authorized to manage the wallet.

## For easy manage smartcontract you can use [TONDev](https://github.com/tonlabs/tondev#tondev)

## 1. Compile
```bash
tondev sol compile SafeMultisigWallet24.sol
```
## 2. Create seed phrases and public keys for all custodians

## 3. Set network https://github.com/tonlabs/tondev#add-a-network

## 4. Set signer https://github.com/tonlabs/tondev#signer-tool

## 5. Check contract address and charge it from any wallet
```bash
tondev contract info SafeMultisigWallet24.sol
```
## 6. Deploy contract to blockchain
```bash
tondev contract deploy SafeMultisigWallet24.sol
```
## 6. Read your contract info from blockchain
```bash
tondev contract run-local SafeMultisigWallet24.sol
```
## 7. Manage your contract on-chain
```bash
tondev contract run SafeMultisigWallet24.sol
```




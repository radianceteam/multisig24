# multisig24
MultiSignature wallet with 24h for signing

Multisignature wallet is a crypto wallet on the blockchain, which supports multiple owners (custodians), who are authorized to manage the wallet.

### For easy manage smartcontract you can use [TONDev](https://github.com/tonlabs/tondev#tondev)

### 1. Build by version
```bash
TONDev Version: 0.10.5

Solidity compiler 
Component  Version   
---------  --------  
compiler   0.52.0    
linker     0.13.103  
stdlib     0.52.0  
```
### 2. Compile
```bash
tondev sol compile SafeMultisigWallet24.sol
```
### 3. Create seed phrases and public keys for all custodians

### 4. Set network https://github.com/tonlabs/tondev#add-a-network

### 5. Set signer https://github.com/tonlabs/tondev#signer-tool

### 6. Check contract address and charge it from any wallet
```bash
tondev contract info SafeMultisigWallet24.abi.json
```
### 7. Deploy contract to blockchain
```bash
tondev contract deploy SafeMultisigWallet24.abi.json
```
### 8. Read your contract info from blockchain
```bash
tondev contract run-local SafeMultisigWallet24.abi.json
```
### 9. Manage your contract on-chain
```bash
tondev contract run SafeMultisigWallet24.abi.json
```




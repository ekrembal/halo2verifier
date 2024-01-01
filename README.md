# Solidity verifier

```bash
DAPP_BUILD_OPTIMIZE=0 forge build
```

Test:

```bash
DAPP_BUILD_OPTIMIZE=0 forge test
```

Deploy to sepolia:

```bash
DAPP_BUILD_OPTIMIZE=0 forge create --rpc-url https://rpc2.sepolia.org \
    --private-key <PRIVATE_KEY> \
    --etherscan-api-key <ETHERSCAN_API_KEY> \
    --verify \
    src/Halo2Verifier.sol:Halo2Verifier
```
## Getting Started

1. Go to [Remix](https://remix.ethereum.org/)
2. Paste the code from `FundMe.sol` and `PriceConverter.sol` into new files in Remix
3. Hit `Compile`
4. Hit `Deploy`

For a more in depth blog on working with remix, [read here](https://docs.chain.link/docs/deploy-your-first-contract/)

Fallback and receive functions

```
fallback() external payable {
        
    }

    receive() external payable {
        
    }
```

Using library

```
contract FundMe {
    using PriceConverter for uint256;
...
```
```
library PriceConverter {
...
```


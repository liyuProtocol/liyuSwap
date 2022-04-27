# liyuSwap Interface

## Development

### Install Dependencies

```bash
yarn
```

### Run

```bash
yarn start
```

UniswapV2Factory
https://cn.etherscan.com/address/0x5c69bee701ef814a2b6a3edd4b1652cb9cc5aa6f#code

UniswapV2Router02
https://cn.etherscan.com/address/0x7a250d5630b4cf539739df2c5dacb4c659f2488d#code

weth合约
https://cn.etherscan.com/address/0xc02aaa39b223fe8d0a0e5c4f27ead9083c756cc2#code

Multicall合约
https://cn.etherscan.com/address/0x5e227ad1969ea493b43f840cff78d08a6fc17796#code



web：uniswap-inteface

uniswap-sdk 
https://github.com/Uniswap/v2-sdk/tree/00a1eca9456d37c3d467f56e57a0496d1bf28e40


给工厂合约的主合约添加：
bytes32 public constant INIT_CODE_PAIR_HASH = keccak256(abi.encodePacked(type(UniswapV2Pair).creationCode));

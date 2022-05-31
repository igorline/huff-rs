<img align="right" width="150" height="150" top="100" src="./assets/huff.png">

# rhuff • [![tests](https://github.com/abigger87/rhuff/actions/workflows/tests.yaml/badge.svg)](https://github.com/abigger87/rhuff/actions/workflows/tests.yaml) [![lints](https://github.com/abigger87/rhuff/actions/workflows/lints.yaml/badge.svg)](https://github.com/abigger87/rhuff/actions/workflows/lints.yaml) ![GitHub](https://img.shields.io/github/license/abigger87/rhuff)  ![Crates.io](https://img.shields.io/crates/v/rhuff)

Huff is a low-level programming language designed for developing highly optimized smart contracts that run on the Ethereum Virtual Machine (EVM). Huff does not hide the inner workings of the EVM. Instead, Huff exposes its programming stack to the developer for manual manipulation.

Rather than having functions, Huff has macros - individual blocks of bytecode that can be rigorously tested and evaluated using the Huff runtime testing suite.

Initially developed by the Aztec Protocol team, Huff was created to write Weierstrudel. [Weierstrudel](https://github.com/aztecprotocol/weierstrudel/tree/master/huff_modules) is an on-chain elliptical curve arithmetic library that requires incredibly optimized code that neither [Solidity](https://docs.soliditylang.org/en/v0.8.14/) nor [Yul](https://docs.soliditylang.org/en/v0.8.9/yul.html) could provide.

While EVM experts can use Huff to write highly-efficient smart contracts for use in production, it can also serve as a way for beginners to learn more about the EVM.



## Usage

**Build**
```bash
cargo build
```

**Run Tests**
```bash
cargo test
```


## Blueprint

```ml
utils
├─ refactored utilities
lexer
├─ 
```


## Contributing

All contributions are welcome! We want to make contributing to this project as easy and transparent as possible, whether it's:
  - Reporting a bug
  - Discussing the current state of the code
  - Submitting a fix
  - Proposing new features
  - Becoming a maintainer

We use GitHub issues to track public bugs. Report a bug by [opening a new issue](https://github.com/abigger87/rhuff/issues/new); it's that easy!


## References

- [huffc](https://github.com/huff-language/huffc)
- [ripc](https://github.com/ibraheemdev/ripc)
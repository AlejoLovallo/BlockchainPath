# The Blockchain path

* A set of blockchain resources along with some snippets. Developer view. 

*******************

## Smart Contracts

### Basics

* Function types:
	* [sc-function-types-I](https://medium.com/@yangnana11/solidity-function-types-4ad4e5de6d56#:~:text=Internal%20functions%20can%20only%20be,context%20of%20the%20current%20contract)
	* [External vs public](https://ethereum.stackexchange.com/questions/19380/external-vs-public-best-practices)
	* [Overrides modifier](https://docs.soliditylang.org/en/latest/contracts.html#function-overriding)

* Variables: 
	* [I](https://betterprogramming.pub/learn-solidity-variables-part-1-657fc27c2cc1)
	* [II](https://betterprogramming.pub/learn-solidity-variables-part-2-f3b842f5bfb8)

* Fallback functions:
	* [Fallback](https://medium.com/upstate-interactive/the-truth-about-fallback-functions-in-solidity-a2c604f8e66b)
	* [Fallback II](https://www.tutorialspoint.com/solidity/solidity_fallback_function.htm)

* [Interfaces](https://www.geeksforgeeks.org/solidity-basics-of-interface/)

* [Libraries](https://jeancvllr.medium.com/solidity-tutorial-all-about-libraries-762e5a3692f9#:~:text=A%20library%20in%20Solidity%20is,in%20a%20more%20modular%20way)

* Testing: 
	* [Technical guide on how to write good unit tests in sc](https://medium.com/upstate-interactive/a-simple-guide-for-how-to-write-unit-tests-for-smart-contracts-8ec4b645f57b)

### Advanced

* [DelegateCalls](https://medium.com/coinmonks/delegatecall-calling-another-contract-function-in-solidity-b579f804178c)

* Upgradable SC: 
	* [Not all contracts are inmutable](https://betterprogramming.pub/not-all-smart-contracts-are-immutable-create-upgradable-smart-contracts-e4e933b7b8a9)
	* [Detailed explanation and Oz implementation](https://simpleaswater.com/upgradable-smart-contracts/)
	* [CardStack in-house solution](https://medium.com/cardstack/upgradable-contracts-in-solidity-d5af87f0f913)

* [Hooks](https://docs.openzeppelin.com/contracts/3.x/extending-contracts)

* [Bytes I (official doc)](https://www.tutorialspoint.com/solidity/solidity_strings.htm)
* [Bytes II (old post)](https://medium.com/@libertylocked/what-are-abi-encoding-functions-in-solidity-0-4-24-c1a90b5ddce8)
* [Bytes III (more complete)](https://docs.soliditylang.org/en/latest/contracts.html#function-overriding)

* [Abstract vs Interfaces](https://medium.com/upstate-interactive/solidity-how-to-know-when-to-use-abstract-contracts-vs-interfaces-874cab860c56)

* [Integration with Oz contracts](https://docs.openzeppelin.com/contracts/3.x/extending-contracts)

* [Pausable Example Contract](https://fravoll.github.io/solidity-patterns/emergency_stop.html)


### Security 

* [Reentracy](https://blockman.medium.com/reentrancy-a-vulnerability-that-causes-your-solidity-smart-contract-to-be-withdrawn-all-money-f4a9f6cdc57)
* [Reentrancy after Istanbul fork](https://blog.openzeppelin.com/reentrancy-after-istanbul/)

### Gas optimizations 

* [Gas tips](https://mudit.blog/solidity-gas-optimization-tips/)
* [Gas tips updated](https://blog.polymath.network/solidity-tips-and-tricks-to-save-gas-and-reduce-bytecode-size-c44580b218e6)
* [Storage is expensive](https://medium.com/geekculture/hitchhikers-guide-to-the-evm-56a3d90212ac)
* [Stack too deep and solution](https://medium.com/1milliondevs/compilererror-stack-too-deep-try-removing-local-variables-solved-a6bcecc16231)

**********************************

## DeFI

### Yield Farming

* [Yield Farming (Es)](https://academy.bit2me.com/que-es-el-yield-farming/)
* [Yield Farming (En)](https://academy.binance.com/en/articles/what-is-yield-farming-in-decentralized-finance-defi)

### Automated market maker
* [AMM](https://academy.binance.com/en/articles/what-is-an-automated-market-maker-amm)

### Borrowing and lending

[Compound docs](https://compound.finance/docs)

[Compound - Lending](https://medium.com/compound-finance/supplying-assets-to-the-compound-protocol-ec2cf5df5aa)

[Compound - Borrowing](https://medium.com/compound-finance/borrowing-assets-from-compound-quick-start-guide-f5e69af4b8f4)

[Gemini explanation](https://www.gemini.com/cryptopedia/what-is-compound-and-how-does-it-work#section-the-compound-de-fi-protocol)

### Flash loans

* [Decrypt](https://decrypt.co/resources/what-are-flash-loans-the-defi-lending-phenomenon-explained)
* [Binance](https://academy.binance.com/en/articles/what-are-flash-loans-in-defi)
* [Medium Geek Culture](https://medium.com/geekculture/what-is-a-defi-flash-loans-flash-loan-attack-c130c83d9811)
* [101 Blockchains](https://101blockchains.com/defi-flash-loans/)
* [AAVE Technical docs](https://docs.aave.com/developers/guides/flash-loans)

* [TVL Tracker](https://defipulse.com/)


## Algorand

* [Standard assets (ASA)](https://developer.algorand.org/docs/features/asa/)
* [Stateful Smart Contracts](https://developer.algorand.org/docs/features/asc1/stateful/)
* [Statless Smart Contracts](https://pyteal.readthedocs.io/en/stable/overview.html)
* [Teal Guidelines](https://developer.algorand.org/docs/features/asc1/stateful/)
* [PyTeal overview](https://developer.algorand.org/docs/features/asc1/teal/pyteal/)

## RSK

* [Rlogin](https://github.com/wighawag/tutorial-hardhat-deploy)
* [RSK Swap](https://rskswap.com/docs/v2/protocol-overview/how-rskswap-works)
* [RSK Swap SC](https://rskswap.com/docs/v2/smart-contract-integration/quick-start/)


## Solana

* [Progamming Solana](https://paulx.dev/blog/2021/01/14/programming-on-solana-an-introduction/)
* [Solana 101](https://learn.figment.io/tutorials/solana-101)


## Glossary and technical mix 

* [Bear and bull market](https://academy.binance.com/en/glossary/bear-market)
* [Tokens Comparisson](https://medium.com/coinmonks/token-standards-erc20-vserc721-vs-erc1155-3106f1e3f2f3)
* [ERC20 Tutorial](https://medium.com/crypto-currently/the-anatomy-of-erc721-e9db77abfc24#:~:text=Ethereum%20Request%20for%20Comments%20721,the%20tokens%20are%20non%2Dfungible%20)
* [ERC721 detailed](https://medium.com/crypto-currently/the-anatomy-of-erc721-e9db77abfc24#:~:text=Ethereum%20Request%20for%20Comments%20721,the%20tokens%20are%20non%2Dfungible%20)
* [Randomness](https://betterprogramming.pub/how-to-generate-truly-random-numbers-in-solidity-and-blockchain-9ced6472dbdf)

### Miscellanous

* Hardhat 
	* [Hardhat-deploy-plugin-tutorial](https://github.com/wighawag/tutorial-hardhat-deploy)

* Truffle: 
	* [under the hood migrate](https://medium.com/@blockchain101/demystifying-truffle-migrate-21afbcdf3264)

* Oracles: 
	* [Why oracles](https://medium.com/iex-ec/why-your-dapp-needs-a-decentralized-oracle-2f2403f9fd7)
	* [MakerDao Medianizer](https://developer.makerdao.com/feeds/)

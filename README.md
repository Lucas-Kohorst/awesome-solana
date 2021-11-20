# awesome-solana
## Thanks to [mtreerungroj](https://github.com/mtreerungroj/awesome-solana) for the starting point

[Overall Solana Ecosystem](https://solana.com/ecosystem)
### Bridges
- [Wormhole](https://wormholebridge.com/#/transfer)
- [Allbridge](https://allbridge.io/)

### Trading
#### DEX
- [Raydium](https://raydium.io/) primary sereum based dex
- [Orca](https://www.orca.so/pools) dex with plans to add concentrated liquidity
- [Cyclos](https://app.cyclos.io/) concentrated liquidity dex
- [Saber](https://saber.so/) cross chain stableswap dex

#### Derivatives
- [Drift](https://drift.trade) vAMM cross margined perps
- [Mango](https://mango.markets/) 
- [Bonfida](https://dex.bonfida.org/) best AMM built on sereum

### Yield Aggregators
- [Step](https://step.finance) 
- [Tulip](https://tulip.garden/)
- [Sunny](https://app.sunny.ag/)

### Data/API
- [Token list](https://github.com/solana-labs/token-list/blob/main/src/tokens/solana.tokenlist.json)
- [Sereum Price API](https://docs-price-api.sonar.watch/)
- [Pyth Oracle](https://pyth.network/) used for most derivative backends, [drift](https://drift.trade) and [mango](https://mango.markets/) 
- [Serum Vial](https://github.com/tardis-dev/serum-vial) websocket market data

## Developer

### Reading
- [Solana Documentation](https://docs.solana.com/)
- [Sealevel parallel runtime](https://medium.com/solana-labs/sealevel-parallel-processing-thousands-of-smart-contracts-d814b378192)
- [Solana Program Library](https://spl.solana.com/)
- [Learning how to build on solana](https://www.brianfriel.xyz/learning-how-to-build-on-solana/)
- [Understanding Program derived Addresses](https://www.brianfriel.xyz/understanding-program-derived-addresses/)
- [The complete solana development guide](https://dev.to/dabit3/the-complete-guide-to-full-stack-solana-development-with-react-anchor-rust-and-phantom-3291)
- [Solana Account model](https://solana.wiki/zh-cn/docs/account-model/)
- [Learning solana tweet thread](https://mobile.twitter.com/pencilflip/status/1451949960065335302)
- [Solana PDAs (again)](https://twitter.com/pencilflip/status/1455948263853600768?s=12&utm_source=pocket_mylist)
- [Debugging custom anchor messages](https://www.notion.so/Debugging-Custom-Anchor-Errors-b8540dd418c44a4e939ab17c56a3fd3b)
- [Solana Onboarding](https://github.com/ilmoi/solana-onboarding)
- [Solana Programming concepts](https://hackmd.io/@adamisrusty/HkVyZHBoO)
- [Programming on solana an introduction](https://paulx.dev/blog/2021/01/14/programming-on-solana-an-introduction/)
- [Anchor Basic-0 walkthrough](https://mirror.xyz/0x840B1dC2abb99f1F86D549303719610F346B2aaF/w3-WcRd8aablvFf8Er5qH4H4b-x-8UVfhElMv6Uwick)
- [Learning anchor](https://www.stasha.dev/girri/learning-anchor)

#### Solana Architecture 
- [Proof of History](https://medium.com/solana-labs/proof-of-history-a-clock-for-blockchain-cf47a61a9274)
- [Tower BFT](https://medium.com/solana-labs/tower-bft-solanas-high-performance-implementation-of-pbft-464725911e79) 
- [Turbine](https://medium.com/solana-labs/turbine-solanas-block-propagation-protocol-solves-the-scalability-trilemma-2ddba46a51db) 
- [Gulf Stream](https://medium.com/solana-labs/gulf-stream-solanas-mempool-less-transaction-forwarding-protocol-d342e72186ad)
- [Sealevel](https://medium.com/solana-labs/sealevel-parallel-processing-thousands-of-smart-contracts-d814b378192)
- [Pipelining](https://solana.com/pipelining-in-solana-the-transaction-processing-unit/) 
- [Cloudbreak](https://medium.com/solana-labs/cloudbreak-solanas-horizontally-scaled-state-architecture-9a86679dcbb1)
- [Archivers](https://solana.com/archivers/)


### Examples
- [Hello World](https://github.com/solana-labs/example-helloworld)
- [Hello Chainlink Price Feeds on Solana](https://blog.chain.link/how-to-build-and-deploy-a-solana-smart-contract/)
- [Break Solana](https://github.com/solana-labs/break)
- [R/W JSON format on the Solana contract](https://github.com/jamesbachini/Solana-JSON)
- [Program examples written in Rust](https://github.com/solana-labs/solana-program-library/tree/master/examples/rust)
- [Interface for creating and managing SPL Tokens](https://www.spl-token-ui.com/#/)

### Videos
- [Building SmartContracts With #Solana and #Rust](https://www.youtube.com/watch?v=gA7hFdq2h9Q)
- [Solana Programming: Connect to Wallet, Send Money, Query Transaction History](https://www.youtube.com/watch?v=wVPGJ_CZTAw)
- [Build Dapps with Solana and Arweave](https://www.youtube.com/watch?v=Jz5v_u75xk8)

### Advanced examples
- [Programming on Solana - An Introduction](https://paulx.dev/blog/2021/01/14/programming-on-solana-an-introduction/): Building the escrow program
- [A Vesting Contract for the Solana Blockchain](https://github.com/Bonfida/token-vesting)
- [Staking](https://github.com/step-finance/step-staking) (Use `Anchor`)
- [Permissioned Markets](https://github.com/project-serum/permissioned-markets-quickstart) (Use `Serum`)

### Other examples
- [Voting App](https://medium.com/@smith_10562/a-simple-solana-dapp-tutorial-6dedbdf65444)
- [Solana File Upload](https://github.com/mcf-rocks/solana-upload)
- [SPL Token UI Repo](https://github.com/paul-schaaf/spl-token-ui)
- [Messaging App](https://github.com/kemargrant/soltalk): Proof of Concept

### Libraries and Frameworks
- Solana Program Library (SPL) is a collection of on-chain programs targeting the Sealevel parallel runtime: https://github.com/solana-labs/solana-program-library/blob/master/examples/rust/README.md
- [Anchor Framework](https://project-serum.github.io/anchor/getting-started/introduction.html): a framework for Solana's Sealevel (opens new window)runtime providing several convenient developer tools : https://project-serum.github.io/anchor/tutorials/tutorial-0.html
- [StreamingFast Solana library for Go](https://github.com/streamingfast/solana-go)
- [Rust Library for the Binance API](https://github.com/wisespace-io/binance-rs)

### Token Minting Tools
- [SPL Token UI](https://spl-token-ui.com)
- [SPL Token Creator UI](https://www.spl-token-ui.com/)
- [Bonfida Token Minter](https://bonfida.com/mint)
- [SPL Manager](http://splmanager.com/)

### Wallets
- [Sollet.io](https://sollet.io)
- [Phantom Wallet](https://phantom.app/)
- [SolFlare](https://solflare.com/)

Rust specific resources can be found [here](https://github.com/Lucas-Kohorst/learning-rust)

### Ethereum related
- [Neon EVM](https://neon-labs.org/) is an Ethereum virtual machine on Solana that enables dApp developers to use Ethereum tooling to scale and get access to liquidity on Solana.
- [Solang](https://github.com/hyperledger-labs/solang) Solidity Compiler for Solana, Substrate, and ewasm

### Other Awesome Lists 
- [mtreerungroj/awesome-solana](https://github.com/mtreerungroj/awesome-solana)
- [paul-schaaf/awesome-solana](https://github.com/paul-schaaf/awesome-solana)
- [ilmoi/awesome-solana-nfts](https://github.com/ilmoi/awesome-solana-nfts)
- [murlokito/awesome-solana-gaming](https://github.com/murlokito/awesome-solana-gaming)
- [Pipana/awesome-solana](https://github.com/Pipana/awesome-solana)

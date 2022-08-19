
# awesome-ethereum-diagrams

"A picture tells a thousand words." A curated list of useful diagrams with links to original sources. Diagrams help me grasp complex ethereum concepts related to L1, L2, and Defi.  Contributions and feedback are welcome.

- [L1](#l1)
- [L2](#l2)
- [Oracles](#oracles)
- [Frameworks](#frameworks)
- [DeFi and DAO tekenomics](#defi-and-dao-tokenomics)
- [Governance](#governance)
- [NFT platforms](#nft-platforms)
- [Other blockchain technologies](#other-blockchain-technologies)

## L1

| Diagram                                                | Source        |       
| -------                                                | ------        | 
| <img src="./images/block.jpeg" width="200" height="100">        | [Merkle Patricia Trie in Ethereum](https://kbaiiitmk.medium.com/merkle-patricia-trie-in-ethereum-a-silhouette-c8d04155b490) - every block header stores roots of three trie structures: stateRoot, transactionRoot, receiptsRoot | 
| <img src="./images/trilemma.png" width="200" height="100">        | [The Scalability Trilemma](https://vitalik.ca/general/2021/04/07/sharding.html) |
| <img src="./images/roadmap.jpeg" width="200" height="100">        | [Ethereum roadmap: merge, surge, verge, purge, splurge](https://twitter.com/VitalikButerin/status/1466411377107558402?s=20&t=IkX3s2xEMU0K9EVJVZLotg) |
| <img src="./images/eth_proof_of_work_chain.png" width="200" height="100">        | [Ethereum proof of work chain](https://notes.ethereum.org/@vbuterin/SkeyEI3xv) |
| <img src="./images/sharding.png" width="200" height="100">        | [Ethereum sharding](https://notes.ethereum.org/@vbuterin/SkeyEI3xv) |
| <img src="./images/casper.jpeg" width="200" height="100">        | [Casper FFG in Ethereum 2.0](https://link.medium.com/gbH9gatWvnb) |
| <img src="./images/epoch.gif" width="200" height="100">        | [Epochs and slots in Ethereum 2.0](https://medium.com/stakefish/deeper-dive-into-ethereum-2-0-part-1-93c475a18735) |
| <img src="./images/evm-architecture.png" width="200" height="100">        | [Ethereum EVM architecture](https://github.com/ethereumbook/ethereumbook/blob/develop/13evm.asciidoc) |
| <img src="./images/eth-roadmap-202203.jpeg" width="200" height="100">        | [Ethereum roadmap status as of 3/15/2022](https://twitter.com/pseudotheos/status/1503370385890324484) |
| <img src="./images/erigon.png" width="200" height="100">        | [The erigon ethereum client](https://erigon.substack.com/p/architecture-of-erigon-separable?s=r) |
| <img src="./images/EL_CL.png" width="200" height="100">        | [Execution/Concencus client pairs](https://hackmd.io/@timbeiko/acd/https%3A%2F%2Ftim.mirror.xyz%2FPWFVaHY3Mrx7srarMmuBWya0J5kioR1l2xaH3p5APDk%3Fdisplay%3Diframe) |
| <img src="./images/engineAPI.png" width="200" height="100">        | [POS Execution/Concencus layer interop](https://besu.hyperledger.org/en/stable/Concepts/Merge/) |
| <img src="./images/evmstorage.jpeg" width="200" height="100">        | [EVM storage structure](https://coinyuppie.com/in-depth-understanding-of-evm-storage-mechanism-and-security-issues/) |
| <img src="./images/state-trie.png" width="200" height="100">        | [Ethereum state trie](https://ethereum.stackexchange.com/questions/268/ethereum-block-architecture) |
| <img src="./images/eth-mechanism.jpeg" width="200" height="100">        | [Ethereum blockchain mechanism](https://ethereum.stackexchange.com/questions/268/ethereum-block-architecture) |
| <img src="./images/charon.png" width="200" height="100">        | [Distributed Ethereum validator](https://docs.obol.tech/docs/dv/introducing-charon) |
| <img src="./images/mev-boost.webp" width="200" height="100">        | [MEV Boost](https://www.blocknative.com/blog/ethereum-block-building) |

## L2

| Diagram                                                | Source                                                   |       
| -------                                                | ------                                                   | 
| <img src="./images/layer2s.jpeg" width="200" height="100">        | [Layer 2 solutions](https://cryptoshine.medium.com/understanding-zero-knowledge-layer-2-scaling-2b88edd86016)                                                          |
| <img src="./images/optimism.png" width="200" height="100">        | [Optimism high level architecture](https://community.optimism.io/docs/protocol/protocol-2.0/#)                                                                           |
| <img src="./images/zkSync.png" width="200" height="100">        | [ZKSync high level architecture](https://starli.medium.com/l2-deep-into-zksync-source-code-d6be1b3c16e5)                                                                   |
| <img src="./images/starknet_roadmap.png" width="200" height="100">        | [StarkNet high level roadmap](https://medium.comstarkwareon-the-road-to-starknet-a-permissionless-stark-powered-l2-zk-rollup-83be53640880)                       |
| <img src="./images/connext.png" width="200" height="100">        | [Connext is the interoperability protocol of L2 Ethereum](https://nxtp-docs.connext.network/Integration/SystemOverview/howitworks)                                  |
| <img src="./images/celestia.jpeg" width="200" height="100">        | [Celestium as the data availability layer](https://blog.celestia.org/celestiums/)         |
| <img src="./images/celestia.png" width="200" height="100">        | [Celestia - modular blockchain](https://medium.com/momentum6/modular-blockchains-the-next-alpha-celestia-overview-456ca5bbf9b1)                         |
| <img src="./images/Beacon-Chain-RANDAO.png" width="200" height="100">        | [RANDAO selects proposers for each slot, and shuffles validators to committees](https://ethos.dev/beacon-chain/)                                  |
| <img src="./images/arbitrum.png" width="200" height="100">        | [Arbitrum high level architecture](https://tracer.finance/radar/arbitrum-in-under-10/)                                        |
| <img src="./images/arbitrum_trx_paths.png" width="200" height="100">        | [Arbitrum transaction paths](https://medium.com/privacy-scaling-explorations/a-technical-introduction-to-arbitrums-optimistic-rollup-860955ea5fec)                               |
| <img src="./images/polygon2.png" width="200" height="100">        | [Polygon architecture](https://docs.polygon.technology/docs/validate/validator/architecture/)                               |
| <img src="./images/polygon-edge.png" width="200" height="100">        | [Polygon edge](https://blog.polygon.technology/how-to-bootstrap-a-blockchain-with-polygon-edge/?utm_source=Twitter-Main&utm_medium=Tweet&utm_campaign=Tier-1-Announcement)                               |
| <img src="./images/chain-and-state-diagram-full.jpeg" width="200" height="100">        | [Ethereum scaling solutions](https://samlaf.github.io/blockchain/graphical-depiction-of-ethereum-scaling-solutions.html) |
| <img src="./images/zkEvm.png" width="200" height="100">        | [Polygon zkEvm](https://blog.polygon.technology/the-future-is-now-for-ethereum-scaling-introducing-polygon-zkevm/) |


## Oracles
| Diagram                                                | Source                                                   |       
| -------                                                | ------                                                   | 
| <img src="./images/uma_oracle.png" width="200" height="100">        | [UMA's DVM Oracle](https://docs.umaproject.org/oracle/tech-architecture)                                                          |
| <img src="./images/chainlink.png" width="200" height="100">        | [Chainlink Oracle](https://www.kaleido.io/blockchain-blog/how-chainlink-works-under-the-covers)                                                          |
| <img src="./images/proof_of_reserves.png" width="200" height="100">        | [Chainlink Proof Of Reserves](https://blog.chain.link/proof-of-reserves/)                                               |

## Frameworks
| Diagram                                                | Source                                                   |       
| -------                                                | ------                                                   | 
| <img src="./images/dsproxy.png" width="200" height="100">        | [DS Proxy](https://twitter.com/definikola/status/1512100163527090193)                                                          |
| <img src="./images/proxy.webp" width="200" height="100">        | [Unstructured Storage Proxy](https://blog.openzeppelin.com/proxy-patterns/)                                                          |


## DeFi and DAO tokenomics

| Diagram                                                | Source                                                   |       
| -------                                                | ------                                                   | 
| <img src="./images/uniswap_const_prod_func.png" width="200" height="100">        | [Uniswap Constant Product Function: x * y = k](https://www.bsc.news/post/uniswap-project-insight-a-pioneer-in-the-decentralised-amm-space)                                                   |
| <img src="./images/uniswap.jpeg" width="200" height="100">        | [Uniswap](https://docs.uniswap.org/protocol/V2/concepts/protocol-overview/how-uniswap-works)                                                   |
| <img src="./images/uniswap_liq_provider.jpeg" width="200" height="100">        | [Uniswap Liquidity Provider](https://docs.uniswap.org/protocol/V2/concepts/protocol-overview/how-uniswap-works)                                                   |
| <img src="./images/uniswap_trader.jpeg" width="200" height="100">        | [Uniswap Trader](https://docs.uniswap.org/protocol/V2/concepts/protocol-overview/how-uniswap-works)                                                   |
| <img src="./images/uni_dai_to_usdc_swap_v1.png" width="200" height="100">        | [Uniswap DAI to USDC swap v1](https://uniswap.org/blog/uniswap-v2)                                                   |
| <img src="./images/uni_dai_usdc_swap_v2.png" width="200" height="100">        | [Uniswap DAI to USDC swap v2](https://uniswap.org/blog/uniswap-v2)                                                   |
| <img src="./images/uni_twap_price.png" width="200" height="100">        | [Uniswap stored TWAP price](https://uniswap.org/blog/uniswap-v2)                                                   |
| <img src="./images/uni_price_from_twap.png" width="200" height="100">        | [Uniswap price from TWAP](https://uniswap.org/blog/uniswap-v2)                                                   |
| <img src="./images/uni_flash_swaps.png" width="200" height="100">        | [Uniswap flash swap](https://uniswap.org/blog/uniswap-v2)                                                   |
| <img src="./images/curve.png" width="200" height="100">        | [Curve Finance](https://medium.com/stakecapital/curve-tokenomics-and-first-mover-advantage-54f2143728c2)                                                   |
| <img src="./images/aave.jpeg" width="200" height="100">        | [Aave](https://docs.aave.com/aavenomics/ecosystem-overview)                                                   |
| <img src="./images/maker.png" width="200" height="100">        | [Maker protocol smart contract modules system](https://docs.makerdao.com/)                                                   |
| <img src="./images/tokemak.png" width="200" height="100">        | [Tokemak reactor structure](https://coinlive.me/is-tokenak-toke-a-potential-liquidity-solution-9042.html)                                                   |
| <img src="./images/fei_pcv_reweights.png" width="200" height="100">        | [FEI pcv reweights](https://medium.com/fei-protocol/introducing-fei-protocol-2db79bd7a82b)                                                   |
| <img src="./images/fei_bonding_curve.png" width="200" height="100">        | [FEI bonding curve](https://medium.com/fei-protocol/introducing-fei-protocol-2db79bd7a82b)                                                   |
| <img src="./images/fei_arbitrage.png" width="200" height="100">        | [FEI arbitrage](https://medium.com/fei-protocol/introducing-fei-protocol-2db79bd7a82b)                                                   |
| <img src="./images/fei_incentivised_exchange.png" width="200" height="100">        | [FEI incentivized exchange](https://medium.com/fei-protocol/introducing-fei-protocol-2db79bd7a82b)                                                   |
| <img src="./images/fei_peg_dynamics.png" width="200" height="100">        | [FEI peg dynamics](https://medium.com/fei-protocol/introducing-fei-protocol-2db79bd7a82b)                                                   |
|<img src="./images/yearn_v2_technical.jpg" width="200" height="100">        | [Yearn v2 architecture](https://defi-diagrams.herokuapp.com/yearn-vaults-v2/)                                                   |
|<img src="./images/ondo_fei_laas.png" width="200" height="100">        | [Liquidity as a service with ondo and fei](https://medium.com/fei-protocol/if-you-are-part-of-a-dao-or-protocol-that-wants-to-create-liquidity-for-your-token-without-f49a01f02863)              |
|<img src="./images/lido.png" width="200" height="100">        | [Lido staking](https://blog.lido.fi/how-lido-works/)                                                   | 
|<img src="./images/alchemix.png" width="200" height="100">        | [Alchemix: self repaying loans](https://alchemixfi.medium.com/introducing-alchemix-9e7054de54d6)                                                     | 
|<img src="./images/tracer.png" width="200" height="100">        | [Tracer DAO: Factory contracts for derivative markets](https://tracer.finance/radar/future-of-derivatives/)                                                     |
|<img src="./images/yearn-ecosystem.png" width="200" height="100">        | [Yearn DeFi ecosystem map](https://messari.io/article/yearning-for-yearn)                                                     | 
|<img src="./images/chainlink-keepers.jpeg" width="200" height="100">   | [Chainlink keepers](https://blog.chain.link/smart-contract-automation-use-cases-powered-by-chainlink-keepers/)                                           |
|<img src="./images/chainlink-keeper-alchemix.png" width="200" height="100">   | [Chainlink keepers - Alchemix](https://blog.chain.link/smart-contract-automation-use-cases-powered-by-chainlink-keepers/)                                           |
|<img src="./images/tokemak-high-level.png" width="200" height="100">   | [Tokemak benefits](https://www.tokebase.org/way-of-the-pilot/)                                           |
|<img src="./images/aave-contracts.png" width="200" height="100">   | [Aave contracts overview](https://docs.aave.com/developers/v/1.0/developing-on-aave/the-protocol)                                           |
|<img src="./images/dopex.png" width="200" height="100">   | [DeFi options: Dopex options flow](https://docs.dopex.io/pools/platform-flow)                                           |
|<img src="./images/klima.png" width="200" height="100">   | [Tokenomics of bringing carbon on-chain and using it to back KLIMA](https://medium.com/coinmonks/tokenomics-101-klima-dao-e8fac497454f)                                           |
|<img src="./images/aladdin_concentrator.png" width="200" height="100">   | [Aladdin Concentrator for maximazing curve LP rewards](https://curve.substack.com/p/march-11-2022-genies-out-of-the-boule?r=br6us&s=w&utm_campaign=twitter_3_11_22)                                           |
|<img src="./images/gysr.png" width="200" height="100">   | [GYSR liquidity mining reward mechanism](https://medium.com/gysr/gysr-gelato-g-uni-for-uniswap-v3-liquidity-mining-5579c2cf8a35)             |
|<img src="./images/gelato.png" width="200" height="100">   | [G-UNI Uniswap v3 liquidity management system with no code](https://medium.com/gysr/gysr-gelato-g-uni-for-uniswap-v3-liquidity-mining-5579c2cf8a35)  |
|<img src="./images/Frax_tokenomics.png" width="200" height="100">   | [FRAX Tokenomics](https://tokenomicsdao.com/frax/)  |
|<img src="./images/alchemix_elixir.png" width="200" height="100">   | [Alchemix Elixir](https://alchemixfi.medium.com/elixir-the-alchemix-algorithmic-market-operator-2e4c8ad04569)  |
|<img src="./images/liquid_lockers.jpeg" width="200" height="100">   | [StakeDAO - Liquid lockers](https://stakedaohq.medium.com/introducing-liquid-lockers-vesdt-5febcf169170)  |
|<img src="./images/lyra.png" width="200" height="100">   | [Lyra options AMM](https://docs.lyra.finance/implementation/lyra-protocol-architecture)  |
|<img src="./images/voltz_architecture.png" width="200" height="100">   | [Voltz IRS](https://docs.voltz.xyz/getting-started/protocol-overview)  |
|<img src="./images/starknet_dai_bridge.png" width="200" height="100">   | [StarkNet Dai Bridge](https://morioh.com/p/be6c9cb57011)  |
|<img src="./images/batch_auctions.png" width="200" height="100">   | [COW Protocol / Batch Auctions](https://docs.cow.fi/overview/batch-auctions)  |

# Governance

| Diagram                                                | Source                                                   |       
| -------                                                | ------                                                   | 
|<img src="./images/aragon.png" width="200" height="100">   | [Building DAOs with Aragon](https://medium.com/quiknode/building-daos-with-aragon-c8b95956a405)  |

# NFT platforms

| Diagram                                                | Source                                                   |       
| -------                                                | ------                                                   | 
|<img src="./images/spore-overview.png" width="200" height="100">   | [Spore Ecosystem](https://www.spores.vision/learn/)                  |

# Other blockchain technologies

| Diagram                                                | Source                                                   |       
| -------                                                | ------                                                   | 
|<img src="./images/terra_luna.png" width="200" height="100">   | [Terra / Luna Tokenomics](https://medium.com/bankless-dao/tokenomics-101-terra-ecosystem-cbbca4a03205)                  |
|<img src="./images/avalanche_consensus.png" width="200" height="100">   | [Avalanche Consensus](https://learn.bybit.com/altcoins/what-is-avalanche-avax/)                  |
|<img src="./images/layerzero.png" width="200" height="100">   | [LayerZero](https://d-core.net/asset-review-summary-layerzero-protocol/)                  |
|<img src="./images/Uploaded_from_Sign_in_with_Ethereum.png" width="200" height="100">   | [Spruce/Sign-in with Ethereum](https://auth0.com/blog/sign-in-with-ethereum-siwe-now-available-on-auth0/)                  |
|<img src="./images/polygon_id.jpeg" width="200" height="100">   | [Polygon ID](https://blog.polygon.technology/introducing-polygon-id-zero-knowledge-own-your-identity-for-web3/)                  |
|<img src="./images/livepeer.png" width="200" height="100">   | [Livepeer](https://github.com/livepeer/wiki/blob/master/WHITEPAPER.md)                  |
|<img src="./images/truebit.png" width="200" height="100">   | [Truebit](https://medium.com/gasworks-crypto/truebit-the-biggest-crypto-project-youve-never-heard-of-512717e5e061)                  |

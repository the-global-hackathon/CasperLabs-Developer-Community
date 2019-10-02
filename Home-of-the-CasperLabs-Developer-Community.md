# Welcome to CasperLabs wiki!

This document provides information about how you can participate with our CasperLabs Community Engagement Program.

So far the development of CasperLabs solution has been progressing with our internal resources and we are now at a stage of actively engaging our CasperLabs Community Members (CCM), also known as the CLarity Member (CM): adding features, improving functionality, developing dApps, fixing security holes and bugs, and contributing insights and feedback to advance the evolution of CasperLabs platform.

## Current Developments

We present a new permissionless, decentralized and Turing-complete smart contract and cryptocurrency platform, backed by a proof-of-stake (PoS) consensus algorithm that is based on Vlad Zamfir's correct-by-construction (CBC) Casper work, with unique features:
* A proof-of-stake system with an on-chain contract managing deposits and rewards.
* Provably safe and live under partial synchrony, even under a 49% attack.
* Client-side configurable fault-tolerance thresholds: users can choose higher safety at the cost of higher latency to transaction finalization.
* Smart contracts that can be written in any language compiling to WebAssembly.
* Stable and predictable economics: reliable costs for users and consistent returns for validators.
* Low overhead because orphaned blocks' transactions are still included when possible.
* On-chain object-capability model for secure permission handling in smart contracts.
* Flexible account permissions model allowing for lost key recovery. 

### Devnet (Public Dev Net)

We recently launched Devnet, our Public Dev Net where Developers can run nodes and connect to a public bootstrap node.

### Testnet (Public Test Net)

We are also well on schedule for November 2019 to launch Testnet; the feature complete, decentralized Public Test Net.

Note: CasperLabs does not as of yet have a bounty program but may consider one after the Testnet launch.

## Roadmap

Main Net Launch in 2020

# Participating in the CasperLabs Community

The consensus protocol is built on Vlad Zamfir's correct-by-construction (CBC) Casper work. Our design is a particular protocol in the CBC Casper family which is provably safe and live under partial synchrony without an in-protocol fault tolerance threshold. The computation model allows for efficient detection of when contract executions can be run in parallel. The technical specification presents details on this design and how you can implement it, including but not limited to:
 
* block message format allows "merging" forks in the chain, thus the platform avoids orphaning blocks unnecessarily. 
* Rust is supported as the primary programming language for smart contracts because of its good support for compilation to wasm 
* libraries facilitating contract development in other programming language having wasm as a compile target

Other features of the execution engine include: 
* an account permissions model allowing for lost key recovery, 
* a permissions model to securely share state between accounts and/or contracts (without the need for expensive cryptographic checks). 

* the economics of our proof-of-stake implementation and our token policies are also provided

_See our_ [Technical Specification]( https://techspec.casperlabs.io/) to understand how, and get started with the information herein provided for CasperLabs Community members as follows:

# Community Members
- **Validators / Node Operators** (Investors) are members of our Community who validate transactions on our platform,

- **dApp Developers** (Developers) are members of our Community who build Apps using our CasperLabs features. You can install our environment locally, create and test Smart contracts with our Smart Contracts and Test Libraries, and use these libraries to build your own applications,

- **Freelance Developer Community** are members of our CasperLabs Community who are developers and engineers interested in contributing to our CasperLabs core development,

- **General Blockchain Enthusiasts** are members of the CasperLabs Community who support blockchain technology and are interested in learning more about CasperLabs progress and impact on the world of blockchain technology,

  

# Getting Started

## Validators/Node Operators

- With this documentation you will gain insight and understanding about what CasperLabs is building
- Learn how to operate a **validator node** or **stake the network**  understanding the economics behind it
- Join a community of like-minded believers

**Pre-requisites:**

- Web access
- Basic understanding on how to use web applications for generating and validating blockchain transactions
- Downloading and Setting Up a Node

**Resources**

- [CasperLabs Explorer](https://explorer.casperlabs.io/) -- takes you to the UI where you can setup security keys, obtain remuneration, and run transactions.
- [CasperLabs Release Notes]( https://github.com/CasperLabs/CasperLabs/releases). See what is currently available in CasperLabs most current versions and get started with CasperLabs Explorer application.

## dApp Developers

- Understand what CasperLabs is building and how you can build your applications
  - [Architecture](https://casperlabs.atlassian.net/wiki/spaces/EN/pages/12713999/Architecture+of+the+CasperLabs+node) 
- Learn how to build and operate applications on the platform
- Learn how to set up the CasperLabs environment locally
- Learn how to create and test Smart Contracts with our Libraries
- Contracts API

**Pre-requisites:**

- Linux and OSx
- Programming knowledge
- JavaScript and/or Python

**Resources**

The following set of documentation is presented in order and provides instructions on Linux and OSx for setting up the CasperLabs environment locally, setting up Nodes, and building, testing, and executing Smart contracts to address your use case including:

- CasperLabs - Smart contract template repository (Debian, Ubuntu, Mint, macOS)
  - Demo -- [How to build a local environment](https://youtu.be/P8SC_upCqAg)
  - Documentated Instructions -- How to build a local environment [Casperlabs Smart Contract template](https://github.com/zie1ony/casperlabs-smart-contract-template)
- [CasperLabs DevNet tools](http://devnet-graphql.casperlabs.io:40403/graphql) (GraphQL)
- [Useful Diagrams](https://github.com/CasperLabs/CasperLabs/blob/dev/docs/DIAGRAMS.md)

## Freelance Developer Community

Join a community of CasperLabs freelance developers to:

- Understand what CasperLabs is building
- Contribute to the CasperLabs Core
- [Contribute](https://github.com/CasperLabs/CasperLabs/blob/dev/CONTRIBUTING.md) to CasperLabs by creating an account on GitHub.
- Learn how to contribute towards development, access required resources here:
  - [Coding Standards](https://casperlabs.atlassian.net/wiki/spaces/EN/pages/16842753/Coding+Standards)
  - [Review Standards](https://casperlabs.atlassian.net/wiki/spaces/EN/pages/4161628/Code+Review+Process)

**Pre-requisites**

- Knowledge of engineering
- Command of Rust, Rust Cargo, JavaScript and/or Python

**Resources**

The following link provides a set of documentation is presented in order and provides instructions on Linux setting up the CasperLabs implementation locally, setting up Nodes, and building, testing, and executing Smart contracts to address your use case.

[Resources](https://github.com/CasperLabs/CasperLabs/wiki/CasperLabs-Resources) 

## General Blockchain Enthusiasts

General Enthusiasts of Blockchain technology are members of the CasperLabs Community who are curious to learn more about CasperLabs to:

- Understand what CasperLabs is building and its unique features
- Learn about the technical resources like specifications, mathematical papers, etc. (*see here below*)
- Keep updated about development status, use cases, and dApps <!--(subscribe)-->

**Resources**

- **Math Proof**

  [Introducing the "minimal" CBC Casper Consensus Protocols.](https://github.com/cbc-casper/cbc-casper-paper/blob/master/cbc-casper-paper-draft.pdf)

- **Specification**

  [Current Technical Specification](https://techspec.casperlabs.io/) 

<!--https://casperlabs.atlassian.net/wiki/spaces/EN/pages/123437404/Specifications-->

# Getting Help

- [Telegram Channel](https://telegram.org/) 

  Our telegram channel is for anyone to join for consistent company updates & any questions our community may have.

- [CasperLabs Discord Server](https://discordapp.com/invite/Q38s3Vh)

  Check out the CasperLabs community on Discord - hang out with other members and enjoy free voice and text chat. 

  Our Discord server is intended for the technical audience to provide a space specifically where you can interact with our internal developer team for any technical, node or testing related questions. 

- [CasperLabs Community Forum](https://forums.casperlabs.io/) 

  Search topics, posts, information from and about our users.
- 

# Known Issues

If you are not running your implemention on Linux, we are currently we are extending our tools to build and run execution-engine binaries on a Mac. -- we recommend using docker.

# Reporting Issues

If you find any issues, please [file an issue](https://github.com/CasperLabs/CasperLabs/issues/new) (for guidelines *see* [Contributing to CasperLabs](https://github.com/CasperLabs/CasperLabs/blob/dev/CONTRIBUTING.md))

You can also find support and resources for help as needed: [Getting Help](#Getting Help)

# References

- [About Rust](rust-lang.org)
- [Rust API documentation](https://github.com/CasperLabs/CasperLabs/blob/dev/execution-engine/contract-ffi/src/contract_api/mod.rs)
  <!--[- Learn about Rust](https://medium.com/learning-rust)-->
  <!--Doc.rust-lang.org std - [Rust documentation](https://github.com/CasperLabs/CasperLabs/blob/dev/execution-engine/contract-ffi/src/contract_api/mod.rs).--> 
  <!--[- CBC CasperLabs Resource List](https://github.com/ethereum/cbc-casper/wiki/Resource-List)--> 
  <!--[- About CBC Casper proof-of-stake protocol](https://blockgeeks.com/guides/ethereum-casper/)--> 
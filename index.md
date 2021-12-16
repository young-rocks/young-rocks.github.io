In order to improve the scalability of the blockchain, we propose zkMove - a zero-knowledge proof-based smart contract runtime environment that combines Move, the most secure smart contract programming language, with PLONK, a maturing zero-knowledge proof technology, to "Move" computation from on-chain to off-chain, significantly improving the scalability of blockchain while ensuring security.

### Excellent programmability

Currently on Etherum, most Layer2 projects only support single application scenarios and are not programmable. zkMove hopes to combine the programming language virtual machine with zero-knowledge proof cryptography to create a Turing-complete zero-knowledge proof virtual machine that allows smart contracts to be deployed directly through the virtual machine without the need to develop a separate circuit.

### Security beyond main chain

First, the security of the blockchain is inherited through zero-knowledge proof technology. With zkMove as the foundation, it is easy to build various Layer2 solutions on the main chain, so that users do not have to monitor the network all the time, no one or organization can steal user assets or destroy user state, and users can withdraw assets unconditionally at any time. Secondly, it goes beyond mainchain security with the Move language. zkMove uses Move, a new generation smart contract programming language for digital assets, combined with tools such as formal verification, which can further enhance the security of smart contracts.

### Cross blockchain

Unlike existing Layer2 solutions, zkMove does not position itself as Layer2 of some public blockchain, but as a cross-blockchain environment for running smart contracts. A smart contract running on zkMove can directly interact with another smart contract running on zkMove, regardless of the underlying blockchain, even if the underlying layer is not blockchain dependent.

Detailed description can be found [here](https://github.com/zkmove/zkmove/blob/master/docs/zkMove_project_description_en.pdf) [(中文)](https://github.com/zkmove/zkmove/blob/master/docs/zkMove_project_description_ch.pdf)

## About

This project was created by Guangyu Zhu in July 2021. The goal is to improve the programmability of zero-knowledge proof technology. It's still in the initial stage, we look forward to more developers joinning.

## Contacts

Basic information about the project is provided by the developers in the [Discord](https://discord.gg/hCTmEkABHn)

## License

zkMove is licensed as [Apache 2.0](./LICENSE).

# Incognito

[![Read Whitepaper](https://img.shields.io/badge/-Website-black?style=for-the-badge&logo=internet-explorer&logoColor=white&link=https://github.com/IncognitoSolana/Incognito/blob/main/Incognito_Whitepaper.pdf)](https://github.com/IncognitoSolana/Incognito/blob/main/Incognito_Whitepaper.pdf)

Incognito Solana implements the first zero-knowledge privacy solution for mixing Solana in an untraceable manner.

It employs a smart contract that accepts transactions in \verb|Sol| so that the amount can be later withdrawn with no reference to the original transaction. This ensures anonymity for our users, while also providing protection against malicious third parties. Incognito also enforces strict guarantees against double-withdrawals and prevents theft while maintaining user-privacy.

To achieve user privacy, smart contracts are used that accept token deposits from one address and enable their withdrawal from a different address. These smart contracts also work as pools that mix all the deposited assets. When the funds are transferred to a completely new wallet address from such pools, they break the on-chain link between the source and destination of the users' funds, providing asset anonymity guarantees for each user. When a user deposits funds into a pool a private note is generated. The user can use the private note (acting as a private key) to access those funds later.

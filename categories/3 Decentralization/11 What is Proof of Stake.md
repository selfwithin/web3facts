Proof of Stake consists of a network of validators.
Proof-of-stake is a cryptocurrency consensus mechanism for processing transactions and creating new blocks in a blockchain. A consensus mechanism is a method for validating entries into a distributed database and keeping the database secure. In the case of cryptocurrency, the database is called a blockchain—so the consensus mechanism secures the blockchain. Proof of Stake was invented by Sunny King and was implimented in BTC Clone called PPCOIN, later name changed to Peercoin.

Validators are individuals which have deposited, or staked, cryptocurrency
and run a specifically designed program to process transactions.
They are typically discouraged from withdrawing their stake or taking their program
offline with financial penalties.

Each network which relies on Proof of Stake has their own set of requirements
for validators. These requirements can include:

-   A minimum stake (2000 AVAX, 32 ETH, ~$50,000 USD, 20 PPC)
-   A minimum uptime (80% on Avalanche)
-   1 to 2 TB SSD Storage
-   4 to 128 GB of RAM

When a Block of transactions is full, the network selects a validator to the
re-execute the transactions and validate the Block so it can be added to the
[Blockchain](#WhatIsABlockchain).

The selection process for validators depends on the network, they can be selected
randomly, or based on the how large their stake is.

The [Nodes](#WhatIsANode) within the network are responsible for selecting the validators.
This all [Nodes](#WhatIsANode) must be capable of randomly selecting the same validator.
One way this is achieved is by having the [Nodes](#WhatIsANode) use the same
[Random Seed](https://en.wikipedia.org/wiki/Random_seed), such as the hash of the previous Block.

**References**
-   [Avalanche - What is Staking](https://docs.avax.network/nodes/validate/staking)
-   [Solana - Validator Requirements](https://docs.solana.com/running-validator/validator-reqs)
-   [Ethereum - Proof of Stake](https://ethereum.org/en/developers/docs/consensus-mechanisms/pos/)
-   [ethos.dev - Beacon Chain](https://ethos.dev/beacon-chain/)
-   [Vitalik - PoS FAQS](https://vitalik.ca/general/2017/12/31/pos_faq.html#how-does-validator-selection-work-and-what-is-stake-grinding)

# EIPs [![Gitter](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/ethereum/EIPs?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge)
Ethereum Improvement Proposals (EIPs) describe standards for the Ethereum platform, including core protocol specifications, client APIs, and contract standards.

# Contributing
First review [EIP-1](EIPS/eip-1.md). Then clone the repository and add your EIP to it. There is a [template EIP here](eip-X.md). Then submit a Pull Request to Ethereum's [EIPs repository](https://github.com/ethereum/EIPs).

# EIP status terms
* **Draft** - an EIP that is open for consideration
* **Accepted** - an EIP that is planned for immediate adoption, i.e. expected to be included in the next hard fork (for Core/Consensus layer EIPs).
* **Final** - an EIP that has been adopted in a previous hard fork (for Core/Consensus layer EIPs).
* **Deferred** - an EIP that is not being considered for immediate adoption. May be reconsidered in the future for a subsequent hard fork.



# EIPs under consideration
| Number                                                  |Title                                                                                | Author                | Type      | Layer       | Status    | 
| ------------------------------------------------------  | ----------------------------------------------------------------------------------- | --------------------  | ----------| ------------| ----------|
| [5](EIPS/eip-5.md)                                      | Gas Usage for `RETURN` and `CALL*` [Note: Unneccessary if 211 is accepted]                                                  | Christian Reitwiessner| Standard  | Core        | Draft     |
| [211](https://github.com/ethereum/EIPs/pull/211)        | New opcodes: RETURNDATASIZE and RETURNDATACOPY                                      | Christian Reitwiessner| Standard  | Core        | Draft     |
| [214](https://github.com/ethereum/EIPs/pull/214)        | New opcode STATICCALL                                                               | Buterin, Reitwiessner | Standard  | Core        | Draft     |


# Accepted EIPs (planned for adoption)
| Number                                                  |Title                                                                                | Author                | Type      | Layer       | Status    | 
| ------------------------------------------------------- | ----------------------------------------------------------------------------------- | --------------------  | ----------| ------------| ----------|
| [86](https://github.com/ethereum/EIPs/pull/208)         | Abstraction of transaction origin and signature                                     | Vitalik Buterin       | Standard  | Core        | Accepted  |
| [96](https://github.com/ethereum/EIPs/pull/210)         | Blockhash refactoring                                                               | Vitalik Buterin       | Standard  | Core        | Accepted  |
| [98](https://github.com/ethereum/EIPs/pull/98)          | Removal of intermediate state roots from receipts                                   | Vitalik Buterin       | Standard  | Core        | Accepted  |
| [100](https://github.com/ethereum/EIPs/issues/100)      | Change difficulty adjustment to target mean block time including uncles	            | Vitalik Buterin       | Standard  | Core        | Accepted  |
| [140](https://github.com/ethereum/EIPs/pull/206)        | REVERT instruction in the Ethereum Virtual Machine                                  | Beregszaszi, Mushegian| Standard  | Core        | Accepted  |
| [196](https://github.com/ethereum/EIPs/pull/213)        | Precompiled contracts for addition and scalar multiplication on the elliptic curve alt_bn128 | Reitwiessner | Standard  | Core        | Accepted  |
| [197](https://github.com/ethereum/EIPs/pull/212)        | Precompiled contracts for optimal Ate pairing check on the elliptic curve alt_bn128 | Buterin, Reitwiessner | Standard  | Core        | Accepted  |
| [198](https://github.com/ethereum/EIPs/pull/198)        | Precompiled contract for bigint modular exponentiation				                      | Vitalik Buterin       | Standard  | Core        | Accepted  |


# Finalized EIPs (standards that have been adopted)
| Number                                                  |Title                                                        | Author          | Type      | Layer       | Status  | 
| ------------------------------------------------------- | ----------------------------------------------------------- | ----------------| ----------| ------------| --------|
| [2](EIPS/eip-2.mediawiki)                               | Homestead Hard-fork Changes                                 | Vitalik Buterin | Standard  | Core        | Final   |
| [6](EIPS/eip-6.md)                                      | Renaming Suicide Opcode                                     | Hudson Jameson  | Standard  | Interface   | Final   |
| [7](EIPS/eip-7.md)                                      | DELEGATECALL                                                | Vitalik Buterin | Standard  | Core        | Final   |
| [8](EIPS/eip-8.md)                                      | devp2p Forward Compatibility Requirements for Homestead     | Felix Lange     | Standard  | Networking  | Final   |
| [150](https://github.com/ethereum/EIPs/issues/150)      | Gas cost changes for IO-heavy operations                    | Vitalik Buterin | Standard  | Core        | Final   |
| [155](https://github.com/ethereum/EIPs/issues/155)      | Simple replay attack protection                             | Vitalik Buterin | Standard  | Core        | Final   |
| [160](https://github.com/ethereum/EIPs/issues/160)      | EXP cost increase                                           | Vitalik Buterin | Standard  | Core        | Final   |
| [161](https://github.com/ethereum/EIPs/issues/161)      | State trie clearing (invariant-preserving alternative)      | Gavin Wood      | Standard  | Core        | Final   |
| [170](https://github.com/ethereum/EIPs/issues/170)      | Contract code size limit                                    | Vitalik Buterin | Standard  | Core        | Final   |

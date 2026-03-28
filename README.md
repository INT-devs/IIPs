# INTcoin Improvement Proposals (IIPs)

People wishing to submit IIPs should first propose their idea in the [Discord #development channel](https://discord.gg/Y7dX4Ps2Ha). After discussion, please open a PR. After copy-editing and acceptance, it will be published here.

We are fairly liberal with approving IIPs and try not to be too involved in decision making on behalf of the community. The exception is in very rare cases of dispute resolution when a decision is contentious and cannot be agreed upon. In those cases, the conservative option will always be preferred.

Having an IIP here does not make it a formally accepted standard until its status becomes Final or Active.

## IIP Index

| Number | Layer | Title | Owner | Type | Status |
|--------|-------|-------|-------|------|--------|
| [1](iip-0001.mediawiki) | | IIP Purpose and Guidelines | INT Core | Process | Active |
| [2](iip-0002.mediawiki) | Consensus | Post-Quantum Signature Scheme (ML-DSA-87) | INT Core | Standard | Final |
| [3](iip-0003.mediawiki) | Consensus | Version Bits with Timeout and Delay | INT Core | Standard | Final |
| [4](iip-0004.mediawiki) | Consensus | Duplicate Transaction Prevention | INT Core | Standard | Final |
| [5](iip-0005.mediawiki) | Consensus | Block Height in Coinbase | INT Core | Standard | Final |
| [6](iip-0006.mediawiki) | Consensus | OP_CHECKLOCKTIMEVERIFY | INT Core | Standard | Final |
| [7](iip-0007.mediawiki) | Consensus | Relative Lock-Time Using Sequence Numbers | INT Core | Standard | Final |
| [8](iip-0008.mediawiki) | Consensus | OP_CHECKSEQUENCEVERIFY | INT Core | Standard | Final |
| [9](iip-0009.mediawiki) | Consensus | Transaction Signature Verification for ML-DSA-87 | INT Core | Standard | Final |
| [10](iip-0010.mediawiki) | Peer Services | mempool Message | INT Core | Standard | Final |
| [11](iip-0011.mediawiki) | Peer Services | Connection Bloom Filtering | INT Core | Standard | Final |
| [12](iip-0012.mediawiki) | Peer Services | sendheaders Message | INT Core | Standard | Final |
| [13](iip-0013.mediawiki) | Peer Services | feefilter Message | INT Core | Standard | Final |
| [14](iip-0014.mediawiki) | Peer Services | Compact Block Relay | INT Core | Standard | Final |
| [15](iip-0015.mediawiki) | Peer Services | addrv2 Message | INT Core | Standard | Final |
| [16](iip-0016.mediawiki) | Peer Services | Client Side Block Filtering | INT Core | Standard | Final |
| [17](iip-0017.mediawiki) | Peer Services | Compact Block Filters | INT Core | Standard | Final |
| [18](iip-0018.mediawiki) | Peer Services | Anti-Fee-Sniping Protection | INT Core | Standard | Final |
| [19](iip-0019.mediawiki) | Peer Services | Erlay Transaction Relay | INT Core | Standard | Final |
| [20](iip-0020.mediawiki) | Peer Services | Ancestor Package Relay | INT Core | Standard | Final |
| [21](iip-0021.mediawiki) | Peer Services | WTXID-Based Transaction Relay | INT Core | Standard | Final |
| [22](iip-0022.mediawiki) | Peer Services | Topology Restrictions | INT Core | Standard | Final |
| [23](iip-0023.mediawiki) | Applications | URI Scheme | INT Core | Standard | Final |
| [24](iip-0024.mediawiki) | Applications | Mnemonic Code for Deterministic Keys | INT Core | Standard | Final |
| [25](iip-0025.mediawiki) | Applications | Multisig Derivation Paths | INT Core | Standard | Final |
| [26](iip-0026.mediawiki) | Applications | Deterministic Input/Output Ordering | INT Core | Standard | Final |
| [27](iip-0027.mediawiki) | Applications | Opt-in Replace-by-Fee | INT Core | Standard | Final |
| [28](iip-0028.mediawiki) | Applications | Secure Multisig Setup (SMS) | INT Core | Standard | Final |
| [29](iip-0029.mediawiki) | Applications | Bech32 Address Format | INT Core | Standard | Final |
| [30](iip-0030.mediawiki) | Applications | Partially Signed Transactions (PST) | INT Core | Standard | Final |
| [31](iip-0031.mediawiki) | Applications | Message Signing | INT Core | Standard | Final |
| [32](iip-0032.mediawiki) | Applications | Wallet Labels Export Format | INT Core | Standard | Final |
| [33](iip-0033.mediawiki) | Applications | Bech32m Address Encoding | INT Core | Standard | Final |
| [34](iip-0034.mediawiki) | Applications | DNS Payment Instructions | INT Core | Standard | Final |
| [35](iip-0035.mediawiki) | Applications | Output Script Descriptors | INT Core | Standard | Final |
| [36](iip-0036.mediawiki) | Mining | getblocktemplate | INT Core | Standard | Final |
| [44](iip-0044.mediawiki) | Applications | HD Wallet Derivation (SHA3-based) | INT Core | Standard | Final |
| [47](iip-0047.mediawiki) | Consensus | Extended OP_RETURN for Payment Codes | INT Core | Standard | Draft |

## IIP Status Terms

* **Draft** - An IIP that is open for consideration and undergoing rapid iteration.
* **Proposed** - An IIP that is done with initial iteration and ready for review by a wide audience.
* **Final** - An IIP that has been reviewed and accepted as a standard.
* **Active** - An IIP that is intended to remain in a state of perpetual improvement.
* **Withdrawn** - An IIP that has been withdrawn by the author(s).
* **Deferred** - An IIP that is not being considered for immediate adoption.
* **Rejected** - An IIP that has been rejected.
* **Replaced** - An IIP that has been superseded by another IIP.

## IIP Types

* **Standards Track** - Describes changes to the protocol, transaction/block formats, or interoperability.
* **Informational** - Describes design issues or general guidelines.
* **Process** - Describes a process surrounding INTcoin.

## Layers

* **Consensus** - Changes to consensus-critical rules.
* **Peer Services** - Changes to the P2P protocol.
* **API/RPC** - Changes to RPC interface.
* **Applications** - Application-level standards (wallets, etc.).

## Contributing

Please see [IIP-1](iip-0001.mediawiki) for guidelines on contributing.

## License

All IIPs are placed in the public domain unless otherwise specified.

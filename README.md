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

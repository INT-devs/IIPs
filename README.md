# INTcoin Improvement Proposals (IIPs)

People wishing to submit IIPs should first propose their idea in the
[IIP Discussion](https://github.com/INT-devs/IIPs/discussions/) forum.
After discussion has produced a mature proposal, the author should open
a pull request against this repository. IIP numbers are assigned by the
editors during the review process — do not self-assign a number.

Having an IIP listed here does not represent community endorsement or a
commitment to deploy. The IIP repository is a publication medium and
archive. Acceptance of consensus changes ultimately rests with the
INTcoin network participants.

For the full process, see [IIP-1](iip-0001.md).

## IIP Numbering

IIP filenames use zero-padded four-digit numbers: `iip-NNNN.md`.

Numbers are assigned sequentially by editors, grouped into reserved
ranges by layer so related proposals cluster together:

| Range | Layer | Scope |
|-------|-------|-------|
| 0001–0099 | Process | IIP workflow, editorial policy, governance |
| 0100–0199 | Consensus | Block validation, soft/hard forks, script rules |
| 0200–0299 | Peer Services | P2P protocol, transport, message formats |
| 0300–0399 | Cryptography | Post-quantum primitives, key formats, signatures |
| 0400–0499 | Applications | Wallet, address encoding, HD derivation, labels |
| 0500–0599 | API / RPC | JSON-RPC interface, REST, ZMQ notifications |
| 0600–0699 | Mining | Proof-of-work, block template, difficulty adjustment |
| 0700–0799 | Institutional | Custody, RBAC, audit, compliance, external signers |

When a range is exhausted, the editors extend it by allocating the next
available hundred-block. Cross-layer proposals use the range of their
primary layer.

## IIP Types

| Type | Purpose |
|------|---------|
| **Standards Track** | Changes affecting the protocol, network, block/transaction validity, or interoperability. Requires consensus where applicable. |
| **Informational** | Design guidance, background, or conventions that do not require consensus. |
| **Process** | Procedures around the IIP workflow itself, editorial policy, or project governance. |

## IIP Statuses

| Status | Meaning |
|--------|---------|
| **Draft** | Under active development. Open for discussion and revision. |
| **Proposed** | Complete draft submitted for community review. |
| **Final** | Accepted and deployed on mainnet. No further changes except errata. |
| **Active** | Process IIPs that are ongoing (e.g. IIP-1 itself). |
| **Replaced** | Superseded by a later IIP (the replacement is noted). |
| **Withdrawn** | Removed by the author before reaching Final. |
| **Deferred** | Postponed by the author or editors; may be resumed later. |
| **Rejected** | Reviewed and explicitly declined by community consensus. |

## IIP Format

Each IIP file must begin with a YAML front-matter preamble:

```yaml
---
iip: <number>
title: <title>
author: <name> <<email>>
type: <Standards Track | Informational | Process>
layer: <Consensus | Peer Services | Cryptography | Applications | API/RPC | Mining | Institutional>
status: <Draft | Proposed | Final | Active | Replaced | Withdrawn | Deferred | Rejected>
created: <YYYY-MM-DD>
requires: <IIP number(s), optional>
replaces: <IIP number(s), optional>
superseded-by: <IIP number(s), optional>
based-on: <BIP number(s) or external reference, optional>
---
```

The `based-on` field is used when an IIP adapts an existing Bitcoin
Improvement Proposal. It links to the original specification for
context but does not imply identical behaviour — the IIP body must
document all divergences.

Following the preamble: Abstract, Motivation, Specification,
Rationale, Backwards Compatibility, Reference Implementation, and
References sections. See IIP-1 for the full template.

## Index

<!-- Add IIPs to the table below as they are merged. Keep sorted by number. -->
<!-- Status colours: Final/Active = green, Draft/Proposed = none, Replaced/Withdrawn/Rejected/Deferred = red -->

| Number | Layer | Title | Author | Type | Status |
|--------|-------|-------|--------|------|--------|
| [1](iip-0001.md) | | IIP Purpose and Guidelines | INTcoin Core Developers | Process | Active |
| [100](iip-0100.md) | Consensus | OP_CHECKSIG_DILITHIUM | INTcoin Core Developers | Standards Track | Final |
| [103](iip-0103.md) | Consensus | Monetary Policy and Consensus Constants | INTcoin Core Developers | Standards Track | Final |
| [200](iip-0200.md) | Peer Services | Post-Quantum V2 Encrypted Transport | INTcoin Core Developers | Standards Track | Final |
| [300](iip-0300.md) | Cryptography | ML-DSA-87 Digital Signature Scheme | INTcoin Core Developers | Standards Track | Final |
| [301](iip-0301.md) | Cryptography | HD Key Derivation | INTcoin Core Developers | Standards Track | Final |
| [600](iip-0600.md) | Mining | RandomX Proof-of-Work | INTcoin Core Developers | Standards Track | Final |

## Copyright

All IIPs are licensed under the
[MIT License](https://opensource.org/licenses/MIT).

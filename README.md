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
| [101](iip-0101.md) | Consensus | Signet Block Signing | INTcoin Core Developers | Standards Track | Final |
| [102](iip-0102.md) | Consensus | Replace-By-Fee Signaling | INTcoin Core Developers | Standards Track | Final |
| [103](iip-0103.md) | Consensus | Monetary Policy and Consensus Constants | INTcoin Core Developers | Standards Track | Final |
| [104](iip-0104.md) | Consensus | Version Bits Deployments | INTcoin Core Developers | Standards Track | Final |
| [105](iip-0105.md) | Consensus | Height in Coinbase | INTcoin Core Developers | Standards Track | Final |
| [106](iip-0106.md) | Consensus | OP_CHECKLOCKTIMEVERIFY | INTcoin Core Developers | Standards Track | Final |
| [107](iip-0107.md) | Consensus | Relative Lock-Time Using nSequence | INTcoin Core Developers | Standards Track | Final |
| [108](iip-0108.md) | Consensus | OP_CHECKSEQUENCEVERIFY | INTcoin Core Developers | Standards Track | Final |
| [109](iip-0109.md) | Consensus | Duplicate Transaction Output Prevention | INTcoin Core Developers | Standards Track | Final |
| [110](iip-0110.md) | Consensus | Timewarp Mitigation | INTcoin Core Developers | Standards Track | Final |
| [111](iip-0111.md) | Consensus | CPFP Topology Restrictions | INTcoin Core Developers | Standards Track | Final |
| [200](iip-0200.md) | Peer Services | Post-Quantum V2 Encrypted Transport | INTcoin Core Developers | Standards Track | Final |
| [201](iip-0201.md) | Peer Services | Compact Block Relay | INTcoin Core Developers | Standards Track | Final |
| [202](iip-0202.md) | Peer Services | ADDRv2 Address Format | INTcoin Core Developers | Standards Track | Final |
| [203](iip-0203.md) | Peer Services | Compact Block Filters | INTcoin Core Developers | Standards Track | Final |
| [204](iip-0204.md) | Peer Services | Erlay Transaction Reconciliation | INTcoin Core Developers | Standards Track | Final |
| [205](iip-0205.md) | Peer Services | Header Announcements | INTcoin Core Developers | Standards Track | Final |
| [206](iip-0206.md) | Peer Services | Fee Filter | INTcoin Core Developers | Standards Track | Final |
| [207](iip-0207.md) | Peer Services | WTXID Relay | INTcoin Core Developers | Standards Track | Final |
| [208](iip-0208.md) | Peer Services | Mempool P2P Message | INTcoin Core Developers | Standards Track | Final |
| [209](iip-0209.md) | Peer Services | Bloom Filters (Disabled) | INTcoin Core Developers | Standards Track | Final |
| [210](iip-0210.md) | Peer Services | Package Relay | INTcoin Core Developers | Standards Track | Draft |
| [211](iip-0211.md) | Peer Services | Reject Messages (Deprecated) | INTcoin Core Developers | Informational | Final |
| [300](iip-0300.md) | Cryptography | ML-DSA-87 Digital Signature Scheme | INTcoin Core Developers | Standards Track | Final |
| [301](iip-0301.md) | Cryptography | HD Key Derivation | INTcoin Core Developers | Standards Track | Final |
| [400](iip-0400.md) | Applications | Address Encoding | INTcoin Core Developers | Standards Track | Final |
| [402](iip-0402.md) | Applications | Message Signing | INTcoin Core Developers | Standards Track | Final |
| [403](iip-0403.md) | Applications | Wallet Labels | INTcoin Core Developers | Standards Track | Final |
| [404](iip-0404.md) | Applications | Partially Signed Transactions | INTcoin Core Developers | Standards Track | Draft |
| [405](iip-0405.md) | Applications | Reusable Payment Codes | INTcoin Core Developers | Standards Track | Draft |
| [406](iip-0406.md) | Applications | Payjoin | INTcoin Core Developers | Standards Track | Draft |
| [407](iip-0407.md) | Applications | Bech32 Encoding | INTcoin Core Developers | Standards Track | Final |
| [408](iip-0408.md) | Applications | Output Descriptors | INTcoin Core Developers | Standards Track | Final |
| [409](iip-0409.md) | Applications | ISMS Multisig Setup | INTcoin Core Developers | Standards Track | Final |
| [410](iip-0410.md) | Applications | Multisig HD Derivation Path | INTcoin Core Developers | Standards Track | Final |
| [411](iip-0411.md) | Applications | Anti-Fee-Sniping | INTcoin Core Developers | Standards Track | Final |
| [412](iip-0412.md) | Applications | Timelock Recovery | INTcoin Core Developers | Standards Track | Draft |
| [413](iip-0413.md) | Applications | DNS Payment Instructions | INTcoin Core Developers | Standards Track | Draft |
| [406](iip-0406.md) | Applications | Payjoin | INTcoin Core Developers | Standards Track | Draft |
| [600](iip-0600.md) | Mining | RandomX Proof-of-Work | INTcoin Core Developers | Standards Track | Final |
| [601](iip-0601.md) | Mining | Block Template Protocol | INTcoin Core Developers | Standards Track | Final |
| [700](iip-0700.md) | Institutional | Institutional Custody Module | INTcoin Core Developers | Standards Track | Draft |

## Copyright

All IIPs are licensed under the
[MIT License](https://opensource.org/licenses/MIT).

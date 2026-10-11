# STCyberProject

Course project repository for **S-INFO-444 (QUIC)**.

## Project context

This project is based on the provided instructions in `S_INFO_444__Project.pdf`.
The goal is to implement the **QUIC Address Discovery extension** (draft `ietf-quic-address-discovery-00`) in the Rust [`quiche`](https://github.com/cloudflare/quiche) implementation.

## Repository content

- `S_INFO_444__Project.pdf`: official project statement and requirements.
- `quiche`: Git submodule pinned to commit `c6489c8` (as requested in the instructions).

## Expected work

According to the instructions, the implementation should include:

- Extension support in the core `quiche` crate.
- Updates to `quiche-client` and `quiche-server` examples to enable the extension.
- Tests for normal behavior.
- Tests covering attack scenarios and implemented defenses.

## Deliverables

The final submission is expected to contain:

1. A PDF report describing implementation choices, validation/testing approach, interoperability testing, and security analysis.
2. The modified `quiche` repository (including code and tests for the extension).

## Getting started

Initialize the submodule before working on the implementation:

```bash
git submodule update --init --recursive
```

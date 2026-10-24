<div align="center">
  <a href="https://tapefly.xyz">
    <img src="https://raw.githubusercontent.com/tapefly/tapefly/main/app/icon.svg" width="104" alt="TapeFly">
  </a>
  <h1>TapeFly</h1>
  <p><strong>A playable fruit fly whose entire brain is 50 NAND gates.</strong></p>
  <p>Deterministic every day · replayable every tick · verified on chain</p>
  <p>
    <a href="https://tapefly.xyz"><img src="https://img.shields.io/badge/play-tapefly.xyz-10b981" alt="Play TapeFly"></a>
    <a href="https://github.com/tapefly/tapefly/actions/workflows/ci.yml"><img src="https://img.shields.io/github/actions/workflow/status/tapefly/tapefly/ci.yml?branch=main&label=CI" alt="CI"></a>
    <a href="https://github.com/tapefly/tapefly"><img src="https://img.shields.io/badge/tests-95%2F95-2ea44f" alt="95 tests passing"></a>
    <a href="https://tapefly.xyz/tapeout"><img src="https://img.shields.io/badge/TapeOut-Circuit%20%231-7c5cff" alt="TapeOut Circuit 1"></a>
    <a href="https://github.com/tapefly/tapefly/blob/main/LICENSE"><img src="https://img.shields.io/badge/license-MIT-blue" alt="MIT license"></a>
  </p>
</div>

---

**TapeFly turns a NAND circuit into a living game character.** Six senses become a
12-bit word; a 50-gate brain returns a move and an escape reflex; every tick is
folded into a SHA-256 hash chain. The input space is exactly **4,096 words**, so
every possible decision can be checked.

The official brain is **TapeOut circuit #1 on BNB Chain**. The committed 350 bytes
match the on-chain netlist, and all 4,096 free read-only `eval` calls return the
same answer as the local simulation.

## Start here

| Try it | What you get |
| --- | --- |
| [Play today's dish](https://tapefly.xyz) | Watch eight sibling flies survive one deterministic UTC day |
| [Build a brain](https://tapefly.xyz/build) | Turn instincts or readable rules into a NAND circuit |
| [Read the docs](https://tapefly.xyz/docs) | Product, science, TapeOut integration, economics and roadmap |
| [Inspect Circuit #1](https://tapefly.xyz/tapeout) | Processor, transaction, stored bytes and exhaustive verification |
| [Use the agent API](https://tapefly.xyz/agents) | Open JSON for all game and circuit data |
| [Read the source](https://github.com/tapefly/tapefly) | MIT code, tests, CI, architecture and reproducible evidence |

## Live proof

| Claim | Verified value |
| --- | --- |
| Official brain | `FFW-NAND/1`, 50 NAND gates, depth 9 |
| Circuit | `#1` on processor `0x6Ac12D578e29D340f178E18eB2C297C7915E011C` |
| Answers | `4,096 / 4,096` identical to the committed netlist |
| Stored bytes | Exact match, SHA-256 `a763117011fe4c4be7106d9b0d2c78fe79b81c15ccc2a6531c9263b4f443d4dd` |
| Test suite | `95 / 95` passing |
| Production | HTTPS live at [tapefly.xyz](https://tapefly.xyz) |
| Dependency audit | 0 npm advisories |

Verify the deployed brain yourself:

```bash
git clone https://github.com/tapefly/tapefly.git
cd tapefly
npm ci
npm run verify:onchain
```

No wallet, account, token or private key is required.

## Why it is different

| Typical on-chain AI or game claim | TapeFly |
| --- | --- |
| Model behavior is hidden in a server | A 50-gate circuit decides |
| Verification means trusting the operator | Every one of 4,096 inputs can be checked |
| Game history depends on a private database | A UTC date reproduces the transcript |
| Users buy an asset without understanding it | Players design the brain before choosing to own it |
| Technical demos stop at a transaction | The deployed circuit is tested against the complete truth table |

## Repositories

| Repository | Purpose |
| --- | --- |
| [**tapefly**](https://github.com/tapefly/tapefly) | Live product, deterministic engine, circuit compiler, API, tests and on-chain verifier |
| [**.github**](https://github.com/tapefly/.github) | Organization profile and community health files |

Retired predecessor code is preserved under `tapefly-v1-archive`; it is not the
current product.

## What is next

TapeFly is live on BNB Chain. The next integration milestone is a real circuit on
**X Layer**, using X Layer block data for the public daily seed and opening one
free arena for human- and AI-designed brains. X Layer is not claimed as live until
there is a processor, circuit ID and successful exhaustive check.

## Community

- Read [CONTRIBUTING.md](https://github.com/tapefly/tapefly/blob/main/CONTRIBUTING.md)
- Report vulnerabilities privately through the [Security tab](https://github.com/tapefly/tapefly/security/advisories/new)
- Follow [CODE_OF_CONDUCT.md](https://github.com/tapefly/tapefly/blob/main/CODE_OF_CONDUCT.md)
- Track public changes in [CHANGELOG.md](https://github.com/tapefly/tapefly/blob/main/CHANGELOG.md)

<div align="center"><sub>TapeFly · MIT licensed · every number replays</sub></div>

<div align="center">
  <a href="https://tapefly.xyz">
    <img src="https://raw.githubusercontent.com/tapefly/tapefly/main/public/tapefly-circuit1-onchain.png" width="180" alt="TapeFly circuit #1 on chain">
  </a>
  <h1>TapeFly</h1>
  <p><strong>A playable fruit fly whose entire brain is 50 NAND gates.</strong></p>
  <p>Deterministic every day. Replayable every tick. Verified on chain.</p>
  <p>
    <a href="https://tapefly.xyz"><strong>Play TapeFly</strong></a> ·
    <a href="https://github.com/tapefly/tapefly">Source code</a> ·
    <a href="https://tapefly.xyz/docs">Docs</a> ·
    <a href="https://tapefly.xyz/tapeout">Circuit #1</a>
  </p>
</div>

---

## What is TapeFly?

TapeFly turns a NAND circuit into a living game character. Six senses become a 12-bit input, a 50-gate brain returns a move and an escape reflex, and every tick is folded into a SHA-256 hash chain.

The input space is exactly **4,096 words**, so every possible decision can be checked. There is no hidden model and no private game database.

## Live proof

| Proof | Verified value |
| --- | --- |
| Official brain | `FFW-NAND/1`, 50 NAND gates, depth 9 |
| On-chain deployment | TapeFly processor, circuit `#1` |
| Exhaustive check | `4,096 / 4,096` answers identical |
| Stored netlist | 350 bytes, byte-for-byte match |
| Test suite | 95 tests passing |
| Network | BNB Chain; X Layer is the next integration milestone |

```bash
npm run tapeout -- verify \
  --processor 0x6Ac12D578e29D340f178E18eB2C297C7915E011C \
  --id 1
```

## Main repository

[**tapefly/tapefly**](https://github.com/tapefly/tapefly) contains the live product, deterministic simulation engine, NAND compiler, complete test suite, API, on-chain verification tools and public documentation.

## Principles

- The game is free to play and verify.
- Every published day can be recomputed from its date.
- Every on-chain brain can be checked against all possible inputs.
- No private key, seed phrase, or hidden game state belongs in this organization.
- TapeFly is independent and is not an official TapeOut, Binance, OKX or X Layer product.

<div align="center"><sub>TapeFly · MIT licensed · every number replays</sub></div>

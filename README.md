# AUCTI / ON

**Hypothetical PoC.** GitHub-as-auction for **used parts** that are minted but technically used.

## Lot
- **Item:** SSD NVME (used / minted-but-used)
- **Provenance:** bought from a bookseller between Farme and Teixeira (Ipanema) for **10 BRL**
- **Opening pin:** `V.10.000.000`
- **Buyer fee:** near zero (no finder’s-fee theater)
- **Seller share:** **10% of all auction proceeds** go to the bookseller — assured

## Rules
1. Every new bid is a **pull request**.
2. Owner validates a bid by **merging** that PR to `main`.
3. **`main` is the current winning bid.**
4. Buyer fee ≈ 0. Process owned by the auction runner.
5. On settlement, **10% of proceeds** remit to the original bookseller.

## How to bid (theory)
1. Fork or branch from `main`.
2. Update `CURRENT_BID.md` with your bid tag / amount and identity.
3. Open a PR titled with your bid (e.g. `BID V.10.000.001`).
4. If merged, that bid becomes live on `main`.

This repo is a strictly theoretical / alleged / hypothetical test surface — not escrow, not payment rails. Magic without Penn & Teller.

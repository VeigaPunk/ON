# AUCTI / ON

**Hypothetical PoC.** GitHub-as-auction for **used parts** that are minted but technically used.

## Lot
- **Item:** SSD NVME (used / minted-but-used)
- **Found in:** *Loucura* by Carmen Dametto — red cover, **1986**
- **Note:** sister of the person on the back of the book
- **Where bought:** bookseller between Farme and Teixeira (Ipanema), **10 BRL**
- **Opening pin:** `V.10.000.000`

## Fees
| Slice | Rate | Notes |
|-------|------|-------|
| **Buyer** | **3%** on top of hammer | Covers transaction |
| **Finder’s** | **~5%** | Stated target |
| **Auctioneer** | **0%** | If run on GitHub via PR + merge |
| **Bookseller / hobo** | **10% of all proceeds** | Supporting role |
| **His dog** | **0.1%** | Whiskas endowment |

## Rules
1. Every new bid is a **pull request**.
2. Owner validates a bid by **merging** that PR to `main`.
3. **`main` is the current winning bid.**
4. Auctioneer fee is zero on this path — process ownership, not a take.
5. On settlement: buyer pays hammer + 3%; bookseller 10%; dog 0.1%; finder’s ~5% as stated.

## How to bid (theory)
1. Fork or branch from `main`.
2. Update `CURRENT_BID.md` with your bid tag / amount and identity.
3. Open a PR titled with your bid (e.g. `BID V.10.000.001`).
4. If merged, that bid becomes live on `main`.

Strictly theoretical / alleged / hypothetical test surface — not escrow, not payment rails.

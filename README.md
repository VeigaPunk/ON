# AUCTI / ON

**Hypothetical PoC.** GitHub-as-auction for **used parts** that are minted but technically used.

## Lot
- **Item:** SSD NVME (used / minted-but-used)
- **Found in:** *Loucura* by Carmen Dametto — red cover, **1986**
- **Where bought:** bookseller between Farme and Teixeira (Ipanema), **10 BRL**
- **Opening ask:** **$10,000,000 USD** (`V.10.000.000`) — initial commit
- **Bids:** dollar-denominated PRs; owner validates by merge to `main`
- **No-sale:** under $10M USD → stays vaulted with custodian

## Fees
| Slice | Rate | Notes |
|-------|------|-------|
| **Buyer** | **3%** on hammer | Transaction cover |
| **Finder’s** | **~5%** | Stated target |
| **Auctioneer** | **0%** | GitHub PR + merge |
| **Supporting** | **10%** | Hobo if available; else **5% mass movers + 5% whale movers** |
| **Dog** | **0.1%** | Whiskas (hobo path) |

## Rules
1. Bid = pull request (USD only).
2. Merge to `main` = validated bid.
3. `main` = current winning bid.
4. Floor: $10M USD.

Strictly theoretical / alleged / hypothetical — not escrow, not payment rails.

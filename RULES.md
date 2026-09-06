# Auction rules (hypothetical)

- Medium: GitHub pull requests (may accumulate; owner reviews / merges when ready)
- Validation: merge to `main` by owner
- Live state: contents of `main` / `CURRENT_BID.md`
- Opening ask: **$10,000,000 USD** (`V.10.000.000`)
- Bids: **dollar-denominated** only
- Settlement: confirmation only; else cascade to previous winner

## Bidder classes
- **Mass / groups:** pay **equal**, **isonomically distributed**. Each group bid must **attach # of members**.
- **Whale movers:** bid **individually only**. Identity on the bid: **initials only**.

## Settlement
1. Confirm on settlement.
2. No confirm → cascade to previous winner.

## Fee stack
- Buyer 3% · Finder’s ~5% · Auctioneer 0%
- Supporting 10%: hobo (+ dog 0.1%) if available; else 5% mass + 5% whale

Owner owns process. Good eyes for treachery.

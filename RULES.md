# Auction rules (hypothetical)

- Medium: GitHub pull requests
- Validation: merge to `main` by owner
- Live state: contents of `main` / `CURRENT_BID.md`
- Opening ask: **$10,000,000 USD** (`V.10.000.000`)
- Bids: **dollar-denominated** only; owner validates by merge
- Currency: USD ask/hammer. BRL purchase is provenance only.
- No-sale under ask: lot stays vaulted with custodian

## Bidder classes
- **Mass movers:** pay **equal**, **isonomically distributed**
- **Whale movers:** bid **individually only**

## Settlement (simple)
1. Winning merged bid needs **confirmation on settlement** only.
2. If confirmation fails / is withheld → **fallback cascades to the previous winner** on `main` history.
3. No extra ceremony. Confirm or cascade.

## Fee stack
- **Buyer fee:** 3% on hammer
- **Finder’s fee:** ~5%
- **Auctioneer fee:** 0% (PR + merge)
- **Supporting 10%:** hobo 10% (+ dog 0.1%) if available; else 5% mass + 5% whale

Owner owns process.

# Auction rules (hypothetical)

- Medium: GitHub pull requests
- Validation: merge to `main` by owner
- Live state: contents of `main` / `CURRENT_BID.md`
- Opening ask: **$10,000,000 USD** (`V.10.000.000`) — initial commit version
- Bids: **dollar-denominated** only; PRs merged to `main` when owner validates
- Currency: USD ask/hammer. BRL purchase is provenance only.
- No-sale: if ask unmet, lot remains with custodian, intact

## Bidder classes
- **Mass movers:** pay **equal**, **isonomically distributed** — same terms, flat among the mass. No preferential individual carve-outs inside the mass pool.
- **Whale movers:** may bid **individually only** — one whale, one bid identity. No pooled whale syndicate bids.

## Fee stack
- **Buyer fee:** 3% on hammer — transaction cover
- **Finder’s fee:** ~5%
- **Auctioneer fee:** 0% (GitHub PR + merge)
- **Supporting 10%:**
  - If hobo / bookseller available → **10%** to him (+ **0.1%** dog Whiskas)
  - If no hobo available → **5% mass movers** + **5% whale movers**

Owner owns process.

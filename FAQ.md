# Frequently Asked Questions (FAQ)

<p align="center">
  <strong>TurboUSD Protocol - Common Questions Answered</strong>
</p>

---

## General Questions

### What is TurboUSD?

TurboUSD is an independently issued TRC20 stablecoin on the TRON blockchain, designed to maintain a 1:1 peg with the US Dollar. It enables fast, low-cost transactions for users seeking USD-stable value on TRON.

### Is TurboUSD the same as Tether's USDT?

**No.** TurboUSD is completely separate from Tether and Tether's USDT. They are:
- Different smart contracts
- Different organizations
- Different teams
- Different reserves
- Different governance

The use of "USDT" as a symbol is a technical identifier only and does not imply any affiliation.

### Why does TurboUSD use the USDT symbol?

The USDT symbol was chosen as a common identifier for USD-pegged tokens on TRON. However, we want to be explicitly clear:

- **TurboUSD Contract**: `TJHkd8J8dNfGDm8ZbpLjS9gb3KZHFpN4Sj`
- **Tether USDT Contract**: `TR7NHqjeKQxGTCi8q8ZY4pL8otSzgjLj6t`

**Always verify the contract address before transacting.**

---

## Trust & Safety

### Why is TurboUSD flagged as "Suspicious" on TronScan?

TronScan uses automated systems to flag tokens based on various criteria. New tokens, especially those with administrative functions (mint, burn, pause) and symbol similarities to established tokens, often receive initial flags.

We are:
1. Fully transparent about our smart contract functions
2. Actively appealing through official channels
3. Building legitimate use cases and documentation

See our [Transparency Report](TRANSPARENCY.md) for full details.

### Is TurboUSD safe to use?

All cryptocurrency carries risk. We recommend:
- Reading our full documentation
- Understanding the risks in [LEGAL_NOTICE.md](LEGAL_NOTICE.md)
- Only using amounts you can afford to lose
- Verifying contract addresses manually
- Conducting your own research (DYOR)

### Has TurboUSD been audited?

A formal smart contract audit has not yet been completed. We are pursuing audits and will publish results publicly when available. The contract code is open for review on TronScan.

---

## Technical Questions

### What is the TurboUSD contract address?

```
TJHkd8J8dNfGDm8ZbpLjS9gb3KZHFpN4Sj
```

### What network is TurboUSD on?

TurboUSD is a TRC20 token on the **TRON** blockchain.

### How many decimals does TurboUSD have?

**6 decimals**, matching standard TRC20 USDT.

### What are the smart contract administrative functions?

| Function | Purpose |
|----------|---------|
| `mint()` | Create new tokens |
| `burn()` | Destroy tokens |
| `pause()` | Halt all transfers |
| `blacklist()` | Block specific addresses |
| `transferOwnership()` | Change contract owner |

These functions exist for supply management, security, and regulatory compliance. See [TRANSPARENCY.md](TRANSPARENCY.md) for detailed explanations.

---

## Wallet Questions

### How do I add TurboUSD to my wallet?

1. Open your TRON-compatible wallet
2. Find "Add Custom Token" or "Import Token"
3. Enter: `TJHkd8J8dNfGDm8ZbpLjS9gb3KZHFpN4Sj`
4. Details auto-populate: Symbol = USDT, Decimals = 6

### Which wallets support TurboUSD?

Any TRC20-compatible wallet works, including:
- TronLink
- Trust Wallet
- TokenPocket
- Klever Wallet
- Ledger (with TRON app)

### Why doesn't my wallet show the TurboUSD logo?

Wallet logo display requires listing with wallet providers (Trust Wallet, etc.). We are currently working on these integrations. The token will still function correctly without logo display.

---

## Trading & Liquidity

### Where can I buy TurboUSD?

Currently, TurboUSD is in early stages. We are working on:
- DEX liquidity pools (SunSwap, JustSwap)
- Exchange listings
- Direct treasury swaps

Check our [Roadmap](ROADMAP.md) for listing progress.

### Why isn't TurboUSD on CoinGecko or CoinMarketCap?

Listing requires verification and trading history. We have submitted applications and are working through the approval process. Track progress at [turbousd.io/listing-progress](https://turbousd.io/listing-progress).

### What is the treasury wallet?

```
TMVCgcoajwicbAXc35FLkzkCNstycGzkv
```

This wallet holds reserve assets backing TurboUSD tokens. Balance is publicly verifiable on TronScan.

---

## Legal & Compliance

### Is TurboUSD legal?

Cryptocurrency legality varies by jurisdiction. Users are responsible for determining whether TurboUSD is legal in their location and complying with local laws. See [LEGAL_NOTICE.md](LEGAL_NOTICE.md).

### Do I need KYC to use TurboUSD?

The TurboUSD Protocol itself does not require KYC. However:
- Exchanges or services may require KYC
- Future regulations may change requirements
- The blacklist function exists for compliance

### Why does the contract have a blacklist function?

The blacklist function enables:
- Regulatory compliance (sanctions, legal orders)
- Fraud prevention (stolen funds)
- Security response (exploited addresses)

This is standard for regulated stablecoins including USDT and USDC.

---

## Development & Community

### Is TurboUSD open source?

The website and documentation are open source under MIT License. The smart contract code is verifiable on TronScan.

### How can I contribute?

See [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines on:
- Bug reports
- Feature suggestions
- Code contributions
- Documentation improvements

### How do I contact the team?

| Purpose | Contact |
|---------|---------|
| General | contact@turbousd.io |
| Security | security@turbousd.io |
| Development | dev@turbousd.io |
| Legal | legal@turbousd.io |
| Telegram | [t.me/turbousd](https://t.me/turbousd) |
| Twitter | [@turbousd](https://twitter.com/turbousd) |

---

## Didn't Find Your Answer?

1. **Read the Docs**: Check [TRANSPARENCY.md](TRANSPARENCY.md) and [LEGAL_NOTICE.md](LEGAL_NOTICE.md)
2. **Open an Issue**: [GitHub Issues](https://github.com/turbousdio/turbousdio/issues)
3. **Join Telegram**: [t.me/turbousd](https://t.me/turbousd)
4. **Email Us**: contact@turbousd.io

---

<p align="center">
  <em>Questions help us improve. Thank you for your interest in TurboUSD.</em>
</p>

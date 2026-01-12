# Changelog

All notable changes to TurboUSD Protocol will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

---

## [Unreleased]

### Planned
- TronScan verification appeal resolution
- DEX liquidity pool establishment
- CoinGecko listing
- Trust Wallet logo recognition
- Smart contract audit

---

## [1.0.0] - 2026-01-12

### Added
- **Smart Contract**: TurboUSD TRC20 token deployed on TRON mainnet
  - Contract Address: `TJHkd8J8dNfGDm8ZbpLjS9gb3KZHFpN4Sj`
  - Symbol: USDT
  - Decimals: 6
  - Total Supply: 100,000,000 tokens
- **Website**: Official website launched at turbousd.io
  - Landing page with protocol overview
  - Market data section with real-time TronScan integration
  - Swap interface for USDT ↔ TurboUSD
  - Wallet import guides for TronLink, Trust Wallet, TokenPocket, Klever
  - Liquidity pools section
  - Contract transparency section
  - FAQ section
- **Documentation**:
  - Technical whitepaper published
  - Terms of Service
  - Privacy Policy
  - Risk Disclaimer
- **API Endpoints**:
  - `/price-feed.json` - Price and metadata
  - `/token-info.json` - CoinGecko-compatible format
  - `/trust-wallet/info.json` - Trust Wallet metadata
  - `/tokenlist.json` - Uniswap token list standard
- **Treasury**: Reserve wallet established at `TMVCgcoajwicbAXc35FLkzkCNstycGzkv`

### Documentation
- README.md with comprehensive project overview
- TRANSPARENCY.md with full disclosure and TronScan status
- LEGAL_NOTICE.md with disclaimers and non-affiliation statement
- ROADMAP.md with development phases
- FAQ.md with common questions
- VERIFICATION.md with authenticity verification guide
- SECURITY.md with vulnerability reporting policy
- CONTRIBUTING.md with contribution guidelines
- LICENSE (MIT)
- CHANGELOG.md (this file)
- GitHub issue templates for community feedback

### Security
- Smart contract deployed with administrative functions:
  - Mint/Burn for supply management
  - Pause for emergency response
  - Blacklist for regulatory compliance
- Security policy established for vulnerability reporting

### Known Issues
- TronScan "Suspicious" flag - Appeal in progress
- Not yet listed on DEXs - In progress
- Not yet listed on CoinGecko/CMC - Applications submitted
- Trust Wallet logo not yet displaying - PR submitted

---

## Version History Summary

| Version | Date | Highlights |
|---------|------|------------|
| 1.0.0 | 2026-01-12 | Initial launch - Contract, website, documentation |

---

## How to Read This Changelog

- **Added**: New features or functionality
- **Changed**: Updates to existing features
- **Deprecated**: Features planned for removal
- **Removed**: Features that have been removed
- **Fixed**: Bug fixes
- **Security**: Security-related changes

---

## Links

- [Full Roadmap](ROADMAP.md)
- [Transparency Report](TRANSPARENCY.md)
- [Website](https://turbousd.io)
- [TronScan Contract](https://tronscan.org/#/token20/TJHkd8J8dNfGDm8ZbpLjS9gb3KZHFpN4Sj)

---

<p align="center">
  <em>Transparency in every update.</em>
</p>

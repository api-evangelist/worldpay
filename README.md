# Worldpay

Worldpay is a global payment processing platform (part of FIS) providing REST APIs for payment acceptance, transaction management, tokenization, recurring billing, fraud prevention, and global acquiring services. It supports card payments, digital wallets, alternative payment methods, payouts, foreign exchange, and hosted payment pages across more than 146 countries.

## Developer Resources

- **Developer Hub:** https://docs.worldpay.com/
- **API Reference:** https://docs.worldpay.com/access/apis
- **Getting Started:** https://docs.worldpay.com/access/products/card-payments/v5/get-started
- **API Principles:** https://docs.worldpay.com/access/products/reference/api-principles
- **Release Notes:** https://docs.worldpay.com/access/products/releases
- **GitHub:** https://github.com/Worldpay

## Status Pages

- **Access Worldpay:** https://status.access.worldpay.com/
- **Worldpay Platform:** https://status.worldpay.com/
- **WPG (WorldPay Gateway):** https://status.wpg.worldpay.com/

## APIs

| API | Description |
|-----|-------------|
| Card Payments | Accept online card payments, digital wallets, recurring payments |
| Tokens | Tokenize card data for PCI-compliant storage |
| Verified Tokens | CIT-compliant token creation with card validation |
| Card Payouts | Send funds to customer cards (Standard or Fast Access) |
| Account Payouts | Send funds to customer bank accounts |
| Account Transfers | Move funds between accounts |
| FraudSight | Standalone fraud risk assessment |
| 3DS | 3D Secure identity verification for SCA compliance |
| APMs | Alternative payment methods (eWallets, BNPL, local schemes) |
| FX | Foreign exchange and currency conversion |
| Hosted Payment Pages | Low-code PCI-compliant payment form integration |
| Events | Webhooks for real-time payment status updates |
| Payment Queries | Query and retrieve transaction data |
| Beneficiary Account Verifications | Validate bank account details before payouts |
| Split Payments | Divide payments among merchants and parties |
| Statements | Retrieve account statements for reconciliation |
| Balances | Retrieve account balance data |
| Sessions | Delegate payments using provided methods |
| SCA Exemptions | Maximize frictionless checkout via issuer insights |
| Card BIN Data | Lookup card metadata from PAN or tokens |
| Money Transfers | Push funds to eligible cards in 30 minutes or less |
| Parties | Manage parties, payout instruments, and beneficial owners |
| Card Verifications | Validate card details to enhance authorization rates |

## Authentication

All Access APIs use HTTP Basic Authentication with Base64-encoded credentials. Separate credentials exist for test (`try.access.worldpay.com`) and live (`access.worldpay.com`) environments. DNS whitelisting is required for both domains.

## API Versioning

APIs use header-based versioning via the `WP-Api-Version` header in `YYYY-MM-DD` format (e.g., `2024-06-01`). Legacy APIs use media type versioning.

## Profile

This repository contains an APIs.json 0.19 profile for Worldpay maintained by [API Evangelist](https://apievangelist.com).

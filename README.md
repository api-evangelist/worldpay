# Worldpay

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

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

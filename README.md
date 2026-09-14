# Awesome Fintech

A curated collection of **popular, well-maintained open source libraries and developer tools** for fintech engineers. The focus is on production-grade projects with real-world traction used by banks, payment companies, and financial platforms.

Projects must demonstrate meaningful adoption (stars, forks, contributors, or industry usage), active maintenance, clear open source licensing (Apache, MIT, AGPL, BSD, etc.), and practical utility for building payments, banking, compliance, data, and financial systems. No weekend projects, AI-agent experiments, personal finance apps, or cryptocurrency/blockchain tools.

**This list is not for trading or market analysis.** Do not submit technical indicators, candlestick/OHLC or other market charts, backtesting frameworks, stock/quote APIs, quarterly reports, SEC filing scrapers, fundamentals, or similar investor-research tools. Those belong in quant/trading lists, not here.

## Table of Contents
- [Payments & Integrations](#payments--integrations)
- [Banking Infrastructure](#banking-infrastructure)
- [Compliance & Sanctions](#compliance--sanctions)
- [Financial Data & APIs](#financial-data--apis)
- [Money, Currency & Formatting](#money-currency--formatting)
- [Charts & Visualization](#charts--visualization)
- [Billing & Subscriptions](#billing--subscriptions)
- [Payment UI Components](#payment-ui-components)
- [Learning Resources](#learning-resources)
- [Related Awesome Lists](#related-awesome-lists)

## Payments & Integrations
- [Active Merchant](https://github.com/activemerchant/active_merchant) – Payment abstraction library extracted from Shopify, with a consistent Ruby API across many gateways.
- [Gringotts](https://github.com/aviabird/gringotts) – Unified API for integrating dozens of payment gateways in Elixir/Phoenix applications.
- [Hyperswitch](https://github.com/juspay/hyperswitch) – Open source, composable payments orchestration platform supporting 100+ processors with intelligent routing and PCI compliance options.
- [Hyperswitch Prism](https://github.com/juspay/hyperswitch-prism) – Stateless unified payment processing library with multi-language SDKs for integrating multiple processors.
- [jPOS](https://github.com/jpos/jPOS) – Java payments platform for ISO 8583, ISO 20022, and EMV, used in production gateways and switches since 1998.
- [Mojaloop](https://github.com/mojaloop/mojaloop) – Open source software for interoperable real-time payment platforms, used to build national switches and financial-inclusion rails.
- [Omnipay](https://github.com/thephpleague/omnipay) – Framework-agnostic PHP library for integrating many payment gateways behind a single, consistent API.
- [PayPal Checkout Components](https://github.com/paypal/paypal-checkout-components) – Official JavaScript integration components for PayPal Buttons and Checkout experiences.
- [Payum](https://github.com/Payum/Payum) – PHP payment processing library covering cards, offsite purchasing, subscriptions, and payouts.
- [React Native Payments](https://github.com/naoufal/react-native-payments) – Cross-platform library for adding Apple Pay and Google Pay to React Native applications.

## Banking Infrastructure
- [ACH](https://github.com/moov-io/ach) – Reader, writer, and validator for NACHA Automated Clearing House (ACH) files used for US electronic payments.
- [Apache Fineract](https://github.com/apache/fineract) – Apache project providing core banking functionality used by financial institutions serving the underbanked.
- [Blnk](https://github.com/blnkfinance/blnk) – Open source ledger and financial core for wallets, billing, and money-movement products.
- [Fed](https://github.com/moov-io/fed) – Fuzzy lookup library for FedACH and FedWire ABA routing numbers and bank names.
- [Formance Ledger](https://github.com/formancehq/ledger) – Programmable open source ledger with atomic multi-posting transactions and a built-in DSL (Numscript).
- [iban4j](https://github.com/arturmkrtchyan/iban4j) – Java library for IBAN and BIC validation, parsing, and generation.
- [IBANTools](https://github.com/Simplify/ibantools) – TypeScript/JavaScript library for validation, creation, and extraction of IBAN, BBAN, and BIC/SWIFT numbers.
- [Image Cash Letter](https://github.com/moov-io/imagecashletter) – Reader, writer, and validator for X9 Image Cash Letter (Check 21) files used in US check clearing.
- [ISO 8583](https://github.com/moov-io/iso8583) – Go library for marshaling and unmarshaling ISO 8583 messages used in card and POS systems.
- [ISO 8583 Connection](https://github.com/moov-io/iso8583-connection) – Connection handling and request/reply matching for ISO 8583 in Go.
- [ISO-8583 Socket Queue](https://github.com/juks/iso-8583-socket-queue) – Node.js ISO 8583 gateway for banking and POS system communication.
- [iso20022.js](https://github.com/svapnil/iso20022.js) – TypeScript library to create ACH, SEPA, FedNow, SWIFT, and RTP payment initiations and process bank statements.
- [JReactive-8583](https://github.com/kpavlov/jreactive-8583) – Netty-based Java ISO 8583 client and server for connecting to card and POS networks.
- [Metro 2](https://github.com/moov-io/metro2) – Parser and generator for Metro 2 consumer credit reporting files used by credit bureaus.
- [Open Bank Project](https://github.com/OpenBankProject/OBP-API) – Open source REST API platform for banks supporting Open Banking, PSD2, XS2A, and Open Finance.
- [Prowide Core](https://github.com/prowide/prowide-core) – Java model and parsers for SWIFT MT (FIN) messages used in correspondent banking.
- [Prowide ISO 20022](https://github.com/prowide/prowide-iso20022) – Java parser and business model for ISO 20022 MX messages (pacs, camt, pain, and related sets).
- [schwifty](https://github.com/mdomke/schwifty) – Python library for parsing and validating IBANs and BICs with country-specific bank registry data.
- [Sequence](https://github.com/hoophq/sequence) – Immutable, scalable ledger service for recording financial transactions with strong auditability.
- [TigerBeetle](https://github.com/tigerbeetle/tigerbeetle) – Financial transactions database designed for mission-critical safety and high throughput.
- [Wire](https://github.com/moov-io/wire) – Parser and writer for FedWire funds service files used for high-value US dollar transfers.

## Compliance & Sanctions
- [OpenSanctions](https://github.com/opensanctions/opensanctions) – Open database and tools for sanctions lists, politically exposed persons (PEP), and persons of interest used in KYC/AML.
- [python-stdnum](https://github.com/arthurdejong/python-stdnum) – Python library to parse, validate, and format standard numbers including IBAN, VAT IDs, and national identifiers.
- [Watchman](https://github.com/moov-io/watchman) – Search across US trade sanctions lists (OFAC, etc.) for compliance screening.

## Financial Data & APIs
- [FRED API](https://github.com/mortada/fredapi) – Python client for Federal Reserve Economic Data (FRED) and ALFRED macroeconomic series.
- [FundsXML](https://www.fundsxml.org/) – Open, royalty-free XML standard for fund data exchange and regulatory reporting across the European fund industry ([schema](https://github.com/fundsxml/schema)).

## Money, Currency & Formatting
- [accounting](https://github.com/leekchan/accounting) – Go utilities for formatting monetary amounts and currencies in a locale-friendly way.
- [accounting.js](https://github.com/openexchangerates/accounting.js) – Lightweight JavaScript library for number, money, and currency parsing/formatting (localizable, zero deps).
- [currency.js](https://github.com/scurker/currency.js) – Lightweight JavaScript library for precise currency value handling and arithmetic.
- [Dinero.js](https://github.com/dinerojs/dinero.js) – Immutable, chainable library for creating, calculating, and formatting monetary values (avoids floating point issues).
- [go-money](https://github.com/Rhymond/go-money) – Go implementation of Fowler's Money pattern for integer-based monetary amounts.
- [Joda Money](https://github.com/JodaOrg/joda-money) – Java library for representing, comparing, and calculating monetary amounts with a given currency.
- [Money](https://github.com/RubyMoney/money) – Ruby library for monetary values, formatting, and currency conversion without floating-point errors.
- [money](https://github.com/moneyphp/money) – PHP implementation of Fowler's Money pattern for precise monetary values and currency.

## Charts & Visualization
- [Perspective](https://github.com/perspective-dev/perspective) – Streaming analytics and data visualization component from FINOS, designed for large financial datasets.
- [Vizzu](https://github.com/vizzuhq/vizzu-lib) – Library for animated data visualizations and data storytelling (useful for financial dashboards).

## Billing & Subscriptions
- [Kill Bill](https://github.com/killbill/killbill) – Open source subscription management and billing platform with usage metering, invoicing, and real-time analytics.
- [Lago](https://github.com/getlago/lago) – Open source metering, usage-based billing, and subscription management API with pricing, analytics, and payment orchestration.
- [OpenMeter](https://github.com/openmeterio/openmeter) – Real-time usage metering and aggregation for usage-based billing of APIs and infrastructure.

## Payment UI Components
- [Card](https://github.com/jessepollak/card) – Minimal, beautiful credit card form component that works in a single line of code.
- [card-validator](https://github.com/braintree/card-validator) – Validate card numbers, expiration dates, and CVV as users type (from Braintree).
- [Payment](https://github.com/jessepollak/payment) – jQuery-free library for building, validating, and formatting credit card forms.
- [payment-webfont](https://github.com/orlandotm/payment-webfont) – SVG webfont of payment system and ecommerce icons for web applications.
- [PaymentFont](https://github.com/AlexanderPoellmann/PaymentFont) – Webfont containing icons for popular payment methods and card networks.

## Learning Resources
- [Fintech Engineering Handbook](https://w.pitula.me/fintech-engineering-handbook/) – Handbook of engineering patterns for building software that handles money and financial systems.

## Related Awesome Lists
- [Awesome Banking Tech](https://github.com/gtonic/awesome-banking-tech) – Curated list of bank engineering blogs, core systems, standards, and technology resources used in financial institutions.
- [Awesome Billing](https://github.com/kdeldycke/awesome-billing) – Knowledge base for billing and payments covering invoicing, pricing, accounting, marketplaces, and fraud.
- [Awesome Compliance](https://github.com/getprobo/awesome-compliance) – GRC resources for SOC 2, ISO 27001, SOX, PCI DSS, and related security and audit frameworks.
- [Awesome Financial Crime](https://github.com/SKR-35/Awesome-Financial-Crime) – Tools, datasets, and resources for AML, fraud, sanctions screening, KYC/KYB, and financial crime compliance.
- [Awesome PCI DSS](https://github.com/junhui/awesome-pci-dss) – PCI DSS standards, SAQs, implementation guidance, tooling, and training for protecting cardholder data.

---

Contributions welcome. Submit PRs for actively maintained, high-traction open source projects that provide clear value to fintech developers building real financial infrastructure. Projects should have meaningful commit history beyond initial creation and demonstrate usage outside the original authors. Keep entries alphabetized within each section, use one short sentence (10–30 words), and stay in existing categories. Trading, technical indicators, candlestick charts, quarterly reports, and market-analysis tools will be declined.

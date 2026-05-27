# Awesome Fintech

A curated collection of **popular, well-maintained open source libraries and developer tools** for fintech engineers. The focus is on production-grade projects with real-world traction used by banks, payment companies, and financial platforms.

Projects must demonstrate meaningful adoption (stars, forks, contributors, or industry usage), active maintenance, clear open source licensing (Apache, MIT, AGPL, BSD, etc.), and practical utility for building payments, banking, compliance, data, and financial systems. No weekend projects, AI-agent experiments, personal finance apps, or cryptocurrency/blockchain tools.

## Table of Contents
- [Payments & Integrations](#payments--integrations)
- [Banking Infrastructure](#banking-infrastructure)
- [Compliance & Sanctions](#compliance--sanctions)
- [Financial Data & APIs](#financial-data--apis)
- [Money, Currency & Formatting](#money-currency--formatting)
- [Charts & Visualization](#charts--visualization)
- [Billing & Subscriptions](#billing--subscriptions)
- [Payment UI Components](#payment-ui-components)

## Payments & Integrations
- [Hyperswitch](https://github.com/juspay/hyperswitch) – Open source, composable payments orchestration platform supporting 100+ processors with intelligent routing and PCI compliance options.
- [Hyperswitch Prism](https://github.com/juspay/hyperswitch-prism) – Stateless unified payment processing library with multi-language SDKs for integrating multiple processors.
- [Omnipay](https://github.com/thephpleague/omnipay) – Framework-agnostic, multi-gateway payment processing library for PHP.
- [PayPal Checkout Components](https://github.com/paypal/paypal-checkout-components) – Official JavaScript integration components for PayPal Buttons and Checkout experiences.
- [React Native Payments](https://github.com/naoufal/react-native-payments) – Cross-platform library for adding Apple Pay and Google Pay to React Native applications.
- [Gringotts](https://github.com/aviabird/gringotts) – Unified API for integrating dozens of payment gateways in Elixir/Phoenix applications.

## Banking Infrastructure
- [Apache Fineract](https://github.com/apache/fineract) – Apache project providing core banking functionality used by financial institutions serving the underbanked.
- [ACH](https://github.com/moov-io/ach) – Reader, writer, and validator for NACHA Automated Clearing House (ACH) files used for US electronic payments.
- [ISO 8583](https://github.com/moov-io/iso8583) – Go library for marshaling and unmarshaling ISO 8583 messages used in card and POS systems.
- [ISO 8583 Connection](https://github.com/moov-io/iso8583-connection) – Connection handling and request/reply matching for ISO 8583 in Go.
- [Wire](https://github.com/moov-io/wire) – Parser and writer for FedWire funds service files used for high-value US dollar transfers.
- [Fed](https://github.com/moov-io/fed) – Fuzzy lookup library for FedACH and FedWire ABA routing numbers and bank names.
- [Metro 2](https://github.com/moov-io/metro2) – Parser and generator for Metro 2 consumer credit reporting files used by credit bureaus.
- [JReactive-8583](https://github.com/kpavlov/jreactive-8583) – Netty-based ISO 8583 client and server for Java.
- [ISO-8583 Socket Queue](https://github.com/juks/iso-8583-socket-queue) – Node.js ISO 8583 gateway for banking and POS system communication.
- [Sequence](https://github.com/hoophq/sequence) – Immutable, scalable ledger service suitable for financial transaction recording.

## Compliance & Sanctions
- [OpenSanctions](https://github.com/opensanctions/opensanctions) – Open database and tools for sanctions lists, politically exposed persons (PEP), and persons of interest used in KYC/AML.
- [Watchman](https://github.com/moov-io/watchman) – Search across US trade sanctions lists (OFAC, etc.) for compliance screening.

## Financial Data & APIs
- [EDGAR Tools](https://github.com/dgunning/edgartools) – Python toolkit for SEC EDGAR filings: 13F holdings, 8-K events, fundamentals, and insider transactions.
- [FRED API](https://github.com/mortada/fredapi) – Python client for Federal Reserve Economic Data (FRED) and ALFRED macroeconomic series.
- [Finance Go](https://github.com/piquette/finance-go) – Go library for financial markets data including stocks, quotes, and fundamentals.
- [FundsXML](https://www.fundsxml.org/) – Open, royalty-free XML standard for fund data exchange and regulatory reporting across the European fund industry ([schema](https://github.com/fundsxml/schema)).
- [Indicator Go](https://github.com/cinar/indicator) – Go library of technical analysis indicators, strategies, and backtesting framework.
- [Indicator TS](https://github.com/cinar/indicatorts) – TypeScript port of technical analysis indicators, strategies, and backtesting.
- [TuShare](https://github.com/waditu/tushare) – Python utility for historical China equities market data (widely used in Asian quant workflows).

## Money, Currency & Formatting
- [Dinero.js](https://github.com/dinerojs/dinero.js) – Immutable, chainable library for creating, calculating, and formatting monetary values (avoids floating point issues).
- [accounting.js](https://github.com/openexchangerates/accounting.js) – Lightweight JavaScript library for number, money, and currency parsing/formatting (localizable, zero deps).
- [currency.js](https://github.com/scurker/currency.js) – Lightweight JavaScript library for precise currency value handling and arithmetic.
- [accounting](https://github.com/leekchan/accounting) – Money and currency formatting utilities for Go.

## Charts & Visualization
- [Lightweight Charts](https://github.com/tradingview/lightweight-charts) – High-performance, canvas-based interactive financial charts from TradingView (Apache 2.0).
- [Perspective](https://github.com/perspective-dev/perspective) – Streaming analytics and data visualization component from FINOS, designed for large financial datasets.
- [React Financial Charts](https://github.com/reactivemarkets/react-financial-charts) – React components for financial charts with indicators, overlays, and drawing tools.
- [Vizzu](https://github.com/vizzuhq/vizzu-lib) – Library for animated data visualizations and data storytelling (useful for financial dashboards).

## Billing & Subscriptions
- [Kill Bill](https://github.com/killbill/killbill) – Open source subscription management and billing platform with usage metering, invoicing, and real-time analytics.
- [Lago](https://github.com/getlago/lago) – Open source metering, usage-based billing, and subscription management API with pricing, analytics, and payment orchestration.

## Payment UI Components
- [Card](https://github.com/jessepollak/card) – Minimal, beautiful credit card form component that works in a single line of code.
- [Payment](https://github.com/jessepollak/payment) – jQuery-free library for building, validating, and formatting credit card forms.
- [PaymentFont](https://github.com/AlexanderPoellmann/PaymentFont) – Webfont containing icons for popular payment methods and card networks.
- [payment-webfont](https://github.com/orlandotm/payment-webfont) – SVG webfont of payment system and ecommerce icons for web applications.

---

Contributions welcome. Submit PRs for actively maintained, high-traction open source projects that provide clear value to fintech developers building real financial infrastructure. Projects should have meaningful commit history beyond initial creation and demonstrate usage outside the original authors.

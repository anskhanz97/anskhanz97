# Ans Khan

### Full Stack Developer | Laravel, PHP, Vue and MySQL

I build business applications from product requirements and operational workflows through backend, frontend, testing and delivery. My strongest work is in Laravel APIs, integrations, reliable data flows and interfaces that help people run their businesses.

At **XEPOS Ltd.**, I work across Retail, Hospitality, Loyalty and delivery operations, collaborating with C# desktop, Flutter/Dart mobile and web teams. My work connects Laravel APIs, client applications, MySQL data, background workers and external services. I also lead two personal products: **RentOps**, a rental operations SaaS, and **MyPoS**, a browser-based POS platform.

[Digital CV and case studies](https://anskhanz97.github.io/) · [Download CV](https://anskhanz97.github.io/Ans_Khan_Resume_Updated.pdf) · [LinkedIn](https://www.linkedin.com/in/anskhano/)

## Products I lead

### RentOps — rental business operations SaaS

A multi-tenant platform covering the rental lifecycle: pricing and availability, reservations and allocation, evidence-based handover and return, payments/deposits/refunds, and settlement. Operational modules include fleet documents, maintenance, damage claims, chauffeurs, vehicle-owner payouts, corporate billing and reporting.

I lead product direction and engineering, including Laravel/Vue architecture, tenant and branch permissions, guarded state transitions, shared interface components, public booking, communications and automation workspaces. A separate React Native field client supports evidence capture, offline queues, resumable uploads and conflict recovery.

**Status:** engineering implementation and local verification are documented; external production launch and mobile distribution qualification remain. Provider configuration or adapter support does not imply every provider has been activated live.

[Read the RentOps case study](https://anskhanz97.github.io/rentops.html)

### MyPoS — browser-based POS and operations

A multi-merchant/store product with barcode and weighted checkout, promotions, split tenders, returns/exchanges, inventory and expiry, purchasing, supplier balances, cash control, loyalty, attendance and operational payroll. Offline cash sales persist locally and reconcile with the authoritative backend.

I designed and implemented the product workflows, Laravel/Vue application, responsive light/dark interfaces and reporting workspace. Reporting includes **77 report definitions**, source drill-downs, saved filters, authorized CSV/XLSX/PDF exports, projections and incremental refresh.

**Measured evidence:** selected reports recorded p95 of **0.72–1.52 seconds** over one million synthetic sale lines in a documented local MySQL benchmark on 17 October 2026. Report-result cache was cleared per request; timings exclude network transport and do not establish production capacity.

**Status:** implemented and locally tested; live merchant, hardware and provider qualification remain.

[View MyPoS source](https://github.com/anskhanz97/MyPoS) · [Read the case study](https://anskhanz97.github.io/mypos.html)

## Professional contributions at XEPOS

- **Retail and Hospitality:** developed and enhanced frontend interfaces and Laravel workflows across till/cloud synchronization, operational administration, reporting, accounting and connected applications, working with web and C# desktop teams.
- **Loyalty platform:** independently designed and built a separate multi-tenant application for members, rewards, tiers, campaigns, QR interactions and balances, integrated with Retail/Hospitality till workflows for earn, redeem, refund and reversal.
- **Accounting integrations:** delivered Xero across Retail and Hospitality and contributed QuickBooks synchronization, including OAuth/token refresh, contacts/products/purchases, invoice/payment processing, taxes, discounts, partial/full refunds, voids and reconciliation.
- **Delivery Driver:** built the Laravel backend and Vue operations portal, tenant provisioning, Retail order ingestion, driver APIs, wallet and cash-custody records, offline reconciliation, proof of delivery, reporting and notification infrastructure. Flutter/C# clients are supported through API contracts and handoffs; real-device/provider verification is tracked separately.
- **Cross-functional delivery across stacks:** worked with C# desktop and Flutter/Dart mobile teams on REST contracts, authentication, driver/device registration, assignment events, offline queues, wallet reconciliation, receipts and end-to-end debugging. I build the backend and integration contracts; the Flutter team owns its client implementation.
- **Firebase and push notifications:** implemented FCM HTTP v1 dispatch with service-account authentication, Android priority and iOS/APNs payloads, encrypted device tokens, registration/revocation, token rotation support, notification outboxes, queued retries and scheduled recovery.
- **Notification observability:** implemented mobile-reported received/displayed/opened stages, replay protection, device readiness and p50/p95 receipt/dispatch metrics. Provider acceptance and device receipt are recorded separately; real-device latency qualification remains a separate activity.
- **Reliability and delivery:** transactions, locking, idempotency, queues, retries, structured application/API/integration logs, Forge workers, synchronization recovery, Postman collections and production troubleshooting across till, cloud and external systems.

Employer-owned code remains private. These descriptions identify my contributions without publishing company source or customer data.

**Live platforms:** [Retail](https://portal.xepos.net/) · [Hospitality](https://cloud.xepos.co.uk/) · [Loyalty](https://loyalty.xepos.co.uk/) · [Delivery Driver](https://driver.xepos.co.uk/)

## Client work and earlier experience

### Tasmiya Enterprises — website, CMS, CRM and integrations

Laravel/Blade business website with multi-division content, profile/service administration, reviews and responsive management interfaces. The CRM adds inquiry routing, ownership, follow-ups, conversion, case history and returning-inquiry/customer handling.

- **Google Drive API + Google Picker API:** Google OAuth with `drive.file` access, image selection, Drive v3 downloads/metadata checks, validated file import and configuration verification.
- **OneDrive + Microsoft Graph REST API:** MSAL sign-in, `Files.Read` access, authenticated folder/file browsing, pagination, image metadata/download retrieval and file validation. This implementation uses Microsoft Graph REST endpoints.
- **Google Places API:** fetch and present business ratings, reviews and attribution with provider failure handling.
- **Messaging and automation:** Meta WhatsApp inbound text and authorized replies, signed webhook/status handling, deduplication and delivery history; SMTP summaries, scheduled follow-up reminders and per-user in-app notifications.
- **Payments:** Stripe PaymentIntent creation/confirmation and staff-reviewed external-payment proof workflows. Provider configuration and actual production acceptance remain distinct.

[View Tasmiya source](https://github.com/anskhanz97/tasmiya-enterprises) · [Detailed case study](https://anskhanz97.github.io/tasmiya.html)

### Earlier roles and application maintenance

- **STechSole — Laravel Developer, Sep 2023–Feb 2026:** REST APIs, Vue/Blade interfaces, modular services, debugging and client application delivery.
- **iT Life — Backend Developer PHP Laravel, Mar–Aug 2023:** custom applications, responsive interfaces, releases, maintenance and live support.
- **Systems Limited — Cloud and Infrastructure Support Intern, Oct 2022–Feb 2023:** AX 2012, Dynamics 365, Azure/Power Platform exposure and technical query resolution.
- **Existing ERP applications:** maintenance and enhancements across accounting, sales, purchasing, stock and manufacturing workflows. This is maintenance experience, with ownership distinct from my personal products.
- Earlier application projects include HRMS, laundry operations, a B2B marketplace and parking management.

## Supporting engineering work

Independent MQL5 trading automation explores modular signal detection, order execution, lifecycle state, persistence, duplicate prevention and diagnostic logging. Selected repositories: [GoldEA](https://github.com/anskhanz97/GoldEA), [FvgEA](https://github.com/anskhanz97/FvgEA). These are engineering/research systems; no financial performance claim is made.

## Technical strengths

**Backend and data:** PHP, Laravel, REST APIs, Sanctum, MySQL, Eloquent, migrations, transactions, locking, tenant isolation

**Frontend and mobile:** Vue 3, React, React Native/Expo, TypeScript, JavaScript, HTML, CSS, Blade, Tailwind, Vite; Flutter API collaboration

**Business APIs:** Xero, QuickBooks, Stripe, Meta WhatsApp Cloud API, Twilio SMS, SMTP, OAuth 2.0, signed webhooks

**Cloud files and identity:** Google Drive API, Google Picker API, Google OAuth, Google Places API, OneDrive, Microsoft Graph REST API, MSAL

**Push and operations:** Firebase Cloud Messaging FCM, Apple Push Notification service APNs, queues, Redis/Horizon, Forge workers, schedulers, logs

**Engineering quality:** Git/GitHub, Postman, PHPUnit, Vitest, Playwright, static analysis, idempotency, transactions, locking, synchronization

I use AI tools for exploration, scaffolding, documentation and iteration, while retaining responsibility for implementation decisions, review, testing and delivery.

## Contact

Lahore, Pakistan · [anskhanz97@gmail.com](mailto:anskhanz97@gmail.com) · [LinkedIn](https://www.linkedin.com/in/anskhano/) · [Digital CV](https://anskhanz97.github.io/)

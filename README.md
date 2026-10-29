# Awesome-Customer-Messaging-Platform

# Top Customer Messaging Platform Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Live Chat, Shared Inboxes & Self-Hosted Customer Support*  
**Last updated: October 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Customer Messaging Platforms**. These tools enable merchants and support teams to engage customers in real time—via website chat, email, social messaging, and in-app channels—while centralizing conversations, automating responses, and measuring support performance.

**Examples** include Shopify Inbox, Gorgias, Intercom, Zendesk Chat, LiveChat, Tidio, Crisp, Drift, Freshchat, and Olark (the category leaders).

**Open-source emphasis**: Customer Messaging is a domain where open-source tooling is **viable for shared inboxes and help desk workflows**, but **lacks mature live-chat-first platforms** comparable to Intercom or Crisp's full widget experience. The strongest active project is **FreeScout**, a lightweight PHP/Laravel help desk and shared inbox explicitly positioned as a free Zendesk/Help Scout alternative, with omnichannel support (email, WhatsApp, Telegram, Facebook, Slack, Live Chat) and unlimited agents . **Crisp** itself maintains open-source SDKs and API wrappers for its chat widget across web, iOS, Android, React Native, and server-side languages—but the core platform is commercial . No open-source project matches the integrated live chat + bot + help desk + outbound messaging stack of Intercom or the Shopify-native commerce context of Shopify Inbox.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-products)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[Shopify Inbox](https://help.shopify.com/en/manual/inbox)**  
  Shopify's free native chat app; connects customers to staff or an opt-in **Inbox agent** that answers product, shipping, and policy questions using your catalog and knowledge base . Accessible via desktop, iOS, and Android apps; supports product links, discount codes, and cart insights .

- **[Gorgias](https://www.gorgias.com/)**  
  Helpdesk built for ecommerce (Shopify Premier Partner); unifies chat, email, and social into one inbox with deep Shopify integration for order edits, refunds, and customer context . Supports macro automation, intent/sentiment detection, and revenue attribution for support interactions .

- **[Intercom](https://www.intercom.com/)**  
  AI-first customer service platform with a customizable Messenger (spaces for messages, tickets, help, news, tasks) and **Outbound** for proactive onboarding, in-product messages, mobile push, and surveys . Positioned for product-led companies needing both reactive support and proactive engagement.

- **[Zendesk Chat](https://www.zendesk.com/)**  
  Live chat within Zendesk's suite with AI-powered bots, intelligent triage, and unified Agent Workspace across chat, voice, email, and messaging channels . Reporting includes bot performance metrics and workforce management insights.

- **[LiveChat](https://www.livechat.com/)**  
  Dedicated live chat platform with customizable widgets, automated and manual greetings, and reports (chat statistics, agent performance, staffing prediction) on higher tiers . Pricing from $19/agent/month (Starter) to $79/agent/month (Business) billed annually .

- **[Tidio](https://www.tidio.com/)**  
  Live chat and AI chatbots with a **free plan** (no credit card) and a 7-day premium trial . WordPress plugin supports widget visibility rules, scheduling, and multi-agent transfer; integrates with Facebook Messenger and 3,000+ apps via Zapier .

- **[Crisp](https://crisp.chat/)**  
  All-in-one customer support platform with chat widget, shared inbox, and bots; maintains **open-source SDKs** for web, iOS, Android, React Native, and API wrappers for Node, Go, PHP, and Ruby under MIT license .

- **[Drift](https://www.drift.com/)**  
  Conversational marketing platform focused on B2B lead capture and account-based marketing (ABM); provides playbooks, meeting booking, and contact management via API . Note: Drift has been transitioning to Salesloft's 1mind; verify current availability.

- **[Freshchat](https://www.freshworks.com/)**  
  AI-powered messaging software with bots, WhatsApp Business API integration, and omnichannel support (Facebook, Instagram, LINE, Google Business Messages) . Free tier available; paid plans add auto-assignment, CSAT, and advanced automations.

- **[Olark](https://www.olark.com/)**  
  Live chat platform with file upload, inline image display, transcript search/filter, and operator activity reports with historical averages . Integrations include JIRA Service Desk and MailChimp; widget size configurable via JavaScript API .

## Open-Source GitHub Projects

### Shared Inboxes & Help Desks

- **[FreeScout](https://github.com/freescout-help-desk/freescout)**  
  The strongest open-source **shared inbox and help desk** available (PHP/Laravel); explicitly built as a free Zendesk/Help Scout alternative . Features: **omnichannel** centralization (email, WhatsApp, Telegram, Facebook, Slack, Live Chat), unlimited agents and mailboxes, AI-powered assistance, mobile-friendly PWA with Web Push, 33 languages, screen reader support, web installer/updater, and one-click installs on PikaPods, Cloudron, and Softaculous . **The best starting point for organizations wanting a self-hosted shared inbox** with live chat as one channel among several.

### Chat SDKs & Widgets (Commercial Core)

- **[Crisp SDKs (web, iOS, Android, React Native, API wrappers)](https://github.com/crisp-im)**  
  Open-source (MIT) SDKs and API wrappers for **integrating Crisp's commercial chat platform** into applications . Repositories include `crisp-sdk-web` (React/Vue/Angular), `crisp-sdk-ios`, `crisp-sdk-android`, `crisp-sdk-react-native`, and API wrappers for Node, Go, PHP, and Ruby—all actively maintained (updated September–October 2026) . **Useful for developers building on Crisp**, but the core messaging platform is not open-source.

### Additional Strong Open-Source Options

- **No mature open-source live-chat-first platform exists** — FreeScout covers shared inbox and help desk with live chat as one channel , but no open-source project replicates the integrated live chat widget + bot builder + outbound messaging + product tours of Intercom or Crisp's full experience. Organizations requiring dedicated live chat with rich widget customization should evaluate commercial platforms.
- **Chatwoot** (not in search results but widely known) — Open-source customer engagement platform with live chat, email, and social channels; **verify current status and maintenance before adoption.**

**Frameworks for building custom systems**: For a **self-hosted shared inbox with live chat**, FreeScout provides the most complete foundation . For **embedding chat widgets into apps**, Crisp's MIT-licensed SDKs are production-ready —but require a Crisp account. No open-source project combines live chat, bot automation, and outbound messaging in a single turnkey platform; organizations needing Intercom-like capabilities should evaluate commercial options or assemble FreeScout with a separate chat widget.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Customer messaging platforms handling conversations and customer data must comply with applicable privacy regulations (GDPR, CCPA) and data retention policies; chat transcripts may contain personal information requiring secure storage and access controls.
- **Open-source customer messaging is strongest for shared inboxes**—FreeScout provides a production-ready help desk with omnichannel support , and Crisp's SDKs enable widget integration for its commercial platform . However, **no open-source project replicates the integrated live chat + bot + outbound stack** of Intercom, Gorgias, or Crisp's full experience. Merchants requiring dedicated live chat with rich commerce context should evaluate commercial platforms.
- Verify license terms for commercial use; FreeScout is open-source (check repository), and Crisp SDKs use MIT .

---

**Made for ecommerce merchants, support teams, and developers building customer engagement infrastructure.**  
Let's make customer messaging more open, but with clear eyes about the live-chat-first platform gap that commercial vendors fill.

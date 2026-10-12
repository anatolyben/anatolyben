# Hi, I'm Anatoly

I'm building **[ModerationOS](https://moderationos.com)**, an AI-powered platform for managing communities, conversations, and content across messaging and social platforms.

## Open Source

### [external-action-ledger](https://github.com/anatolyben/external-action-ledger)

An experimental JavaScript/TypeScript library for applications and workflow engines to record external actions, coordinate workers, and control retries with PostgreSQL storage. Failure simulations cover crashes, stale workers, and lost responses.

A lost response should not cause an external action to be blindly repeated.

### [telegram-bot-test-server](https://github.com/anatolyben/telegram-bot-test-server)

A local test server for the Telegram Bot API, for testing bots: members, restrictions, bans, join requests, invite links, buttons, multiple bots, channels, forum topics, polls, business chats, Telegram Login, a GramJS-style client for a user's own account (dialogs, history, folders) and updates by webhook or polling.

A bot should be testable without real accounts, real groups or real Telegram.

### [instagram-graph-test-server](https://github.com/anatolyben/instagram-graph-test-server)

A local test server for the Instagram Graph API (Instagram Login), for testing comment moderation, private replies, a professional account's inbox (conversations, history, reply windows), mentions and publishing (including carousels), with signed webhooks, token expiry, rate limits and Meta's error shapes.

An Instagram integration should be testable without real accounts, app review or Meta.

### [ibkr-tws-test-server](https://github.com/anatolyben/ibkr-tws-test-server)

A local test server for the Interactive Brokers TWS API, for testing trading programs across stocks, futures, FX, US Treasuries and indices: contract details, historical bars, live and delayed market data, accounts, margin and P&L, and the order lifecycle with brackets, OCA groups and what-if previews.

A trading program should be testable without an IB account, TWS or real orders.

### [whatsapp-cloud-test-server](https://github.com/anatolyben/whatsapp-cloud-test-server)

A local test server for the WhatsApp Business Platform Cloud API: text messages sent from business phone numbers, signed webhooks for incoming messages and delivery statuses, scoped access tokens, the 24-hour customer service window, and the failures Meta documents, including a send accepted after its response was lost.

A WhatsApp integration should be testable without a Meta app, a business account or real phone numbers.

### [stripe-test-server](https://github.com/anatolyben/stripe-test-server)

A local test server for Stripe Billing, driven by the official stripe SDK: customers, prices, Checkout, subscriptions and schedules, invoices, the customer portal and test clocks, with hosted pages a test can complete, time that renews, retries and cancels, and signed webhooks.

A billing integration should be testable without a Stripe account, network access or waiting for real time to pass.

## Gists

- [A lost response does not mean a failed action](https://gist.github.com/anatolyben/3330d4edc912d7b3e9c20f0759a7086c)
- [Lowercasing doesn't catch lookalike usernames](https://gist.github.com/anatolyben/f326542a92a47fea8db2d2f3419ff25c)

## Stack

TypeScript · Node.js · Python · PostgreSQL · Redis · Docker · React · Next.js


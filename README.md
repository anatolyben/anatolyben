# Hi, I'm Anatoly

I'm building **ModerationOS**, an AI-powered platform for managing communities, conversations, and content across messaging and social platforms.

## Open Source

### [action-boundary](https://github.com/anatolyben/action-boundary)

A small TypeScript library for putting an explicit authorization boundary between automated action proposals and real-world execution.

Models and automation can propose actions. They should not grant themselves permission to execute them.

### [redis-stream-consumer](https://github.com/anatolyben/redis-stream-consumer)

A small Node.js library for reading Redis Streams through a consumer group with at-least-once delivery, bounded retries, and a dead-letter stream written before the acknowledgement.

A message should only be acknowledged once it has been handled or safely set aside.

### [telegram-bot-test-server](https://github.com/anatolyben/telegram-bot-test-server)

A local, in-memory fake of the Telegram Bot API for testing bots: members, restrictions, bans, join requests, invite links, buttons, multiple bots, channels, forum topics, polls, business chats, Telegram Login and updates by webhook or polling.

A bot should be testable without real accounts, real groups or real Telegram.

### [instagram-graph-test-server](https://github.com/anatolyben/instagram-graph-test-server)

A local, in-memory fake of the Instagram Graph API (Instagram Login) for testing comment moderation, private replies, direct messages, mentions and publishing (including carousels), with signed webhooks, token expiry, rate limits and Meta's error shapes.

An Instagram integration should be testable without real accounts, app review or Meta.

## Stack

TypeScript · Node.js · Python · PostgreSQL · Redis · Docker · React · Next.js

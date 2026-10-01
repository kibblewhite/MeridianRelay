# MeridianRelay
Self-contained .NET notification hub. Polls RSS feeds and JSON APIs, detects changes by location and relays them to subscribers as authenticated webhooks. Durable SQLite queue, Polly retries with dead-lettering, SSO login and AES-GCM encrypted secrets. One Docker container, no external brokers or databases. Built for simplicity, not speed.

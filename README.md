# MeridianRelay
Self-contained .NET notification hub. Serves location-based change data as RSS feeds and JSON API endpoints, cached for 3 hours, and relays changes to subscribers as authenticated webhooks. Durable SQLite queue, Polly retries with dead-lettering, SSO login and AES-GCM encrypted secrets. One Docker container, no external brokers or databases.

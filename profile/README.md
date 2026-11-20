## Email reputation monitoring for teams that send email

HostRepute checks the domains and IP addresses you send from against 80+ DNS blocklists around the clock and alerts you the moment one is listed or removed. It also checks your email authentication records, TLS certificates, uptime and domain expiry, and reads what Gmail and Outlook.com report about your mail.

[Website](https://hostrepute.com) · [Free tools](https://hostrepute.com/tools) · [Documentation](https://docs.hostrepute.com) · [API reference](https://docs.hostrepute.com/api/) · [Pricing](https://hostrepute.com/pricing)

### What HostRepute watches

- **Blocklists.** Scheduled scans of every domain and IP, with a reputation score from 0 to 100 for each one and for the whole team.
- **Email authentication.** SPF, DMARC, MX, reverse DNS and the other records mailbox providers check before they trust your mail.
- **Certificates, uptime and domains.** TLS certificate expiry, trust and revocation over HTTPS, TLS or STARTTLS; HTTP(S) and TCP uptime checks; domain registration expiry from WHOIS.
- **Inbox providers.** Google Postmaster Tools and Microsoft SNDS data, synced daily.

When something changes, HostRepute alerts you by email, Slack, Telegram, Discord, PagerDuty, Pushover or webhook, and helps you respond: each blocklist's removal steps, manual scans, campaign preflight checks and an AI assistant that answers from your own monitoring data.

Need a one-off answer? The [free diagnostic tools](https://hostrepute.com/tools) and the [reputation check](https://hostrepute.com/check) work without an account.

### Build on HostRepute

A REST API with scoped team tokens, signed webhooks, an MCP server for AI clients and Prometheus metrics. Start with the [developer overview](https://docs.hostrepute.com/developers/overview/).

### Open source

| Project | What it is |
| --- | --- |
| [ReputeCast](https://github.com/HostRepute/ReputeCast) | Self-hosted newsletter platform that checks deliverability before you send. Works with Amazon SES, Postmark, Mailgun, SendGrid, Postal or any SMTP server. Every feature is free. Go, AGPL-3.0. |
| [ReputeCastDocs](https://github.com/HostRepute/ReputeCastDocs) | Source of [docs.reputecast.com](https://docs.reputecast.com), the ReputeCast documentation. Astro and Starlight. |

ReputeCast works with or without a HostRepute account. Connecting one adds 80+ blocklists, Google Postmaster Tools and Microsoft SNDS to its deliverability checks.

### Get started

Try HostRepute free for 14 days, no card needed. The [quickstart](https://docs.hostrepute.com/getting-started/quickstart/) walks you through monitoring your first domain.

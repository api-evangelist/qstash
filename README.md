# QStash (qstash)

QStash is a serverless message queue and task scheduling REST API from Upstash that delivers HTTP messages to endpoints reliably without requiring any long-lived connections or infrastructure management. Built entirely on stateless HTTP requests, it is designed for serverless and edge runtimes where traditional message brokers are impractical. QStash supports automatic retries, CRON-based scheduling up to one year in advance, URL group broadcasting for fan-out delivery, FIFO queuing, dead-letter queues, and message deduplication. Developers simply POST a message with a destination URL and QStash handles guaranteed delivery with configurable retry logic and flow control.

- **APIs.json**: https://raw.githubusercontent.com/api-evangelist/qstash/refs/heads/main/apis.yml
- **Naftiko**: https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=qstash-api-evangelist&utm_content=repo

## Tags

- Message Queue
- Task Scheduling
- Serverless
- HTTP Messaging
- Background Jobs
- Webhooks
- Dead Letter Queue
- CRON
- Upstash

## APIs

| Name | Base URL | Documentation |
|------|----------|---------------|
| QStash API | https://qstash.upstash.io/v2 | https://upstash.com/docs/qstash/overall/getstarted |

## Plans, Rate Limits, and FinOps

| Resource | File |
|----------|------|
| Plans & Pricing | [plans/qstash-plans-pricing.yml](plans/qstash-plans-pricing.yml) |
| Rate Limits | [rate-limits/qstash-rate-limits.yml](rate-limits/qstash-rate-limits.yml) |
| FinOps | [finops/qstash-finops.yml](finops/qstash-finops.yml) |

### Plan Summary

| Plan | Price | Messages/Day |
|------|-------|-------------|
| Free | $0/month | 1,000 |
| Pay As You Go | $1.00/100K messages | Unlimited |
| Fixed 1M | $180/month | 1,000,000 |
| Fixed 10M | $420/month | 10,000,000 |
| Enterprise | Custom | 100M+ |

## Timestamps

- **Created**: 2026-06-12
- **Modified**: 2026-06-12

## Common Links

| Type | URL |
|------|-----|
| Website | https://upstash.com/qstash |
| Documentation | https://upstash.com/docs/qstash/overall/getstarted |
| GitHub Org | https://github.com/upstash |
| LinkedIn | https://www.linkedin.com/company/upstash |
| Blog | https://upstash.com/blog |
| Pricing | https://upstash.com/pricing/qstash |
| Status Page | https://status.upstash.com/ |
| X (Twitter) | https://x.com/upstash |

## Maintainers

| Name | Email |
|------|-------|
| Kin Lane | kin@apievangelist.com |

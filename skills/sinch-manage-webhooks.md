---
name: sinch-manage-webhooks
description: Create, retrieve, update, list, and delete webhooks for a Sinch project.
api: openapi/sinch-webhooks-api-openapi.yml
operations:
- listWebhooks
- createWebhook
- getWebhook
- updateWebhook
- deleteWebhook
generated: '2026-10-03'
method: generated
generator: extract-docs-artifacts.py skills (local)
source: openapi/sinch-webhooks-api-openapi.yml ; every operationId checked against the contract
---

# sinch-manage-webhooks

Create, retrieve, update, list, and delete webhooks for a Sinch project.

## Steps

1. 1. Use `listWebhooks` to retrieve the collection of webhooks for the specified project and app.
2. 2. Use `createWebhook` to add a new webhook, providing the required request body fields.
3. 3. Use `getWebhook` to fetch details of a specific webhook by its `webhook_id`.
4. 4. Use `updateWebhook` to modify an existing webhook, supplying the `webhook_id` and the fields to change.
5. 5. Use `deleteWebhook` to remove a webhook identified by its `webhook_id`.

## Rules

- Authentication: Include a valid Bearer token in the `Authorization` header (BearerAuth).
- No idempotency key is required for these operations.
- Pagination is not applicable to these endpoints.

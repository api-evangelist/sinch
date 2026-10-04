---
name: sinch-create-and-retrieve-contact
description: Create a new contact and then retrieve its details.
api: openapi/sinch-contacts-api-openapi.yml
operations:
- createContact
- getContact
generated: '2026-10-03'
method: generated
generator: extract-docs-artifacts.py skills (local)
source: openapi/sinch-contacts-api-openapi.yml ; every operationId checked against the contract
---

# sinch-create-and-retrieve-contact

Create a new contact and then retrieve its details.

## Steps

1. 1. Use `createContact` with the required request body fields for a new contact and include an Authorization header (basicAuth, bearerAuth, or oAuth2).
2. 2. Use `getContact` with the `project_id` and the `contact_id` returned from the create step, and include the same Authorization header.

## Rules

- Authentication: Provide an Authorization header using one of the supported schemes (basicAuth, bearerAuth, oAuth2).
- Idempotency: The `createContact` operation is not idempotent; repeat calls will create duplicate contacts.

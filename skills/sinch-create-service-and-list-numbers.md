---
name: sinch-create-service-and-list-numbers
description: Create a new Fax Service in a project and then list the phone numbers assigned to that service.
api: openapi/sinch-projects-api-openapi.yml
operations:
- createService
- listServiceNumbers
generated: '2026-10-03'
method: generated
generator: extract-docs-artifacts.py skills (local)
source: openapi/sinch-projects-api-openapi.yml ; every operationId checked against the contract
---

# sinch-create-service-and-list-numbers

Create a new Fax Service in a project and then list the phone numbers assigned to that service.

## Steps

1. 1. Call `createService` with the required path parameter `project_id` and the request body fields defined for creating a Fax Service.
2. 2. Call `listServiceNumbers` with the path parameters `project_id` and `service_id` returned from the previous step.

## Rules

- Authentication: include a valid Bearer token in the `Authorization` header (bearerAuth) or use basicAuth as defined by the API.
- Idempotency: the `createService` operation is not idempotent; repeat calls will create duplicate services.
- Pagination: `listServiceNumbers` supports standard pagination query parameters (`page`, `pageSize`) as defined in the API contract.

# Public Client API

The public client talks to an auth and entitlement service through HTTP APIs.
The production service implementation, secrets, user data, and operations data
are not included in this public source repository.

Client-facing API groups:

- `POST /auth/register`
- `POST /auth/login`
- `POST /auth/refresh`
- `POST /auth/logout`
- `GET /entitlement`
- `POST /entitlement/device/bind`
- `POST /order/create`
- `GET /order/:id/status`
- `POST /order/:id/payment-proof`
- `GET /order/:id/payment-page`

The client treats server entitlement as the source of truth. UI state alone is
not a payment or authorization boundary.

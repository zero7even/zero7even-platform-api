# Zero7even Platform API

Private backend for the Zero7even Platform.

This repository will contain the core server-side platform services used by Zero7even, including account identity, authentication, Experiences, servers, economy, entitlements, administration, persistence, and internal platform integrations.

## Status

The active API is still being developed in the current Zero7even project workspace.

This repository is intentionally kept minimal until the current API implementation is completed and ready to be moved here.

## Planned responsibilities

- Accounts and authentication
- Zero7even usernames and identity
- Experiences and server registry
- Economy and wallets
- Entitlements
- Admin API and administration services
- MariaDB migrations
- Cache / Redis integration
- Moderation and audit systems
- Developer and server-facing platform APIs

## Security

Do not commit production secrets, passwords, API keys, OAuth secrets, database credentials, or private certificates to this repository.

Environment-specific configuration must remain outside source control.

## Related repository

`zero7even-services` contains the Luanti-facing SDK, service mods, bridge integration, shared contracts, and developer-facing platform integration layer.

---

Copyright © Zero7even.

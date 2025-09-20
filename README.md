# zt-ui-releases
Unofficial self-hosted UI for ZeroTier controllers (releases only). Not affiliated with ZeroTier, Inc.
# ZT UI (Unofficial)

Self-hosted dashboard for your own ZeroTier controller. Uses PostgreSQL.  
**Unofficial project — not affiliated with or endorsed by ZeroTier, Inc. “ZeroTier” is a trademark of ZeroTier, Inc.**

## Requirements
- PostgreSQL (DSN like `postgres://user:pass@host:5432/ztui`)
- ZeroTier controller + API token

## Quick start
1. Create DB & user in PostgreSQL.
2. Set env vars:
   - `DATABASE_URL` — your Postgres DSN
   - `ZT_CONTROLLER_URL` — e.g. `https://controller.example.com`
   - `ZT_API_TOKEN` — token with the rights you need
3. Start the app (first run auto-creates tables).

> Demo resets on each load (sandbox). Use at your own risk; PRs welcome.

## Donate
If this saves you time, you can buy me a coffee: <a href="https://donate.stripe.com/dRm14n0vI6ab8TD6tK9Ve00" rel="noopener">
  <Button className="rounded-2xl">Donate</Button>
</a>



# KAZI LINKER

Responsive installable web app (PWA) for the Qatar-to-Kenya money-management experience.

## App files
- `index.html` — responsive interface
- `manifest.json` — install metadata
- `sw.js` — app-shell offline caching
- `icon.svg` — custom emerald app icon

## Current release status
This is a front-end preview. It does not send money, create a wallet balance, quote a live exchange rate, or process M-Pesa payouts. Real transfers require a contracted licensed remittance/payment provider, server-side integration, and required compliance checks. Never put Supabase service-role keys or provider secrets in browser code.

## Supabase
The existing PesaLinker Supabase project is retained for KAZI LINKER. Its current public schema contains profiles, recipients, transfer_quotes, transfers, notifications, and audit_events. All listed tables have row-level security enabled. No schema or user data was changed in this initial front-end commit.

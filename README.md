# SHARP-casinha

Manual de uso da Casinha — espaço físico da Sharp em Pinheiros.

Site estático (`index.html`), sem build. Login restrito a e-mails `@sharpit.co` via Supabase Auth (Google OAuth).

## Stack

- HTML/CSS/JS puro, sem framework
- [Supabase](https://supabase.com/dashboard/project/eavluxeygfvyxkbzargs) — projeto `sharp-casinha`, usado só pra autenticação
- Deploy: Vercel, projeto `casinha-manual` (time `sharpit-co-projects`)

## Pendências

Ver o doc [Casinha — Pendências de infraestrutura](https://claude.ai/artifact/HkYjedzPT6cL2PnufNkqLd) — falta configurar o provedor Google no Supabase (Client ID/Secret do Google Cloud, restrito a `sharpit.co`).

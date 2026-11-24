# Huebel Bolt Observatory

## О проекте / токене

По описанию на официальном сайте, Huebel Bolt (BOLT) — мем-токен в сети TON и часть сообщества Huebel: сеть Telegram-каналов и чатов вокруг мемов и проектов TON. Сайт связывает экосистему с NFT-коллекцией Huebel (TON Furniture). Метаданные этого контракта называют BOLT официальным токеном Huebel Company.

Описание атрибутировано официальному сайту и метаданным. Рекламные заявления о первенстве, популярности и планах здесь не подтверждаются.

Источники (проверены 2026-11-24):

- <https://huebel.art/>
- <https://tonapi.io/v2/jettons/EQD0vdSA_NedR9uvbgN9EikRX-suesDxGeFg69XQMavfLqIw>

Generated from https://github.com/Freebielife/TON-Observatory-Template.

Run python3 -m scripts.refresh_observatory; python3 build.py; python3 verify.py.
Publish index.html in TON Sites only after independent on-chain verification.
Market data is collected from the configured token and swap-verified pools; see per-section freshness and completeness in the page.
Only native TON swap pairs supported. Locks, staking and custom project NFT badges are configured through project.json and verified against TonAPI.
GitHub Actions fallback schedule: 23 and 53 minutes past each hour (UTC); actual starts may be delayed. Shared Cloudflare registration has not been verified.

Foundation version: 1.3.0. Holders show 10, expandable to top 20.
`project.json` is the per-project specification. Contract/pool/precision changes require regenerating from the factory; do not reuse another token's snapshot.
Run `python3 build.py` for an atomic bundle and `build/report.json` size report.
No external fonts, scripts or images are needed to render the saved page. Fresh data checks and manual wallet lookups require network access.
Cloudflare dispatch registration and GitHub repository access remain separate deployment steps. No credentials go into HTML.

## BOLT configuration

- Contract: `EQD0vdSA_NedR9uvbgN9EikRX-suesDxGeFg69XQMavfLqIw` (9 decimals).
- Website: https://huebel.art/
- Project channel: https://t.me/daitebolt
- Community: https://t.me/boltlink
- Hero logo: https://huebel.art/images/fav-icon.png (official website fallback; metadata IPFS source unavailable at setup).
- Section flag: owner-selected TONecoFlags #165.
- Supported swap pairs: DeDust BOLT/TON and STON.fi BOLT/TON, verified via TonAPI successful swaps. Other pairs do not imply transaction coverage.
- TON Storage / RT publication is a separate step and has not been performed.

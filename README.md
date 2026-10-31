# productive-lab.com

Static site on GitHub Pages (`main`, repository root, custom domain in `CNAME`). No build step.

- `/` — Productive Lab hub.
- `/habit-streaks/policy/`, `/habit-streaks/terms/` — Habit Streaks legal pages (linked from the app and App Store Connect).
- Old Tilda URLs redirect, keeping their query:
  - `/habit-streaks/support/`, `/habit-streaks/feature-request/`, `/time-farm/support/`, `/time-farm/feature-request/`, `/support/` → [support.productive-lab.com](https://support.productive-lab.com/)
  - `/time-farm/policy/`, `/time-farm/terms/`, `/time-farm/` → [timefarm.productive-lab.com](https://timefarm.productive-lab.com/)
  - `/habit-streaks/` → App Store

DNS (GoDaddy): `@` A → 185.199.108.153, 185.199.109.153, 185.199.110.153, 185.199.111.153; `www` CNAME → `nikfanton.github.io`.

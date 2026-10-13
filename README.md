# Amongout – Factures

Single-file invoice/quote app (`index.html`).

## Put it on GitHub (so you can open it from anywhere)

1. Create a **public** repo, e.g. `amongout`. Upload `index.html` (and this README).
   Do NOT upload `amongout-data.json` (it holds client names / tax IDs).
2. Repo > Settings > Pages > Source: "Deploy from a branch" > `main` / `(root)`.
   Your app will be at `https://<your-user>.github.io/amongout/`.

## Keep your data synced (private)

1. Create a second repo, **private**, e.g. `amongout-data`. Upload `amongout-data.json` to it.
2. GitHub > Settings > Developer settings > Fine-grained tokens > Generate:
   - Repository access: only `amongout-data`
   - Permissions: Contents = Read and write
3. Open the app > "Synchronisation GitHub" > fill `your-user/amongout-data`,
   file `amongout-data.json`, paste the token > Connecter.
   Repeat on each device (phone, PC). Changes are pushed automatically.

The token is stored only in that browser, never in the data file.

# GRANTED HUB | VIP Gaming Store

A single-file web app for a VIP gaming store — accounts, orders, products, and an owner dashboard — all running in the browser with `localStorage`.

## 🚀 Deploy to GitHub Pages (fastest way)

1. **Fork or upload** this repo to your GitHub account
2. Go to **Settings → Pages**
3. Under *Source*, pick **Deploy from a branch**
4. Set branch to `main` and folder to `/ (root)`
5. Click **Save** — your site goes live at:
   ```
   https://<your-username>.github.io/<repo-name>/
   ```

## 📁 File structure

```
granted-hub/
├── index.html   ← entire app (self-contained)
└── README.md    ← this file
```

## 🔑 Owner login

| Field    | Value                     |
|----------|---------------------------|
| Email    | osje76hwhu72@gmail.com    |
| Password | *(set inside index.html)* |

> **Note:** Change the owner credentials inside `index.html` before going public.  
> Search for `OWNER_EMAIL`, `OWNER_USERNAME`, and `OWNER_PASSWORD` near the top of the file.

## 💾 How data is stored

All data (users, orders, products, notifications) lives in the visitor's browser `localStorage`.  
There is no backend — no database, no server needed.

## ✏️ Customization

| What to change | Where in `index.html` |
|---|---|
| Store name / branding | Search `GRANTED HUB` |
| Owner credentials | Search `OWNER_EMAIL` |
| Product listings | Search `sampleProducts` |
| Colors / fonts | Top of `<style>` block |

## 📜 License

MIT — use freely, modify as needed.

# QuickQuiz — Legal static pages (GitHub Pages)

Static pages for Google Play / App Store data-deletion and related declarations.
Pattern mirrors Gap Dash (`hosting/gapdash-privacy`).

## Files

| File | Use |
|------|-----|
| `data-deletion.html` | Play Console → Data safety → account / data deletion URL |

Privacy & Terms for the product already live at:

- https://quickquiz.net/privacy  
- https://quickquiz.net/terms  

## Deploy to GitHub Pages

1. Create a new GitHub repository (for example `quickquiz-legal`).
2. Copy **`data-deletion.html`** into the **root** of that repository (not inside a subfolder).
3. Commit and push to `main`.
4. On GitHub: **Settings → Pages**
   - **Source:** Deploy from a branch  
   - **Branch:** `main` / **Folder:** `/ (root)`  
   - Save  
5. Wait 1–2 minutes. Your URL will be:

```text
https://<username>.github.io/quickquiz-legal/data-deletion.html
```

## Before you publish

1. Open `data-deletion.html` and replace **`support@quickquiz.net`** with the real support inbox (same in both `mailto:` links).
2. Open the Pages URL in an **incognito** window — you must see this HTML immediately (no login wall, no empty SPA shell).

## Use in Google Play Console

**App content → Data safety:**

- “Add a link that users can use to request that their account and associated data is deleted”  
  → paste the Pages URL above.

**Partial data deletion without deleting the account:** choose **No** unless you later add that flow.

## Optional: custom domain

In GitHub Pages settings you can attach a custom domain (for example `legal.quickquiz.net`) and point DNS accordingly. Then use:

```text
https://legal.quickquiz.net/data-deletion.html
```

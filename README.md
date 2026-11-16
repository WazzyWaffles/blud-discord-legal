# BLUD Command Center — Privacy & Terms website

This folder is a ready-to-publish **static GitHub Pages website** for the BLUD Discord bot.

## BEFORE PUBLISHING

1. Replace **[ADD CONTACT EMAIL OR PUBLIC SUPPORT LINK]** in `privacy.html` and `terms.html` with a real email or accessible support URL.
2. Review both policies to ensure they match your actual hosting and bot setup. The policy reflects the November 2026 v1.0 bot code (SQLite, manual/CSV statistics, event registration); it does **not** claim automatic statistics sync or automatic deletion features.
3. Publish these HTML files only. Do not upload your `.env`, bot token, SQLite database, user records, or other secrets.

## Upload using GitHub Desktop (easy on Mac)

1. Install GitHub Desktop from https://desktop.github.com/ and sign into GitHub.
2. Unzip this package. In GitHub Desktop choose **File → Add Local Repository**, then select this folder. If the folder isn't a Git repository, choose **Create a repository here**.
3. Make an initial commit if requested, then click **Publish repository**. Name it `blud-discord-legal` and make it **Public** if using GitHub Free Pages.
4. Open the published repository on github.com, then **Settings → Pages → Build and deployment → Deploy from a branch**. Select **main** and **/(root)**, then save.
5. When published, URLs are:
   - `https://YOUR-USERNAME.github.io/blud-discord-legal/privacy.html`
   - `https://YOUR-USERNAME.github.io/blud-discord-legal/terms.html`
6. Open both URLs to confirm they load. Paste them into the Discord Developer Portal's application Privacy Policy URL and Terms of Service URL fields.

Official instructions: https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site

## Note

These are practical starter policies, not individualized legal advice. Update them if you add third-party data sync, analytics, payment features, or change retention practices.

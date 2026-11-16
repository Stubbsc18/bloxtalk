# BloxTalk — GitHub Pages website

## Upload
Upload **index.html**, **admin.html**, and **data.json** to the root of a public GitHub repository. In Settings → Pages, deploy from the `main` branch `/ (root)`.

## Content manager
Visit `https://YOUR-USERNAME.github.io/YOUR-REPO/admin.html` to edit hosts, production personnel (including Sl7shii), episodes, events, and announcements.

**Important:** This is NOT a secure, authenticated admin panel. It is a browser-based editor. Click **Download data.json**, then replace `data.json` in your GitHub repository and commit. GitHub Pages will publish the changes. Browser draft saves are local to that browser and do not update the public website. Anyone can visit admin.html, but they cannot publish to your GitHub repository without repository write permissions. Never store tokens or passwords in the site.

To make editing private, keep `admin.html` on your own computer rather than uploading it publicly (it can still import/export JSON files).

## Branding
The official BloxTalk logo is stored at `assets/bloxtalk-logo.png`. Upload the entire `assets` folder along with the HTML and JSON files. The website and admin panel use navy, purple, neon pink, and electric blue.

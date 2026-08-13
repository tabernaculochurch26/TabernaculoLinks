TABERNÁCULO CHURCH — V6 GITHUB LINKS EDITION

This version is designed so you can change button URLs from GitHub without
re-uploading the whole folder manually.

FILES
- index.html
- styles.css
- links.js        <-- EDIT THIS FILE FOR BUTTON LINKS
- logo.png
- background.webp

HOW TO CHANGE A LINK IN GITHUB
1. Open your repository.
2. Click links.js.
3. Click the pencil icon (Edit this file).
4. Change only the URL you want.
5. Click "Commit changes".
6. If the repository is connected to Cloudflare, Cloudflare redeploys automatically.

EXAMPLE

window.CHURCH_LINKS = {
  instagram: "https://www.instagram.com/tabernaculo_church3/",
  facebook: "https://www.facebook.com/YOUR_PAGE",
  youtube: "https://www.youtube.com/@YOUR_CHANNEL",
  pictime: "https://tabernaculochurch.pic-time.com/",
  giving: "https://YOUR-GIVING-LINK",
  visit: "https://YOUR-VISIT-LINK"
};

IMPORTANT
- Keep the quotes around each URL.
- Keep the commas between entries.
- "#" means the button has no destination yet.
- You do not need Astro, npm, or Wrangler for this version.

# Exceptional Butterfly Cleaning Company website

This is a static website. It uses plain HTML, CSS and JavaScript, so it does not need a framework, package installation or a build step.

## Files

- `index.html` - the website
- `logo.jpg` - the company profile image used as the logo
- `render.yaml` - Render Blueprint configuration for a static site
- `robots.txt` - allows search engines to crawl the public website

## Deploy on Render

1. Put all the files in this folder at the top level of a GitHub repository. Keep `render.yaml`, `index.html` and `logo.jpg` together.
2. In Render, choose **New +** and then **Blueprint**.
3. Connect the GitHub repository and approve access if asked.
4. Render reads `render.yaml`. Review the service named `exceptional-butterfly-cleaning` and choose **Apply**.
5. Wait for the first deploy to finish, then open the `onrender.com` link shown in the Render dashboard.

If you create a Static Site manually instead of using a Blueprint, connect the repository and use these settings:

- **Build command:** leave empty
- **Publish directory:** `.`

The website is static; it does not require environment variables or a server process. Render can redeploy it automatically when you push changes to the connected branch.

## Before sharing the live website

- Open the live URL on a phone and computer and test all navigation links.
- Submit a test quote and review. WhatsApp should open with the text prefilled; the visitor still has to press **Send** in WhatsApp.
- Add the live Render URL as the canonical URL and to a sitemap if you later add a custom domain or want stronger search-engine indexing. Google ranking is not guaranteed by deployment.
- Confirm the published service area and all company details are accurate.


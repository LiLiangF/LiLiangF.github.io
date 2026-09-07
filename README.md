# Personal Homepage

A dependency-free, responsive academic personal homepage designed for GitHub Pages.

## Customize

Edit `index.html` to replace `Your Name`, the bio, social URLs, work entries, and their destination links. The avatar deliberately starts as an empty dashed placeholder. When you have a photo, place it under `assets/` and replace the placeholder block with an image element (the inline comment marks the exact spot).

## Preview locally

Open `index.html` directly in a browser, or serve the folder with any static-file server.

## Deploy to GitHub Pages

1. Create a GitHub repository and push this folder's contents to its `main` branch.
2. In the repository, open **Settings → Pages** and choose **GitHub Actions** as the publishing source.
3. The included workflow at `.github/workflows/deploy.yml` runs after every push to `main` and deploys the site.
4. When the workflow finishes, use the URL shown under **Actions** or **Settings → Pages**.

For a repository called `personal-homepage`, the typical project URL is `https://YOUR-USERNAME.github.io/personal-homepage/`. If the repository is named `YOUR-USERNAME.github.io`, it is published at `https://YOUR-USERNAME.github.io/`.

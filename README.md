# KvK3 — King of All Britain (Thailand time)

Static HTML site for the KvK3 schedule. Schedule times are shown in Thailand time (UTC+7). `index.html` is the homepage. The original schedule pages and local image/CSS assets are included alongside it.

## Put this on GitHub

Create a repository and upload the **contents of this folder** to its top level, so `index.html` is at the repository root.

## Deploy with Cloudflare Pages

1. In Cloudflare, open **Workers & Pages → Create application → Pages → Import an existing Git repository** and select the GitHub repository.
2. Choose no framework preset.
3. Set the production branch to `main`.
4. Set the build command to `exit 0` and the build output directory to `.`.
5. Save and deploy.

The Pages output directory must contain the top-level `index.html`, all five schedule HTML pages, and the `resources/` folder. Cloudflare's static HTML instructions: https://developers.cloudflare.com/pages/framework-guides/deploy-anything/

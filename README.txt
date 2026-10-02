SR Tech Works Portfolio

Cloudflare Pages deployment structure:
- public/index.html  -> main website
- project-data/Project desc.txt -> project reference data

For Cloudflare Pages Direct Upload, upload the contents of the public folder,
or deploy the public folder with Wrangler:
  npx wrangler pages deploy public --project-name srtechworks

The existing Pages project name should remain: srtechworks
URL: srtechworks.pages.dev

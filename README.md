# Plaid Dash support website

Standalone HTML and CSS. No build step, JavaScript, package dependencies, login, server functions, or connection to a ChatGPT account.

## Ownership and hosting

- Source: https://github.com/yp27/plaid-dash-support (user-owned GitHub account yp27).
- GitHub Pages publishes the main branch root.
- Custom domain: support.wzkeji.cn, managed by the owner through Aliyun DNS.
- DNS: support CNAME yp27.github.io, default route, TTL 10 minutes.
- Keep the CNAME file in every deployment.
- The owner explicitly authorized my.yang.peng@icloud.com as the temporary public support email on September 8, 2026.

## Updating

Edit index.html and styles.css, commit, and push main. GitHub Pages publishes automatically. Verify the root page, #privacy section, styles.css, and HTTPS after updates.

Local preview: python3 -m http.server 8080 --directory release-site from the app repository.

Do not publish using the connected ChatGPT/Sites account. No iOS app source, private keys, credentials, or build artifacts belong in this public website repository.

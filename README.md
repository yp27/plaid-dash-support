# Plaid Dash support website

Standalone HTML and CSS. No build step, JavaScript, package dependencies, login, server functions, or connection to a ChatGPT account.

Deploy `index.html`, `styles.css`, and `favicon.svg` to a static host owned by the app developer. The root URL is the support page; append `#privacy` for the privacy policy. Confirm public access before filling App Store Connect URL fields.

Hosting account and domain are pending owner selection. Do not deploy using the connected ChatGPT/Sites account. The support email in the page is a draft until confirmed by the owner.

To preview locally: `python3 -m http.server 8080 --directory release-site` from the app repository.

The retired Sites scaffold is retained only as a local recovery copy under the ignored `artifacts/retired-sites-source/` directory. It is not the source for future deployment.

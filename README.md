# Hermes Personal

Public app information for Richard Löfberg’s personal Hermes integration.

## Publishing

GitHub Pages publishes the root of the `main` branch. `.nojekyll` keeps the
site as plain HTML and CSS; no build dependencies are required.

- Homepage: https://loefberg.github.io/hermes-personal/
- Privacy: https://loefberg.github.io/hermes-personal/privacy.html
- Terms: https://loefberg.github.io/hermes-personal/terms.html

Keep the Google OAuth consent screen and public pages consistent. If Google
requests Search Console ownership verification, add the supplied
`google-site-verification` meta tag to `index.html`, commit, and publish before
clicking Verify. Never add OAuth credentials, codes, tokens, or account data to
this repository.

The integration uses `gmail.readonly` and `calendar` scopes. Hermes runs on the
private Hestia server, and its setup commands are documented in that server’s
configuration repository.

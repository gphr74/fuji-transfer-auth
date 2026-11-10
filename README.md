# fuji-transfer-auth

The OAuth redirect page for Fuji Transfer's Lightroom sign-in. Adobe only redirects to https addresses, so
`callback.html` forwards the query string (`code`, `state`, or `error`) to `fujitransfer://auth`, where the
app's web sign-in sheet picks it up. Served by GitHub Pages at
https://gphr74.github.io/fuji-transfer-auth/callback.html.

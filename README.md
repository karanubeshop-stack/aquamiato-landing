 # aquamiato-landing

This repository hosts a static landing page for Aquamiato.

## Custom domain
A `CNAME` file has been added to connect the site to:

- `pg88game.net`

## GitHub Pages deployment
To publish the site:

1. Enable GitHub Pages in the repository settings.
2. Choose the `main` branch and select the root folder as the publishing source.
3. Confirm the custom domain is listed as `pg88game.net`.

## DNS settings
For the apex domain `pg88game.net`, add these A records at your registrar:

- `185.199.108.153`
- `185.199.109.153`
- `185.199.110.153`
- `185.199.111.153`

If you want `www.pg88game.net` to work as well, point it to `pg88game.net` with a CNAME record or to `karanubeshop-stack.github.io`.

# link.bitcoincharlotte.org redirect

Single-purpose GitHub Pages redirect for:

`https://link.bitcoincharlotte.org` → `https://linktr.ee/bitcoincharlotte`

## How it works

1. DNS: `link.bitcoincharlotte.org` CNAME → `BitcoinCharlotte.github.io`
2. GitHub Pages serves this repo with a real TLS certificate.
3. `index.html` and `404.html` redirect visitors to Linktree via JavaScript, with a meta-refresh fallback.

## Files

- `index.html` — redirect page for `/`
- `404.html` — redirect page for any path under the subdomain
- `CNAME` — custom-domain binding for GitHub Pages
- `.nojekyll` — skip Jekyll processing

## Target

Current redirect target: `https://linktr.ee/bitcoincharlotte`

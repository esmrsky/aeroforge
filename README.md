# aeroforge (redirect only)

This repo exists solely to keep `https://esmrsky.github.io/aeroforge/` alive after
the site moved to Cloudflare. GitHub Pages cannot issue a real 301, so this is a
meta-refresh plus a `location.replace` fallback, with a visible link if both are
blocked. It is `noindex` and declares a canonical pointing at the live site.

The actual project lives in the private repo **esmrsky/aeroforge-site**.

Delete this repo once the old URL is no longer in circulation.

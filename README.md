# Lickety-Sync — web

The browser client, published to GitHub Pages at **licketysync.dev**. This is a
separate domain and origin from the documentation site on purpose: a company
that blocks the client blocks only the client, and the client's keys and cache
live on an origin no documentation page shares.

The bundle here is built from the `app` repository's `ui` crate plus the core
compiled to WebAssembly; this repository holds the deploy, the service worker
and the signed manifest of the bundle's hashes that releases publish.

Arrives in phase 6. Until then `public/index.html` is a placeholder. MPL-2.0.

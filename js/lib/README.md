# Bundled runtime libraries

These files load locally with the xite. Keep the matching MIT license files when updating them.

| File | Source | SHA-256 |
| --- | --- | --- |
| `epixframe.min.js` | [https://github.com/EpixZone/epixframe/releases/download/v1.1.1/epixframe.min.js](https://github.com/EpixZone/epixframe/releases/download/v1.1.1/epixframe.min.js) | `040b1e5bf0198a56a71bc35ff8d37a77e65c8f2e4bc59eaf675ffe0700f2ba71` |
| `ethers.umd.min.js` | [https://cdnjs.cloudflare.com/ajax/libs/ethers/6.13.4/ethers.umd.min.js](https://cdnjs.cloudflare.com/ajax/libs/ethers/6.13.4/ethers.umd.min.js) | `fd66c04651929c6a37806a37e8217e6b6aac07c7e816ad478f52690b7429bc61` |
| `epixkit.js` | [https://github.com/EpixZone/epixkit/blob/5f966dbcbc507641bb6a79b660805525d803f262/epixkit.js](https://github.com/EpixZone/epixkit/blob/5f966dbcbc507641bb6a79b660805525d803f262/epixkit.js) | `cfa2fb3d1c3e269f81116bf1a5977da5b8e35f2c2bf2aa1b62fdb5d79799d657` |

EpixKit is copied from merged commit `5f966dbcbc507641bb6a79b660805525d803f262`. EpixFrame is the `epixframe.min.js` asset of the GitHub release `v1.1.1` (the same bytes as `dist/epixframe.min.js` at that tag). ethers preserves the bytes served by its pinned CDN URL on 2026-11-05.

After updating source files, use the normal authorized xite signing and publishing process so the signed file manifest includes these assets. Do not edit the existing signature by hand.

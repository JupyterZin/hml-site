# hml-site

Static explainer for **HML (Hybrid Memory Ledger)**: a hash-chained, append-only memory that several AI agents (Claude, Kimi, Gemini) share across sessions, with a server as the only writer and hasher.

**Live page:** https://jupyterzin.github.io/hml-site/

`index.html` is generated, not edited here. In the HML repo, `npm run site:export` embeds a snapshot of the real ledger, verified by the HML core at export time, and `npm run site:publish` uploads it here. The "Live" section shows that snapshot; the other demos run entirely in the browser (the chain demo computes real SHA-256 with Web Crypto).

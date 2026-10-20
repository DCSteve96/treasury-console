# Treasury console

Two static pages for a NEAR treasury policy contract. No build, no server, no secrets in this repository.

- `index.html`: read-only dashboard. Balance, caps, vendors and every payment decision, read from the NEAR RPC.
- `app.html`: the console. Drop a PDF invoice, have it read inside a NEAR AI Cloud enclave, check the signed receipt in the page, then ask the policy contract to pay. The API key and the agent's function-call key are entered in the page and stay in that browser's local storage.

Served with GitHub Pages from the root of this repository.

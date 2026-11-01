# Bursar, the site

The static pages of Bursar, served with GitHub Pages at https://bursar.network. No build, no server, no secrets in this repository: every page reads the NEAR chain over public RPC and signs in the browser.

- `index.html`: the landing page, with the last decisions read live from the demo contract.
- `login.html`: sign in with any NEAR wallet, an invite link, or a keys file.
- `console.html`: the console. Inbox, invoices read in a NEAR AI Cloud enclave, attention, vendors, orders, analytics, settings.
- `explorer.html`: every treasury on the network, read from the public registry and verified against each contract.
- `dashboard.html`: one company's public dashboard.
- `docs.html`: the documentation in one page. `privacy.html`: the privacy notice.
- `contracts/`: the policy contract build the console deploys for a new company, and the list of known builds.
- `samples/`, `brand/`, `vendor/`: sample invoices with recorded readings, the mark and logo, the bundled Meteor SDK.

The source of the whole project, contracts, agent, relay and these pages, is https://github.com/DCSteve96/Bursar. Bursar is software, not a payment service: funds stay in the company's own contract, with the company's keys.

# Hi, I'm Johan 👋

Founder of **[Pybara](https://pybara.com)** — non-custodial crypto payment infrastructure for e-commerce, built on the Internet Computer.

Ten years in full-stack web development. Now building production-grade decentralized applications through **[Yogabuild](https://yogabuild.eu)**, an Internet Computer development house based in Estonia.

**Currently:** onboarding early WooCommerce merchants ahead of full launch.

## What is Pybara?

Pybara lets e-commerce merchants accept crypto payments (ICP, ckBTC, ckETH, ckUSDC, ckUSDT) without Pybara ever holding customer funds. Payments move directly from buyer to merchant through `pybara-settle`, an open-source canister designed to be immutable and independently auditable.

- **Non-custodial by design** — funds never pass through a Pybara-controlled account
- **WooCommerce plugin** — crypto checkout that sits alongside existing payment methods
- **Pybara Wallet** — a lightweight, non-custodial wallet with cross-merchant order history in one place
- **Pybara Donate** — a standalone crypto donation widget for any WordPress site

## Open source

| Repo | What it is |
|---|---|
| `pybara-settle` | The payment-splitting canister. Open-sourced so anyone can verify the deployed code matches the source. |
| `pybara-docs` | Documentation for the wallet, plugin, and SDK. |

<!-- Replace the repo names above with proper [name](url) links once pinned — see note below on which org they need to sit under -->

Most of the platform — SDK, admin backend, wallet frontend, plugin — stays closed. `pybara-settle` is the part that actually touches funds, so that's the part built to be checked by anyone.

## Links

- [pybara.com](https://pybara.com) — product
- [docs.pybara.com](https://docs.pybara.com) — documentation
- [yogabuild.eu](https://yogabuild.eu) — development house

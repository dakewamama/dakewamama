# Ebele Asiadiachi

Software engineer working with Rust and TypeScript. I build payment applications, blockchain infrastructure, and tools for inspecting and controlling authority.

## Selected work

### [Velon](https://github.com/dakewamama/velon)

Reads supported permissions from Solana account state, explains who can act, and builds reviewed revoke transactions with verification afterward. The repository brings together the permission model, protocol adapters, runtime, and web console.

[Source and setup](https://github.com/dakewamama/velon#readme) · [Console](https://console.velonsecure.xyz/)

Live permission reads are supported. The full revoke flow currently runs on a local validator; public-network revocation remains disabled pending executor compatibility.

### [Hermit](https://github.com/dakewamama/hermit)

Moves scanned Zcash wallet state between devices in encrypted, signed capsules. The Rust kernel checks lineage, rollback, forks, and device authorization; the CLI handles wallet restoration and ZeWIF interchange.

[Source and setup](https://github.com/dakewamama/hermit#readme) · [Interactive demo](https://hermit-demo-orpin.vercel.app/)

Device migration has been exercised on testnet and regtest. Cross-application restoration depends on the receiving wallet's importer and may require a rescan.

### [Axis](https://github.com/dakewamama/axis)

An account and payment approval app for connected AI applications. The Next.js frontend handles wallet balances, saved recipients, recurring payments, permissions, and transaction approval using a PIN or passkey. Backend credentials stay on the server.

[Web app source](https://github.com/dakewamama/axis#readme) · [Wallet service](https://github.com/dakewamama/onboarding)

Payment execution depends on the configured backend services and provider credentials.

## Engineering interests

Authorization, transaction execution, payment reconciliation, wallet portability, and distributed state. My main tools are Rust, TypeScript, Node.js, Next.js, PostgreSQL, and Solana.

Each project's README documents its setup, verification steps, and current limits. This account also contains forks, experiments, and coursework; the projects above are the starting points for reviewing my work.

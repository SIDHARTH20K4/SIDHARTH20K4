# Hey, I'm Sidharth

Software engineer focused on Bitcoin and Lightning open source. Interested in Bitcoin protocol development, Lightning, wallets, P2P systems, and developer tooling.

[![Twitter](https://img.shields.io/badge/-@sidharth__2k04-000000?style=flat&logo=x&logoColor=white)](https://x.com/sidharth_2k04)
[![LinkedIn](https://img.shields.io/badge/-sidharth--blockchain--dev-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/sidharth-blockchain-dev/)
[![Email](https://img.shields.io/badge/-sidharth.120504@gmail.com-D14836?style=flat&logo=gmail&logoColor=white)](mailto:sidharth.120504@gmail.com)

## Bitcoin and Lightning

My main focus is contributing to Bitcoin and Lightning open source and building toward protocol-level development.

### BIP 451 / ddust

- Merged [ddust #46](https://github.com/bip451/ddust/pull/46), fixing multisig transaction validation for P2WSH and P2SH-P2WSH inputs. The validator was checking the empty `OP_0` witness item instead of the actual signatures when verifying the required sighash type.
- Merged [ddust #49](https://github.com/bip451/ddust/pull/49), adding integration coverage for P2SH 2-of-3, P2SH-P2WSH 2-of-2, and P2SH-P2WSH 2-of-3 multisig dust inputs.
- Merged [ddust #4](https://github.com/bip451/ddust/pull/4), adding a Justfile workflow around Bitcoin Core's `walletprocesspsbt` for signing dust-spending PSBTs. Tested on regtest by signing and broadcasting a transaction.

### Mostro

- Merged [Mostro #945](https://github.com/MostroP2P/mostro/pull/945), fixing a dispute workflow where solvers were not notified when buyers and sellers settled a dispute themselves.
- Added direct solver notifications and three tests, closing issue #918.
- Mostro has also given me practical experience working with Rust, Nostr, Lightning payments, and a real peer-to-peer Bitcoin application.

### BIP 451 / dusts

- Merged [dusts #2](https://github.com/bip451/dusts/pull/2), fixing a division-by-zero crash in Bitcoin dust analysis when a script type contained no victim UTXOs.
- The bug could appear only after processing a large UTXO dataset, causing the final statistics calculation to fail.

### Ride The Lightning

Contributing across the Angular frontend and Node.js backend of RTL, working primarily around LND and Eclair.

- Merged [RTL #1760](https://github.com/Ride-The-Lightning/RTL/pull/1760), fixing an assignment-vs-comparison bug that could misclassify Eclair relays as trampoline relays. Also enabled a lint rule and added the first Eclair store reducer test.
- Merged [RTL #1687](https://github.com/Ride-The-Lightning/RTL/pull/1687), fixing LND invoice and payment query validation so invalid parameters are caught before reaching the Lightning node.
- Merged [RTL #1609](https://github.com/Ride-The-Lightning/RTL/pull/1609), improving form accessibility for screen reader and keyboard users.

## What I'm learning

Currently going deeper into:

`Bitcoin Script` `UTXO Model` `PSBT` `SegWit` `Taproot` `Miniscript` `Multisig` `Sighash` `HTLCs` `Lightning Channels` `LND` `Core Lightning` `Nostr` `Fedimint`

Completed Bitshala Bitcoin Protocol Development cohorts with hands-on work around Bitcoin Core RPCs, wallet logic, raw P2P communication, regtest environments, transaction construction, and coinbase maturity.

Long term, I want to contribute to Bitcoin Core and major Bitcoin and Lightning protocols.

## Projects

- **[fairpass](https://fairpass.vercel.app)**: Privacy-focused event platform using zero-knowledge proofs and NFT-based tickets.
- **[vaultis](https://vaultiss.vercel.app)**: ERC-4626 tokenized yield vault with inflation-attack protection.
- **LigerGames**: Worked on smart contracts, security, and frontend wallet integrations.

## Other ecosystem work

I have also worked with Ethereum, Solana, and Sui, mainly around smart contracts and security.

- Selected for Rektoff's Solana security auditing program, 1 of 125 selected from more than 4,000 applicants.
- Audited Solana programs for ownership, account lifecycle, CPI, and lamport-handling vulnerabilities.
- Audited a Sui CLMM implementation and investigated a token-ordering issue through localnet testing and on-chain evidence.

## Stack

**Bitcoin:** Bitcoin Core, Bitcoin Script, PSBT, LND, Core Lightning, Nostr, Miniscript, Regtest

**Languages:** Rust, TypeScript, JavaScript, Python, Solidity

**Backend and tooling:** Node.js, Express, REST APIs, WebSockets, Linux, Docker, Git

**Web:** React, Next.js, Angular

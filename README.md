# Hey, I'm Sidharth 👋

Blockchain developer building across Bitcoin and Solana — final-year CS student chasing protocol-level work.

[![Twitter](https://img.shields.io/badge/-@sidharth__2k04-000000?style=flat&logo=x&logoColor=white)](https://x.com/sidharth_2k04)
[![LinkedIn](https://img.shields.io/badge/-sidharth--blockchain--dev-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/sidharth-blockchain-dev/)
[![Email](https://img.shields.io/badge/-sidharth.120504@gmail.com-D14836?style=flat&logo=gmail&logoColor=white)](mailto:sidharth.120504@gmail.com)

## Bitcoin
Long-term goal is Bitcoin protocol development. Other work is a bridge while building toward this.
- Merged [ddust #46](https://github.com/bip451/ddust/pull/46), fixing a witness-parsing bug where the sighash check always read the empty OP_0 item for P2WSH and P2SH-P2WSH multisig inputs, causing valid multisig transactions to fail validation.
- Merged [ddust #49](https://github.com/bip451/ddust/pull/49), adding integration tests for P2SH and P2SH-P2WSH multisig dust inputs.
- Started with the BOSS Month challenge, fixing a division-by-zero bug in `dusts` and filing several follow-up improvement issues on `ddust`.
- Merged [RTL #1609](https://github.com/Ride-The-Lightning/RTL/pull/1609), fixing an accessibility issue where multiple form fields lacked visible labels for screen readers.
- Completed Bitshala's Bitcoin Protocol Development cohorts: RPC clients, wallet logic, raw P2P protocol implementation, regtest environment setup, coinbase maturity mechanics.
## Solana
- Selected for Rektoff's Solana security auditing program, 1 of 125 from over 4,000 applicants, run in partnership with the Solana Foundation.
- Audited a Solana lending program's `close_user_deposit` function and found multiple vulnerabilities, including a missing ownership check, an account reinitialization risk, and redundant lamport transfer logic.
- Studied CPI mechanics in depth, including the Confused Deputy attack pattern.
- Audited FlowX CLMM contracts on Sui as part of a bug bounty program, proving an orientation asymmetry bug where non-canonical token ordering caused pool prices to initialize up to 100x wrong. Set up a localnet environment and produced on-chain evidence for the submission.
## Products and experience
- **[fairpass](https://fairpass.vercel.app)**: ZK-enabled event management dApp using Next.js, Semaphore.js, wagmi, and viem, deployed on Sonic testnet.
- **[vaultis](https://vaultiss.vercel.app)**: ERC-4626 tokenized yield vault with inflation-attack protection via OpenZeppelin's decimals offset defense.
- **LigerGames**: Blockchain game developer. Smart contracts, auditing, frontend wallet integrations with ethers.js, wagmi, and viem.
- Freelance client work, including a booking system rebuild for a bowling arcade business.
## Stack
Solidity, Rust (Anchor), Ethereum, Solana, Foundry, Hardhat, Anchor, wagmi, viem, React, Next.js, TypeScript, Python

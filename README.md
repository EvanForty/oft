# OFT — The Omnichain Fungible Token Launchpad

Launch a coin. Go omnichain.

Static site: plain HTML, CSS and JavaScript. No build step.

## Deploy on Vercel
1. Push these files to the root of a GitHub repo.
2. In Vercel, choose **Add New → Project** and import the repo.
3. Framework preset: **Other**. Leave the build command and output directory empty.
4. Deploy.

## Wallet
Solana wallets (Phantom, Solflare, Backpack) connect through `@solana/web3.js` 1.95.3 from jsDelivr. EVM wallets (MetaMask and others) connect through the browser wallet directly.
For a reliable SOL balance, replace `W3.clusterApiUrl('mainnet-beta')` in `index.html` with your own RPC URL.

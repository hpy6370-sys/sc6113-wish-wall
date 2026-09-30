# Wish Wall · SC6113 DApp

A mobile-friendly DApp: connect a wallet (MetaMask), view address / network / balance, switch to the Sepolia testnet, and sign a wish with your private key. Every signed wish is verified on the page with `ethers.verifyMessage`, proving it came from that address.

- Single static page: `index.html` (ethers.js v6 via CDN)
- On a phone, open the link inside the MetaMask in-app browser

## Deploy on Render

New → Static Site → connect this repo → Build Command: (empty) → Publish Directory: `.`

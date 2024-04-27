# How to integrated with Tron blockchain

## Deploying contract on tron Shasta testnet

- Create `.env` file with the corresponding private keys configuration (check [tronbox.js](tronbox.js) to learn more)
- Run `npx tronbox compile`
- Run `npx tronbox migrate --network Shasta` (add `--reset` param to redeploy)
- Run tests (`npx tronbox test`)

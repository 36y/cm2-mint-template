## Getting started

### Rename the .env.example file to .env and populate the following environment variables:

Required:

```
VITE_APP_CANDY_MACHINE_ID=
VITE_APP_SOLANA_NETWORK=
VITE_APP_SOLANA_RPC_HOST=
```

Optional:
Populate with your Google Analytics Measurement ID (in the format G-XXXXXXXXXX)

```
VITE_APP_GOOGLE_ANALYTICS=
```

### Example configuration
Devnet:
```
VITE_APP_SOLANA_NETWORK=devnet
VITE_APP_SOLANA_RPC_HOST=https://explorer-api.devnet.solana.com
```

Mainnet-beta:
```
VITE_APP_SOLANA_NETWORK=mainnet-beta
VITE_APP_SOLANA_RPC_HOST=https://api.mainnet-beta.solana.com
```

### Edit the following variables in App.svelte to match your project:

```
- TITLE
- DESCRIPTION
- IMAGE_LINK
- HEADER_TITLE
- HEADER_LINK
```

### Then run:

```
yarn install
yarn dev
```

## Features

- Automatically fetches items minted, total quantity and price from the candy machine state
- Whitelist token detection and whitelist price updates
- 'View on Solana Explorer' after transaction has been broadcasted
- Confetti after a successful mint
- Google Analytics tracking


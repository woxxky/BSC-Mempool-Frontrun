
# BSC/EVM Mempool Frontrun Bot

A mempool monitoring and frontrunning bot targeting EVM-compatible networks, including Binance Smart Chain (BSC), Ethereum (ETH), Avalanche (AVAX), Polygon (MATIC), Fantom (FTM), Cronos (CRO), Harmony (ONE), Milkomeda (MilkADA), Moonforce, and Pinksale.

This project is provided for research and educational purposes only. Use responsibly and in accordance with applicable laws and platform terms.

## Features

- Multi-chain EVM support
- Mempool transaction decoding (via `abi-decoder`)
- Web3-based interaction with nodes (`web3`)
- Configurable runtime parameters (see `src/env.js` and `src/constants.js`)

## Requirements

- Node.js and npm (LTS recommended)
- Windows users: Visual Studio C++ Build Tools (only if native modules are required)

## Getting Started

1. Install dependencies:
   - Navigate to the `src` directory and install packages.
   
   ```bash
   cd src
   npm install
   ```

2. Configure environment:
   - Update `src/env.js` with your RPC endpoints and credentials (e.g., private key).
   - Adjust `src/constants.js` for chain IDs, contract addresses, gas settings, and other operational parameters.

3. Run the bot:

   ```bash
   node frontrun.js
   ```

## Configuration

- `src/env.js`: Sensitive runtime values such as RPC URLs and private keys. Keep this file secure and never commit secrets.
- `src/constants.js`: Network and application constants (e.g., router addresses, WETH/WBNB addresses, gas multipliers).

## Contact

| Platform | Link |
|----------|------|
| 📱 Telegram | [t.me/novustch](https://t.me/novustch) |
| 📲 WhatsApp | [wa.me/14105015750](https://wa.me/14105015750) |
| 💬 Discord | [discordapp.com/users/985432160498491473](https://discordapp.com/users/985432160498491473)

<div align="center">
    <a href="https://t.me/novustch" target="_blank"><img alt="Telegram"
        src="https://img.shields.io/badge/Telegram-26A5E4?style=for-the-badge&logo=telegram&logoColor=white"/></a>
    <a href="https://wa.me/14105015750" target="_blank"><img alt="WhatsApp"
        src="https://img.shields.io/badge/WhatsApp-25D366?style=for-the-badge&logo=whatsapp&logoColor=white"/></a>
    <a href="https://discordapp.com/users/985432160498491473" target="_blank"><img alt="Discord"
        src="https://img.shields.io/badge/Discord-7289DA?style=for-the-badge&logo=discord&logoColor=white"/></a>
</div>

Feel free to reach out for implementation assistance or integration support.

## Security Notes

- Never commit private keys or credentials.
- Prefer environment variables or a secrets manager in production.
- Use dedicated wallets and risk controls when operating on mainnet.

## Legal Disclaimer

This software is provided “as is,” without warranty of any kind. You are solely responsible for compliance with laws, exchange/DEX terms, and all risks (including financial loss) arising from use of this software.

## Binaries

Precompiled binaries are not provided in this repository. Build and run from source as described above.

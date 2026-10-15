# Bind-App-o-NordLynx
Basically, a better version of split tunneling for Nord. Why not just use split tunneling? It was leaking traffic when 'paused'. Setting kill switch, makes all traffic wait for nord to connect even when split tunneling is on and the app is allowed outside of the tunnel it still waits and causes NAT issues in games, anti cheat blockage etc.... This is a windows firewall rule creator that blocks network traffic to the app if NordLynx is paused.
Limitations: Only setup to work with NordLynx
#How to run the script
Go to the scripts directory, open a powershell type
powershell.exe -ExecutionPolicy Bypass -File ".\BindAppToNord.ps1"

<!-- chaython-funding:start -->
## Support development

[GitHub Sponsors](https://github.com/sponsors/Chaython) · [Patreon](https://patreon.com/Chaython) · [Buy Me a Coffee](https://buymeacoffee.com/chaython) · [PayPal](https://paypal.me/ChaythonM)

Crypto donations:

- ETH (Ethereum): `0x201B6E0B0282BBAE1592C24f9CbD39009A70F7d7`
- BTC (Bitcoin): `32o7JmXgFcs4R1SbcLLVKQCRw9KHkhneJi`
- SOL (Solana): `BDicyUL9zizDeYBLw8oBwotv6jtHotLLQD7Bcqg2atLk`
- **USDC (Base network):** `0xBeD35dcAd9F1A32459B3C0DF004371EBE939E760`

**Send USDC only on Base.**
<!-- chaython-funding:end -->

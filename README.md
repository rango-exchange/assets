
# Rango Assets

Rango Exchange Assets is a repository that provides static assets for all supported blockchains, protocols, and swappers, along with useful resources such as the Rango Exchange brand book.

---

## New Asset Addition Checklist

### Blockchain
1. Create a directory in the `blockchains` folder, named after the blockchain's unique ID in Rango (e.g., `AKASH`, `ETH`, `BSC`, `TON`, `BTC`, etc.). You can verify the blockchain name through the meta endpoint.
2. Add the blockchain icon to this directory and name it `icon.svg`. Icons must be _200x200 px_ **rounded** SVG images with _no margins, padding, or background_. Ensure the file size is below 10KB.

### Swappers
1. In the `swappers` folder, create a directory named after the swapper group in Rango (e.g., `ParaSwap`, `Pancake`, `UniSwap`, etc.). You can confirm the swapper group by checking the meta endpoint.
2. Place the swapper icon in this directory and name it `icon.svg`. Icons should be SVG images (or PNG if SVG is unavailable) with dimensions of _200x200 px_, with _no margins, padding, or background_. Ensure the file size is below 30KB.

### Wallets
1. In the `wallets` folder, create a directory named after the lowercase wallet name (e.g., `metamask`, `walletconnect`, `solflare-snap`, `okx`, etc.).
2. Place the wallet icon in this directory and name it `icon.svg`. Icons must be SVG images with no margins, padding, or background. Ensure the file size is below 50KB.

# Customizable Edition Drop Minting Page

In this template, we build a page where users can claim NFTs from the [Edition Drop](https://docs.web3sdks.com/pre-built-contracts/edition-drop) contract.

## Tools

- [**Edition Drop**](https://docs.web3sdks.com/pre-built-contracts/edition-drop): Create a collection of ERC-1155 NFTs and release them to users under [claim conditions](https://docs.web3sdks.com/pre-built-contracts/edition-drop#minting--claiming-nfts).
- [**React SDK**](https://docs.web3sdks.com/react): to enable users to connect their wallets with the [useMetamask](https://docs.web3sdks.com/react/react.usemetamask) hook, and access hooks such as [useNFTDrop](https://docs.web3sdks.com/react/react.usenftdrop) to interact with the NFT drop contract.
- [**TypeScript SDK**](https://docs.web3sdks.com/typescript): to view the claimed supply, total supply, and mint NFTs from the drop.

## Using This Repo

To create your own version of this template, you can use the following steps:

Run this command from the terminal to clone this project:

```bash
npx web3sdks create --template edition-drop
```

### 1. Deploy Your Own Edition Drop on web3sdks

Head to the [dashboard](https://web3sdks.com/dashboard) and create your own **Edition Drop** contract.

You can learn how to do that with our guide [Release an NFT drop on your own site without writing any code](https://docs.web3sdks.com/guides/release-an-nft-drop-with-no-code#create-a-drop-contract).

Be sure to configure a **name**, **description**, and **image** for your NFT drop in the dashboard.

### 2. Configure the styles to your branding

You can fully customize the colors and style of this template by editing the values in the [`globals.css`](/styles/globals.css) file.

You can configure:

- The color of the background with `--background-color`
- The color of the text with `--text-color`
- The color of the button (is a gradient from primary to secondary color) with `--color-primary` and `--color-secondary`
- The font with `--font`
- The border colors with `--border-color`

### 3. Plug in your Edition Drop contract address

Replace the value of the `myEditionDropContractAddress` inside [`index.tsx`](/pages/index.tsx) with your Edition Drop contract address (you can find in the dashboard).

---

## Join our Discord!

For any questions, suggestions, join our Discord at [https://discord.gg/KX2tsh9A](https://discord.gg/KX2tsh9A).

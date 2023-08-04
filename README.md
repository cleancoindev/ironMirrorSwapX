# ironMirrorSwapX
### _**Create trustless limit orders across EVM chains**_

Hey this ironMirrorSwapX. We have created an automation module for any account abstraction or EOA wallet to be able to create limit orders or any scheduled DeFi strategy from any token on any source chain to another token on any destination chain across EVM.

## Key Features
**1. Trustless** - ironMirrorSwapX is a smart contract module, meaning it is completely decentralized, composable and operates on a trustless system.

**2. Cross-chain** - ironMirrorSwapX can be deployed on any EVM compatible chain, making it possible for users to trade across multiple chains.

**3. Automation** - ironMirrorSwapX leverages Gelato Network to automate the execution of limit orders. This means that once a user creates a limit order, they no longer need to actively monitor the market to execute the trade.

**4. Composable** - ironMirrorSwapX can be easily integrated into other DeFi protocols, enabling composability and allowing developers to create more complex trading strategies.

## How it Works
ironMirrorSwapX leverages Gelato Network to create a task with call data as per the limit order specified by the user. The task is then executed using Connext, Uniswap v3, Honeyswap, or other AMMs as per the token pair, and fetching token prices from UMA protocol oracles.

When a user creates a limit order, they specify the token pair they want to trade, the price they want to buy or sell at, and the amount of tokens they want to trade. The limit order is then added to the ironMirrorSwapX order book.

When the price of the token pair reaches the user's specified price, the Gelato Network executes the trade automatically. The user's tokens are then swapped for the desired tokens at the specified price.

You can find our old origination project contract deployments on - 
* Mainnets
  * <a href="https://polygonscan.com/address/0xc082906f6744b3438c9ef78c738b225af8e17021#tokentxns" target="_blank">Polygon Chain</a>
  * <a href="https://gnosisscan.io/address/0xaa3E5FA2DcB475752AC1fbE86769201A1e30b29B" target="_blank">Gnosis Chain</a>
* Testnets
  * <a href="https://goerli.etherscan.io/address/0xd55cb9fa29c5E66B2681dfbA56e3bcAae15571ed" target="_blank">Goerli Testnet</a>
  * <a href="https://alfajores.celoscan.io/address/0x363109864e7505b9d81ba5aca261fa3824a3540f" target="_blank">Celo</a>
  * <a href="https://explorer.testnet.mantle.xyz/tx/0xfb8c6d3d85314b5ac8e57ea9d33d2d7403bf7edb8cd90806782d8987ac57c87c" target="_blank">Mantle zK</a>
  * <a href="https://explorer.goerli.linea.build/address/0x0062623038c3A46765b359Cc6621C4b8BD7fca5c" target="_blank">Linea</a>
  * <a href="https://blockscout.scroll.io/tx/0xe0d0f13ef99af60c35aafa309b843ad94ca3c4d1a91c3474a5d2364152a0736e" target="_blank">Scroll zK</a>
 
 Future ones will be listed later.

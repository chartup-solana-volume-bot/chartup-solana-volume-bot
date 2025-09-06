---
icon: plus
cover: ../../.gitbook/assets/Group 1547765196 (2).png
coverY: 0
---

# Create Liquidity Pool (LP)

### Pool Types

ChartUp uses the **Raydium CPMM (Constant Product Market Maker)** model to create your token's liquidity pool, with **SOL as the base pair**. This ensures your token is tradable immediately after deployment on a decentralized exchange.

#### Required Information

To deploy a liquidity pool, the following information is needed:

* **Wallet**:\
  Select the wallet that will be used to deploy the liquidity pool.\
  In most cases, this will be the same wallet used during the token minting process.

> 💡 **Note**: The selected wallet must hold both the token and enough SOL to seed the pool. Make sure it contains a sufficient token balance.

* **Supply Amount**:\
  Define how much of your total token supply you'd like to allocate to the liquidity pool.\
  This is fully up to you—there are no restrictions.

> 💡 **Note**: Any remaining supply not added to the pool can be used for **volume boosting** or other strategies after the pool is live.

* **SOL Amount**:\
  Specify how much SOL to pair with your tokens.\
  The ratio between tokens and SOL determines your token's **initial market cap and price**.

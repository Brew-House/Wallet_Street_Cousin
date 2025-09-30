# $WSC Wallets

For full transparency, below are all official Wallet Street Cousin ($WSC) wallets, including the contract deployer, treasury, liquidity, and team holdings.

Every wallet serves a defined purpose, and all token movements are trackable on-chain.

---

## 🧱 Deployer Wallet (Contract Creator)

**Purpose:**  
Deployed the $WSC contract and minted the full 8.23B supply.

**Actions:**  
- Minted total supply.  
- Immediately transferred tokens to the Treasury and Liquidity wallets.  

**Address:**  
`0x89cdc8542790b9814566d2523dba31bc5d1e5a7f`

**Status:**  
Deployment-only wallet. No further use planned.

### Deployment Notes — update 6/9/25
- Original deployment wallet used to launch $WSC contract.  
- Performed **two test transactions** to confirm deployment on live pair.  
- No further use planned.  
- Remaining gas in this wallet will be used to replicate test transactions (see `LP_Test_Transactions.md`) on future pairs.
- ### Deployment Notes — update 30/9/25
- Deployer Wallet is to be used as LynchPin wallet.
- To date it has been the Listing address to Label All Wallet Street Wallets on Routescan
- Deployed 'Wallet Street Waver' (0xC5749424103Aae8C16ac230329bC642EfCf083D2) to facilitate airdrop
- Any future NFT's will be minted from this address and transfered to treasury wallet for storage or distribution

---

## 💧 Liquidity Wallet

**Purpose:**  
Used exclusively for seeding and growing the WSC/FLR liquidity pool(s).

**Allocation:**  
55% of total supply, deployed in phases:  
- 12.5% initial  
- 12.5% Phase 2  
- 6 × 5% as community scales  

**Address:**  
`0x89cdc8542790b9814566d2523dba31bc5d1e5a7f`

**Notes:**  
All LP deployments will be announced ahead of time and traceable via this address.

---

## ❄️ Liquidity_Cold Wallet

**Purpose:**  
Holds the full allocation of $WSC designated for liquidity, but is **not connected directly to DEXs**.  
Functions as a cold reserve wallet to securely store tokens prior to tranche releases.

**Usage:**  
- Acts as the source of truth for the 55% LP allocation.  
- Funds are moved from this wallet into the **Liquidity Wallet** when a tranche is deployed.  
- Adds an extra layer of security by separating storage from execution.  

**Address:**  
`0x8778b9e2C6905F4bFEaB6924aa37Ba29E88b526F`

**Notes:**  
This wallet will not interact with trading pairs directly.  
Any gas remaining here may be used for test or verification transactions, but all public LP seeding will route through the **Liquidity Wallet** listed above.  

---

## 📥 Treasury Wallet

**Purpose:**  
Holds the 35% reserve for marketing, ecosystem initiatives, CEX listings, and community incentives.

**Address:**  
`0x5D5252E377dc3AAC3FEB0C5858Ea7E425534f4aF`

**Usage Examples:**  
- Meme contests    
- Development of tools, bots, or content
- Update 30/9/25
- Future FTSO infrastructure
- Founder pledges 50 000 FLR and 10 000 FLR loan to Stake and Delegate from this wallet - to be returned at end of Vesting Period with rewards remaining in wallet and not legible for rolling escrow.

---

## 🔐 Founder & Team Wallet(s)

**Purpose:**  
Holds 10% allocation reserved for founding team and contributors.
2.5% Pledged to Liquidity Monsoon
6 month Vesting period starting from 2/9/25, any subsequent sales to be conducted a La 'Taco Stand' and tied to a % of daily volume

**Address(es):**  
`0x7faa1a20efd1127b8319dd09ed45884e012e8fa5`

**Notes:**  
These funds are transparent and publicly visible. There is no stealth allocation.
---
## 🔐 Operations (update 30/9/25)

**Purpose:**  
Daily operations, Initial Liquidity Monsoon Drops from this wallet.

**Address(es):**  
`0xf6548256eac1c8b8580714754e2055dc19311ae0`

**Notes:**  
These funds are transparent and publicly visible. There is no stealth allocation.
All wallet activity will be disclosed in updates and linked from this repo.

**The meme is public. So are the wallets.**

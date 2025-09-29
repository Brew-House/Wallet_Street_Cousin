# 🧪 Wallet Street Cousin — LP Test Filing

## 📂 Context
Following the initial pairing of **12.5% supply (≈1.03B WSC)** with **5,000 wFLR** on BlazeSwap, a live test swap was executed to confirm pool functionality.

---

## 🔍 Test Procedure
- Swap executed: **FLR → WSC** (small amount, test scale).  
- Counter-swap executed: **WSC → FLR** (confirm both directions).  
- Wallet used: **Deployer wallet**.  
- Gas source: available FLR balance within deployer.  

---

## ✅ Observations
- Swap completed successfully.  
- WSC appeared in wallet once contract was imported.  
- Reverse swap confirmed pool symmetry.  
- No errors in BlazeSwap interface.  

---

## 🔗 References

**Token Contract:**  
`0x37E43D91180171211b207670420824369DA80176`  
[View on Flare Explorer](https://flare-explorer.flare.network/address/0x37E43D91180171211b207670420824369DA80176)

**Initial LP Transaction:**  
[Flare Explorer TX](https://flare-explorer.flare.network/tx/0xa3db2ae5ef12faa8ab7573c7c5d99a0fe70ad1beece41e11c457104b6eb15701)

**Test Swaps:**  
- [FLR → WSC](https://flare-explorer.flare.network/tx/0x5ba3e75ec42c57465cdc00208f396429b727f4a7b575d8766ebf0e794c2bdb69)  
- [WSC → FLR](https://flare-explorer.flare.network/tx/0x98717ca7af2219fc8650bc1d448b9762f6ec6efec25807cf272865c8a6ac3018)  

---

## 📜 Filing Notes
- Test confirms that the liquidity pool is live and functioning.  
- Test swap executed from **Deployer wallet**.  
- LP pairing confirmed: **12.5% WSC + 5,000 wFLR**.  

---

*This meme was open-sourced. Filing complete.*

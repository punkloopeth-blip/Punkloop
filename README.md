# 🌀 PunkLoop

**The autonomous Ethereum engine that loops CryptoPunks forever.**  
A one-time presale launches the system, then each future epoch self-triggers when liquidity taxes accumulate enough ETH to buy another Punk.

---

### 🌐 Live Site
[https://punkloop.xyz](https://punkloop.xyz)

---

### 🧠 Core Contracts
| Name | Address | Description |
|------|----------|-------------|
| **PloopToken** | [`0xEc8301F255aC509016d6a7B9B4822C0Cd1cBFf88`](https://etherscan.io/address/0xEc8301F255aC509016d6a7B9B4822C0Cd1cBFf88#code) | $PLOOP ERC-20 token |
| **ListingOracle** | [`0xD7708D19Bce58963F7821FC20Dc7e939cE85219c`](https://etherscan.io/address/0xD7708D19Bce58963F7821FC20Dc7e939cE85219c#code) | Oracle tracking Punk listings and floor price data |
| **V4Forwarder** | [`0xF9F1b276Fc465200A1451C1efC1dA094689A754f`](https://etherscan.io/address/0xF9F1b276Fc465200A1451C1efC1dA094689A754f#code) | Liquidity tax router that accumulates ETH for new epochs |
| **PunkLoopEngine** | [`0x2140c8eff891B7eA232021995Fb56E440aDCCc29`](https://etherscan.io/address/0x2140c8eff891B7eA232021995Fb56E440aDCCc29#code) | Core epoch and winner logic |

---

### ⚙️ How PunkLoop Works

**1️⃣ One-Time Presale (Epoch 0)**  
- The presale is a single event used to bootstrap the PunkLoop system.  
- ETH raised establishes the initial liquidity and treasury routing via the **V4Forwarder**.  
- Once completed, all future Punk purchases and epoch triggers become fully autonomous.

**2️⃣ Continuous Epochs (Post-Presale)**  
- The **V4Forwarder** collects a small tax from trades within the $PLOOP liquidity pool.  
- When the tax balance reaches the **oracle-determined Punk price threshold**, a new epoch automatically begins.  
- The **ListingOracle** supplies live Punk listings from Punk Strategy, ensuring each purchase is market-accurate.

**3️⃣ Winner Selection & Decision Mechanic**  
- Each epoch (including the presale) selects a winner.  
- The winner faces a choice:  
  - 💰 **Claim 20% of the global Punk floor in ETH immediately**, **or**  
  - 🔒 **Lock the Punk NFT for 12 months** to gain **full ownership** at unlock.  

This mechanic blends instant liquidity incentives with long-term alignment toward Punk holding and protocol growth.

---

### 🧩 Solving Punk Strategy’s Major Limitation

> “Roughly 70% of Punk Strategy’s volume trades outside their V4 pool.”  

PunkLoop fixes this structural leakage through **pool enforcement**:  
- Only wallets that **trade within the official PLOOP pool** remain eligible for epoch rewards and draws.  
- Wallets that trade outside the sanctioned pool are **automatically disqualified** by the Engine contract.  
- This drives organic volume into the official PLOOP pool and stabilizes on-chain liquidity.

---

### 🔗 Verified Contracts
All contracts are verified on [Etherscan](https://etherscan.io/):

- [PloopToken](https://etherscan.io/address/0xEc8301F255aC509016d6a7B9B4822C0Cd1cBFf88#code)
- [ListingOracle](https://etherscan.io/address/0xD7708D19Bce58963F7821FC20Dc7e939cE85219c#code)
- [V4Forwarder](https://etherscan.io/address/0xF9F1b276Fc465200A1451C1efC1dA094689A754f#code)
- [PunkLoopEngine](https://etherscan.io/address/0x2140c8eff891B7eA232021995Fb56E440aDCCc29#code)

---

### 🧾 Tokenomics Overview
| Allocation | Percentage | Notes |
|-------------|-------------|-------|
| Presale Participants | 60% | Distributed after successful presale |
| Dev Allocation | 1.69% | smol not greedy |
| Treasury + Liquidity | 38.31% | For LP, burns, and future epochs |

---

### 🐦 Social
- [Twitter / X](https://x.com/punkloopeth)

---

### 🧾 License
MIT License — see [LICENSE](LICENSE)

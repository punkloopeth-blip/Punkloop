# 🌀 PunkLoop

**The autonomous presale engine looping CryptoPunks forever.**  
Deployed and verified on Ethereum mainnet.

---

### 🌐 Live Site
[https://punkloop.xyz](https://punkloop.xyz)

---

### 🧠 Core Contracts
| Name | Address | Description |
|------|----------|-------------|
| **PloopToken** | [`0xEc8301F255aC509016d6a7B9B4822C0Cd1cBFf88`](https://etherscan.io/address/0xEc8301F255aC509016d6a7B9B4822C0Cd1cBFf88#code) | $PLOOP ERC-20 token |
| **ListingOracle** | [`0xD7708D19Bce58963F7821FC20Dc7e939cE85219c`](https://etherscan.io/address/0xD7708D19Bce58963F7821FC20Dc7e939cE85219c#code) | Oracle for Punk listings & floor price data |
| **V4Forwarder** | [`0xF9F1b276Fc465200A1451C1efC1dA094689A754f`](https://etherscan.io/address/0xF9F1b276Fc465200A1451C1efC1dA094689A754f#code) | ETH routing and burn forwarder |
| **PunkLoopEngine** | [`0x2140c8eff891B7eA232021995Fb56E440aDCCc29`](https://etherscan.io/address/0x2140c8eff891B7eA232021995Fb56E440aDCCc29#code) | Core presale engine and epoch logic |

---

### 🧩 Overview

PunkLoop automates Ethereum presales through epoch-based logic that loops ETH contributions into CryptoPunk acquisitions, treasury routing, and tokenized participation rewards.

Each presale epoch executes autonomously via the **PunkLoopEngine**, distributing contributions and managing forwarder-based burn events through the **V4Forwarder**.

---

### ⚙️ Features
- Autonomous presale epochs with soft/hard caps  
- Weighted participant selection and entropy-seeded draws  
- On-chain Punk acquisition routing via oracle pricing  
- ETH forwarding and burn streams  
- Verified open-source architecture  

---

### 🔗 Verified Contracts
All contracts are verified on [Etherscan](https://etherscan.io/):
- [Engine](https://etherscan.io/address/0x2140c8eff891B7eA232021995Fb56E440aDCCc29#code)
- [Token](https://etherscan.io/address/0xEc8301F255aC509016d6a7B9B4822C0Cd1cBFf88#code)
- [Forwarder](https://etherscan.io/address/0xF9F1b276Fc465200A1451C1efC1dA094689A754f#code)
- [Oracle](https://etherscan.io/address/0xD7708D19Bce58963F7821FC20Dc7e939cE85219c#code)

---

### 🐦 Social
- [Twitter / X](https://x.com/punkloopeth)

---

### 🧾 License
MIT License — see [LICENSE](LICENSE) for details.

# 🪩 Netlink Token (NET)

Official smart contract and transparency repository for **Netlink Token (NET)** — a community-driven utility token deployed on the **Polygon (PoS)** network.

---

## 📄 Contract Details
- **Token Name:** Netlink Token (NET)  
- **Network:** Polygon (PoS) — Chain ID 137  
- **Contract Address:** [`0x0e893B239094A5c573373d44CF1C7D03576b95cb`](https://polygonscan.com/token/0x0e893B239094A5c573373d44CF1C7D03576b95cb)  
- **Total Supply:** 99,000,000 NET  
- **Standard:** ERC-20 (EVM Compatible)

> Always verify the official contract address before any on-chain interaction.

---

## 🔐 Security & Transparency

### 1️⃣ GoPlus Token Security Scan
**Live report:**  
[View on GoPlus Labs](https://gopluslabs.io/token-security/137/0x0e893B239094A5c573373d44CF1C7D03576b95cb)

**Key notes:**
- GoPlus performs **real-time automated security scans** using on-chain bytecode analysis (not manual review).  
- Results can update automatically when metadata or ownership status changes on-chain.  
- It helps detect potential issues like minting rights, blacklist, high tax/fee, proxy usage, or honeypot risks.

🧾 **Local summary:**  
A snapshot of the GoPlus report is stored under `/audits/goplus-scan.txt` for archival transparency.

---

### 2️⃣ Certora Formal Verification
- **Status:** Planned (Free Tier, basic invariant testing)  
- **Purpose:** To mathematically prove logical safety for core token operations such as transfer, mint, and burn.  
- **Output:** Future verification logs will be published under `/audits/certora-result.txt`.

> Formal verification by Certora complements public scans by providing **mathematical proofs** of contract behavior.

---

## 📁 Repository Structure

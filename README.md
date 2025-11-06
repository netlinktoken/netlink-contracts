# 🪩 Netlink Token (NET)

Official smart contract and transparency repository for **Netlink Token (NET)** — a community-driven utility token deployed on the **Polygon (PoS)** network.

---

## 📄 Contract Details
| Property | Information |
|-----------|--------------|
| **Token Name** | Netlink Token (NET) |
| **Network** | Polygon (PoS) — Chain ID 137 |
| **Contract Address** | [`0x0e893B239094A5c573373d44CF1C7D03576b95cb`](https://polygonscan.com/token/0x0e893B239094A5c573373d44CF1C7D03576b95cb) |
| **Total Supply** | 99,000,000 NET |
| **Standard** | ERC-20 (EVM Compatible) |
| **Deployer** | Netlink Developer Team |

> Always verify the official contract address before any on-chain interaction.

---

## 🔐 Security & Transparency Overview
| Category | Status | Reference / Notes |
|-----------|---------|------------------|
| **GoPlus Security Scan** | ✅ Passed *(no critical risk detected)* | [View Report](https://gopluslabs.io/token-security/137/0x0e893B239094A5c573373d44CF1C7D03576b95cb) |
| **Ownership Status** | 🔒 Locked / Renounced | Confirmed on PolygonScan |
| **Source Code Verification** | ✅ Verified | Public on PolygonScan |
| **Certora Formal Verification** | 🧠 Planned | Basic invariant testing (transfer, mint, burn) |
| **Audit Archive** | 📂 Available | `/audits/` folder contains scan snapshots |

---

## 🧾 GoPlus Live Security Summary
**Latest check:** November 2025  
> GoPlus performs real-time on-chain security analysis (not manual review).  
> Report may change automatically when contract metadata or state updates.

| Risk Category | Detected | Description |
|----------------|-----------|-------------|
| Mint / Unlimited Supply | ❌ | No mint function detected |
| Blacklist / Freeze | ❌ | No blacklist control |
| Trading Fees / Tax | ✅ *Low* | Fixed 0% transfer fee |
| Ownership Renounced | ✅ | Ownership locked for transparency |
| Proxy Contract | ❌ | No proxy pattern detected |
| Honeypot / Malicious Pattern | ❌ | Safe to trade on Polygon DEXs |

> A local copy of this summary is stored in `/audits/goplus-scan.txt`.

---

## 📁 Repository Structure

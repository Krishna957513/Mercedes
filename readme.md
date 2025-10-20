# 🌠 WishBox – Immutable Wishes on the Blockchain

**WishBox** is a simple yet meaningful Ethereum smart contract that allows users to record their wishes permanently on the blockchain.  
Each wish is timestamped, publicly visible, and forever stored — a digital time capsule of dreams, hopes, and gratitude.

---
prove of work
Image- Screenshot 2025-10-18 232004.png
## 🧩 Smart Contract Overview

**File:** `def.sol`  
**Language:** Solidity ^0.8.0  
**License:** MIT  

### ✨ What It Does
- Users can **make a wish** with a custom message.
- All wishes are **stored permanently** on the blockchain.
- Anyone can **view** the total number of wishes or **read all wishes**.
- Each wish includes:
  - The **wisher’s address**
  - The **wish message**
  - The **timestamp** (block time when the wish was made)

---

## 🧠 Contract Structure

```solidity
struct Wish {
    address wisher;
    string message;
    uint256 timestamp;
}


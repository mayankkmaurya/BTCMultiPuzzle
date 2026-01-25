# BTC Multi Puzzle Pool

A collaborative Bitcoin puzzle mining pool that searches **multiple puzzles simultaneously** using random key generation.

[![Pool Stats](https://img.shields.io/badge/Pool-Live%20Stats-orange)](https://btcmultipuzzle.com)
[![Telegram](https://img.shields.io/badge/Telegram-Join%20Chat-blue)](https://t.me/btcmultipuzzle)

---

## 🎯 What Are Bitcoin Puzzles?

In 2015, someone created a series of Bitcoin wallets with increasing bounties. The private keys can be found by searching through specific number ranges. Earlier puzzles have been solved — the remaining ones hold **millions in BTC**.

| Puzzle | Range | Bounty |
|--------|-------|--------|
| #71 | 2⁷⁰ to 2⁷¹ | ~7 BTC |
| #72 | 2⁷¹ to 2⁷² | ~7 BTC |
| #73 | 2⁷² to 2⁷³ | ~7 BTC |

---

## ⚡ Why Multi-Puzzle?

Most pools focus on one puzzle at a time. **We don't.**

| Single-Puzzle Pools | BTC Multi Puzzle |
|---------------------|------------------|
| ❌ If someone else solves it, all work is lost | ✅ Progress on other puzzles remains |
| ❌ Must restart from zero on next puzzle | ✅ Instantly add new puzzles to rotation |
| ❌ All-in bet on one target | ✅ Diversified across 3 puzzles |

**If another group finds Puzzle #71 tomorrow, we've already searched a massive chunk of #72 and #73. That progress stays with us.**

---

## 💰 Payout Structure

**No upfront costs. You only share rewards if we win.**

| Recipient | Share | Description |
|-----------|-------|-------------|
| Pool Admin | 20% | Infrastructure & development |
| Finder Bonus | 10% | Extra reward for the machine that finds the key |
| All Contributors | 70% | Split by contribution % shown in pool stats |

---

## 🖥️ Requirements

- **NVIDIA GPU** (GTX 1060 or better recommended)
- **Windows** or **Linux** (Ubuntu 22.04 / 24.04)
- Stable internet connection
- Bitcoin address for payouts

---

## 🚀 Quick Start

### Download

| Platform | Download |
|----------|----------|
| Windows 64-bit | [puzzle-client-win64.zip](https://btcmultipuzzle.com/join/clients/puzzle-client-win64.zip) |
| Ubuntu 24.04 | [puzzle-client-ubuntu-24.tgz](https://btcmultipuzzle.com/join/clients/puzzle-client-ubuntu-24.tgz) |
| Ubuntu 22.04 | [puzzle-client-ubuntu-22.tgz](https://btcmultipuzzle.com/join/clients/puzzle-client-ubuntu-22.tgz) |

### Windows

1. Extract `puzzle-client-win64.zip` to a folder
2. Right-click `START-MINING.bat` → **Edit**
3. Change these two lines:
   ```batch
   set NICKNAME=YourNicknameHere
   set BTC_ADDRESS=YourBTCAddressHere
   ```
4. Save the file (Ctrl+S) and close
5. Double-click `START-MINING.bat` to run

### Linux

```bash
tar -xzf puzzle-client-ubuntu-*.tgz
chmod +x puzzle
./puzzle -s 72.60.71.15 -n YourNickname -b YourBTCAddress
```

### Command Line Options

| Flag | Description |
|------|-------------|
| `-s` | Server address (72.60.71.15) |
| `-n` | Your nickname (shows in pool stats) |
| `-b` | Your Bitcoin address (for payouts) |

---

## 📊 Live Stats

View real-time pool statistics, your contribution percentage, and active workers:

**[btcmultipuzzle.com](https://btcmultipuzzle.com)**

---

## ✅ Is This Legal?

**Yes, 100% legal.**

The Bitcoin Puzzle Challenge was **intentionally created** as a public cryptographic challenge. The creator deliberately funded these wallets and published the address ranges as an open invitation for anyone to solve them.

This is the same as:
- Solving a publicly posted math problem with a prize
- Participating in a cryptographic capture-the-flag competition
- Mining Bitcoin (searching for a valid block hash)
- Claiming a bug bounty

We are **not** attempting to crack random wallets. The puzzle wallets were specifically created to be solved — the creator *wants* someone to find the keys.

---

## 💬 Support

- **Telegram:** [t.me/btcmultipuzzle](https://t.me/btcmultipuzzle)
- **Pool Dashboard:** [btcmultipuzzle.com](https://btcmultipuzzle.com)

---

## 📜 License

This project is provided as-is for educational and recreational purposes. Participation is at your own risk.

---

<p align="center">
  <strong>Happy hunting! 🎯</strong>
</p>

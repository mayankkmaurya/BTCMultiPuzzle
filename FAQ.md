# Frequently Asked Questions

## General

### What are my actual odds of winning?
Low for any individual key, but non-zero. Unlike traditional lotteries, your contributions accumulate — every key checked is progress. And searching 3 puzzles simultaneously means 3x the opportunities.

### Why random search instead of sequential?
Random searching means every key has equal probability of being the winner, regardless of when you join. No advantage to early participants — the odds are always fair.

### How is my contribution calculated?
Your contribution percentage is tracked in real-time on [btcmultipuzzle.com](https://btcmultipuzzle.com). It's based on the verified work your GPU submits to the pool relative to everyone else.

### What's the "Finder Bonus"?
If your machine discovers the winning key, you get an extra 10% on top of your normal contribution share.

---

## Technical

### Why NVIDIA only?
Our client is optimized for CUDA, which provides the best performance for this type of computation. AMD support may come in the future.

### What GPU should I use?
Any NVIDIA GPU from GTX 1060 or newer works. Higher-end cards (RTX 3070, 3080, 4080, 4090) will check more keys per second.

### Can I run multiple GPUs?
Yes! Each GPU will be detected automatically and contribute to your total speed.

### How much internet bandwidth does it use?
Very little. The client only sends small status updates and receives work assignments.

### Will this damage my GPU?
No more than any other GPU-intensive task. The client uses your GPU similarly to gaming or rendering. Make sure you have adequate cooling.

---

## Payments

### When do I get paid?
Only when the pool solves a puzzle. This is a lottery-style system — there's no guaranteed payout timeline.

### How are payouts sent?
Directly to the Bitcoin address you specify when running the client.

### What if I change my BTC address?
Update the address in your client startup command. Your contribution history stays tied to your nickname.

---

## Legal

### Is this legal?
Yes. The puzzles were intentionally created as a public challenge. See our [full legal explanation](https://btcmultipuzzle.com/join) for details.

### Is this hacking?
No. We're solving a publicly posted cryptographic challenge, not accessing anyone's private funds without permission.

---

## Troubleshooting

### Client won't start
- Make sure you have an NVIDIA GPU with updated drivers
- Check that CUDA is installed
- Try running as administrator (Windows)

### "Connection refused" error
- Check your internet connection
- The server might be temporarily down — try again in a few minutes
- Join [Telegram](https://t.me/btcmultipuzzle) to check for announcements

### Low speed / performance
- Close other GPU-intensive applications
- Make sure your GPU isn't thermal throttling
- Update to the latest NVIDIA drivers

---

## Still have questions?

Join our [Telegram group](https://t.me/btcmultipuzzle) — we're happy to help!

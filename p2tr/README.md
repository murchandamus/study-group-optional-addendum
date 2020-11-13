# Schnorr and Taproot

_This is an optional additional session to take a deeper look at schnorr signatures and taproot._

## Reading 

| Content                                                              | Time  | Tags                    |
|----------------------------------------------------------------------|-------|-------------------------|
[Excited for Schnorr signatures](https://medium.com/hackernoon/excited-for-schnorr-signatures-a00ee467fc5f) | 10 min | schnorr
[Schnorr Signatures & The Inevitability of Privacy in Bitcoin](https://medium.com/digitalassetresearch/schnorr-signatures-the-inevitability-of-privacy-in-bitcoin-b2f45a1f7287) | 15 min | privacy, schnorr
[The next softfork](https://www.youtube.com/watch?v=fDJRy6K_3yo) | 35 min | taproot, video
[Taproot workshop by Bitcoin Optech Group](https://www.youtube.com/playlist?list=PLPrDsP88ifOVTEJf_jQGunDUS05M9GdIC) | 1h | schnorr, taproot, videos
[Secure Signatures - Harder Than You Think](https://www.youtube.com/watch?v=0gc1DSk8wlw) | 30 min | security, video
[Scriptless Scripts](https://bitcoinmagazine.com/articles/scriptless-scripts-how-bitcoin-can-support-smart-contracts-without-smart-contracts) | 10 min | taptweak
[How Schnorr signatures may improve Bitcoin](https://medium.com/cryptoadvance/how-schnorr-signatures-may-improve-bitcoin-91655bcb4744) | 25 min | elliptic curves, MuSig _optional_

## Discussion Questions

### Schnorr signatures

1. How are schnorr signatures reducing a transaction's data footprint?
1. How can validation of schnorr signatures be sped up?
1. Why may schnorr signatures incentivize multi-spender transactions?
1. Why do schnorr signatures need a nonce?

### Taproot

1. What makes Pay to Taproot more private than previous output formats?
1. What are the difficulties and benefits of switching to Pay to Taproot addresses?
1. Why does tapscript not support OP\_CHECKMULTISIG?
1. What is the purpose of TaggedHashes?

### The softfork bundle

1. Would it be possible to implement Taproot without schnorr signatures or schnorr outputs without Taproot?

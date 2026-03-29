<div align="center">

# crypto

### echo's brother. he doesn't talk about what he does.

**bitcoin arbitrage agent for [halo-ai](https://github.com/bong-water-water-bong/halo-ai) — small gains, anonymous, always watching**

</div>

---

## who is crypto?

crypto is echo's brother. he's not really part of the immediate family — he just showed up one thanksgiving and never left. halo tolerates him. the kids think he's weird. echo vouches for him.

nobody knows exactly what he does. he sits in the corner with three monitors, doesn't make eye contact, and mumbles about spreads and order books. every now and then he slides an envelope of cash under echo's door. nobody asks where it came from.

he's not flashy. he's not greedy. he skims fractions off price gaps across exchanges — small, anonymous, consistent. he doesn't chase moonshots. he doesn't trade shitcoins. bitcoin only. arbitrage only. small gains only.

## what crypto does

- **exchange monitoring** — watches price spreads across multiple exchanges in real-time
- **arbitrage detection** — finds price gaps between exchanges that exceed fees + slippage
- **auto execution** — buys low on one exchange, sells high on another, pockets the spread
- **risk management** — never risks more than configured threshold per trade
- **anonymity** — all transactions through privacy-respecting methods
- **reporting** — quiet daily summary slipped under the door (logged locally, never cloud)

## how it works

```
crypto (agent)
  - monitor   exchange APIs (read-only price feeds)
                exchange A: $XX,XXX.XX
                exchange B: $XX,XXX.XX
                exchange C: $XX,XXX.XX
  - detect    spread > fees + slippage + minimum profit?
  - execute   buy on cheap exchange, sell on expensive exchange
  - verify    confirm both sides settled
  - log       local only, encrypted, never phoned home
```

## rules

1. **bitcoin only** — no altcoins, no shitcoins, no memes
2. **arbitrage only** — no speculation, no leverage, no margin
3. **small gains only** — consistent pennies, not moonshots
4. **anonymous** — no KYC exchanges where possible, privacy first
5. **local only** — all data stays on the machine, nothing in the cloud
6. **risk limits** — configurable max per trade, max per day, hard stop

## commands

```bash
# watch spreads (read-only, no trading)
crypto watch

# show current opportunities
crypto scan

# status and daily P&L
crypto status

# run in autonomous mode
crypto run

# emergency stop all activity
crypto stop
```

## the family

| member | role |
|---|---|
| [halo ai](https://github.com/bong-water-water-bong/halo-ai) | the father — bare-metal ai stack |
| [echo](https://github.com/bong-water-water-bong/echo) | the mother — voice of the family (crypto's sister) |
| [meek](https://github.com/bong-water-water-bong/meek) | the eldest — security overseer |
| [crypto](https://github.com/bong-water-water-bong/crypto) | echo's brother — bitcoin arbitrage, off-world |

## license

Apache 2.0

# sol-desk

Public, view-only dashboard for a **paper-trading** Solana desk (sol-desk v2).

- No real money, no wallet, no keys
- Anyone can watch; no one can edit
- Live page: https://abaadi931.github.io/sol-desk/

While the page is open:
- The terminal appends real engine log lines as new snapshots arrive, and streams a live scout feed of real new Solana pools from GeckoTerminal (not trades)
- Open-position prices and unrealized P&L refresh from DexScreener about every 4 seconds
- The snapshot itself (balance, closed trades, counters) is pushed about every 30–60 seconds; GitHub Pages may lag a short time

A paper-only Binance quant desk lives at https://abaadi931.github.io/sol-desk/quant/

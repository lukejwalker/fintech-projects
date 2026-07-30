# FinTech Projects

A collection of trading tools, UI prototypes, and experiments built at the
intersection of markets and technology.

I've spent nearly two decades in trading, the last 13 of them in the Chicago
community — working at a hedge fund, selling execution technology to
institutional options traders, and working deeply with FIX, market structure,
and low-touch trading workflows. These projects merge that experience with
building real technical fluency.

Not an engineer. Operator, builder, and someone who thinks the gap between
markets people and technology people is smaller than it looks.

---

## Projects

### Options Montage UI

**[Live Demo](https://lukejwalker.github.io/fintech-projects/options_montage_v7.html)**

A browser-based options chain viewer prototyping a modern institutional
montage. Includes:

- Full call/put chain with bid/ask IV, market depth and Greeks
- Order ticket supporting both limit price and limit vol orders
- Open/close routing (BTO/STO/BTC/STC) and a delta auto-hedger
- Spread builder and position blotter with portfolio-level Greeks aggregation
- Live order status panel and an IV skew chart with separate bid/ask curves

Built in vanilla HTML/CSS/JavaScript. Data is simulated; the UI reflects
actual institutional workflows from years working alongside options traders
and execution desks.

---

### Vol Scanner

**[Live Demo](https://lukejwalker.github.io/fintech-projects/vol_scanner.html)**

A volatility surface scanner built for pre-trade idea generation. Includes:

- Watchlist with IVR pills, price and realized vol context
- IV heatmap across delta buckets and tenors with hover tooltips
- Three normalization modes: vol-point change, percentile rank and z-score
- Lookback toggle (1D, 3D, 7D, 30D) for comparing surface shifts
- Term structure chart with ±1σ historical band and lookback overlay

Built in vanilla HTML/CSS/JavaScript with simulated surface data. Reflects
actual pre-trade workflows from institutional options desks.

---

### Vol Surface Viewer

**[Live Demo](https://lukejwalker.github.io/fintech-projects/vol_surface.html)**

A 2D volatility surface viewer for examining the smile and term structure of
a single name. Includes:

- Smile plot with bid, theo and ask IV curves, one expiry at a time
- X-axis toggle across delta, moneyness (K/S) and log-moneyness
- Strike grid showing put/theo/call in both price and vol terms side by side
- Click any point on the smile to highlight the nearest strike in the grid
- Right-click a strike to send both legs to an order ticket

Built in vanilla HTML/CSS/JavaScript with a Black-Scholes surface. Data is
simulated; the layout reflects institutional vol-trading workflows.

---

## Connect

[LinkedIn](https://www.linkedin.com/in/lukejwalker/) · [GitHub](https://github.com/lukejwalker)

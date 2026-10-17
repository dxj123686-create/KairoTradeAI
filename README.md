# TrendPilot Android MVP

An original Android Studio starter project inspired by common AI-assisted chart-analysis workflows. It is not affiliated with KairoTrend and does not copy its code or branding.

## Features in this prototype
- Chinese mobile-first dark interface
- Public Binance spot ticker and candlestick data (REST API)
- BTC, ETH, SOL, BNB, XRP and DOGE symbol switching
- 5m / 15m / 1h / 4h / 1d candle chart
- Basic rule-based technical summary (moving averages, RSI, recent support/resistance)
- Position-size / planned-risk calculator
- Watchlist and locally stored analysis history

## Important limitations
- The current analysis is deterministic indicator logic, not a hosted large-language-model AI or institutional-flow detector.
- It does not place trades or connect to exchange accounts.
- Market access depends on network and Binance API availability in your region. No API keys are included.
- This is an MVP, not investment advice; signals may be wrong and trading can lose money.

## Build an APK
1. Install Android Studio (current stable) on a computer.
2. Open this `KairoTrendMobile` folder as an existing project.
3. Allow Gradle sync and install the Android SDK platform requested by the project (API 35).
4. Select **Build > Build Bundle(s) / APK(s) > Build APK(s)**.
5. The debug APK will be in `app/build/outputs/apk/debug/`.

Package: `com.example.kairotrend`

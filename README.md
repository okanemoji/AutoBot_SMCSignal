# AutoBot_SMCSignal

📈 Automated Smart Money Concept Trading Bot using Python, Google Sheets, and TradingView.

## 🔥 Features
- ✅ Trade based on signals from Google Sheets (via TradingView alerts)
- ✅ Entry size based on % of total balance
- ✅ Supports multi-symbol (BTCUSDT, ETHUSDT, SOLUSDT)
- ✅ Timeframe: 4H, 1H, 15M (limit 3 trades/day for 15M)
- ✅ Trailing Stop triggered by TP (RR hit)
- ✅ PnL logging to Google Sheet
- ✅ Telegram notification
- ✅ Monthly trade report saved to Google Drive

## ⚙️ How it works
1. Monitor signal sheet (connected to TradingView)
2. Open order with stop loss but no take profit
3. Once TP (RR) is reached, trailing stop begins
4. Trades are managed and results are logged

## 🚀 Start Bot
```bash
bash start.sh

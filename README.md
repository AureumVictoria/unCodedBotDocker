## 🚀 Quick Deploy on Railway

### 1. Deploy with One Click
[![Deploy on Railway](https://railway.app/button.svg)](https://railway.app/new/template/uncoded-bot)

### 2. After Deploy (Important!)
The bot needs your API keys to work:

1. **Wait 2-3 minutes** for all services to start
2. **Add Binance API Keys:**
   - Click on `trading-bot` service in Railway
   - Go to "Variables" tab
   - Fill in `API_KEY` and `API_SECRET`
   - Click "Deploy" to apply changes

3. **Add Telegram Bot Token:**
   - Click on `telegram-bot` service
   - Go to "Variables" tab
   - Fill in:
     - `TELEGRAM_BOT_TOKEN` (from @BotFather)
     - `TELEGRAM_GROUP_ID` (your group ID)
     - `TELEGRAM_OWNER_ID` (your user ID)
   - Click "Deploy" to apply changes

### 3. Verify Everything Works
- Check PostgreSQL logs: Should show "database system is ready"
- Check trading-bot logs: Should show "Connected to Binance"
- Check telegram-bot logs: Should show "Bot started"

### 💡 Pro Tips:
- Railway gives you $5 free credits every month
- Your bot will cost ~$5-10/month depending on usage
- You can pause services anytime to save costs
- Use Railway's mobile app to monitor on the go
GB BARAKA Telegram Bot + Web App

MUHIM:
Siz tokenni chatga yubordingiz. Xavfsizlik uchun @BotFather orqali /revoke qiling va yangi token oling.

Ishga tushirish:
1) index.html faylini Netlify yoki Vercel'ga yuklang.
2) Olingan HTTPS linkni WEBAPP_URL sifatida kiriting.
3) Botni Railway/Render/VPS'da ishga tushiring.

Environment variables:
BOT_TOKEN=BotFather bergan yangi token
WEBAPP_URL=https://sizning-webapp-linkingiz

Local test:
pip install -r requirements.txt
BOT_TOKEN=... WEBAPP_URL=... python bot.py

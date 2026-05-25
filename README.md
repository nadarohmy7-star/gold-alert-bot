import requests

TOKEN = "8842816335:AAE7t2r6QezaHBgpCM7HfzRqblNq1h07ZoY"
CHAT_ID = "https://t.me/goldmohamedmm"

message = "🟢 تم تشغيل بوت الذهب بنجاح!"

url = f"https://api.telegram.org/bot{TOKEN}/sendMessage"

data = {
    "chat_id": CHAT_ID,
    "text": message
}

requests.post(url, data=data)

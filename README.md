import requests

TOKEN = "8842816335:AAEIy3Hbaj3WMJju0rfDQhAn0nQotOwuBv4"
CHAT_ID = "https://t.me/goldsignals20266"

url = f"https://api.telegram.org/bot{TOKEN}/sendMessage"

data = {
    "chat_id": CHAT_ID,
    "text": "🟢 البوت يعمل الآن"
}

requests.post(url, data=data)

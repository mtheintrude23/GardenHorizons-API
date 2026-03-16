# 🌿 Garden Horizons Stock API

**Developed by Zenith 🚀**

The official API system for retrieving **Garden Horizons stock data**, including **Seeds, Gear, Weather, and historical appearances**.

---

# 🔗 Base URL
```
https://zenithghz.qzz.io/
```

---

# 📡 WebSocket (Realtime Updates)

For realtime stock updates:

```
wss://api.nthanhtai.xyz/api/stock
```

The WebSocket will push data whenever the stock changes.

---

# 🛠️ Available Endpoints

## 🌱 Get Seeds
Retrieve the current **seed stock**.

```
GET /api/seed
```

---

## ⚙️ Get Gear
Retrieve the current **gear stock**.

```
GET /api/gear
```

---

## 📦 Get All Data
Retrieve **all available stock data** (seeds + gear).

```
GET /api/all
```

---

## 🌤️ Weather
Retrieve the **current weather information**.

```
GET /api/weather
```

---

## 📊 Last Seen
Retrieve **seed and gear appearance history** for the **day and week**.

```
GET /api/lastseen
```

---

# 📄 Example Response

```json
{
  "success": true,
  "data": {
    "seeds": [
      {
        "name": "Corn",
        "emoji": "🌽",
        "quantity": 2,
        "category": "COMMON"
      }
    ],
    "gear": [
      {
        "name": "Trowel",
        "emoji": "⛏️",
        "quantity": 1
      }
    ]
  }
}
```

---

# 🆘 Bug Reports

If you encounter any issues, please report them to the admin or send a message in the bug report channel.

**Bug Report Channel**

[Bug Report](https://discord.com/channels/1458075109989421067/1483070894782943263)
---

# 💬 Discord Support

Join the support server:

```
https://discord.gg/NKKesve9d8
```

---

# ⚡ Notes

- The API is updated continuously.
- WebSocket provides **real-time stock updates**.
- Suitable for **Discord bots, websites, and third-party applications**.

---

⭐ If you find this API useful, consider supporting the project!

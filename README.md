# 🪙 Crypto Landing Page

A simple and stylish cryptocurrency landing page that shows live prices for Bitcoin, Ethereum, and Dogecoin — fetched directly from a real API.

## 👀 What Does It Look Like?

- A full-screen background image with white text
- A navigation bar with logo, links, and a language button
- A bold headline with an orange highlight
- Live crypto prices displayed at the bottom right corner

## ✨ What Can It Do?

- ✅ Shows live prices for **BTC, ETH, and DOGE**
- ✅ Fetches real-time data from **CoinLayer API**
- ✅ Clean dark-themed design with orange accents
- ✅ Fully responsive navigation bar
- ✅ Uses **async/await** to load data without freezing the page

## 🔌 API Used

This project uses the **CoinLayer API** to get live crypto prices.

- Website: [coinlayer.com](https://coinlayer.com)
- Returns prices in USD

> **Note:** The API key in the code is for demo purposes. If it stops working, get your own free key from [coinlayer.com](https://coinlayer.com) and replace it in `script.js`.

## 🧠 How The JavaScript Works

1. Page loads
2. script.js runs getCryptoRates()
3. It sends a request to the CoinLayer API
4. API sends back live crypto prices
5. Prices are shown on screen inside the coin cards

If anything goes wrong (no internet, bad key, etc.), the error is caught and shown in the console — the page won't crash.

# 🔥 Free Fire API (Instant Delivery)

[![API Status](https://img.shields.io/badge/API_Status-Online_24%2F7-brightgreen?style=for-the-badge)](https://matrixgamingstore.com)
[![Delivery](https://img.shields.io/badge/Delivery-Instant_(1--5_Sec)-blue?style=for-the-badge)](https://matrixgamingstore.com)
[![Official Website](https://img.shields.io/badge/Website-matrixgamingstore.com-orange?style=for-the-badge)](https://matrixgamingstore.com)

Welcome to the official documentation repository for the **Matrix Gaming Store Free Fire Automatic Top-Up API**. 

Integrate 100% automated, instant **Free Fire UID Diamond Top-Ups, Weekly/Monthly Memberships, and Level-Up Passes** directly into your own website, mobile app, or Telegram bot with a simple REST API.

🌐 **Official Website & API Portal:**
(https://matrixgamingstore.com/reseller)

---

## 🚀 Key Features

* ⚡ **Instant Auto-Topup:** Orders are processed automatically within 1–5 seconds (24/7/365).
* 🎯 **UID Based Only:** No account login required—only the Player UID is needed.
* 💎 **All Packages Supported:** 25 Diamonds to 2530+ Diamonds, Weekly Membership, Monthly Membership, and Level-Up Pass.
* 💰 **Wholesale Reseller Rates:** Best market pricing for store owners and high-volume resellers.
* 🔒 **Secure & Reliable:** High-uptime infrastructure with instant webhook/status callbacks and live order tracking.
* 🛠️ **Easy Integration:** Compatible with PHP, Laravel, Node.js, Next.js, Python, and WordPress/WooCommerce.

---

## 📦 Supported Products & Packages

| Package Code | Product Name | Type | Delivery Speed |
| :--- | :--- | :--- | :--- |
| `FF_25` | 25 Diamonds | UID Top-Up | Instant |
| `FF_115` | 115 Diamonds | UID Top-Up | Instant |
| `FF_240` | 240 Diamonds | UID Top-Up | Instant |
| `FF_610` | 610 Diamonds | UID Top-Up | Instant |
| `FF_1240` | 1240 Diamonds | UID Top-Up | Instant |
| `FF_2530` | 2530 Diamonds | UID Top-Up | Instant |
| `FF_WEEKLY` | Weekly Membership | UID Top-Up | Instant |
| `FF_MONTHLY` | Monthly Membership | UID Top-Up | Instant |
| `FF_LEVELUP` | Level Up Pass | UID Top-Up | Instant |

*(For live reseller pricing and full product catalog, visit [matrixgamingstore.com](https://matrixgamingstore.com))*

---

## 💻 Sample API Integration (Preview)

> **Note:** Our core API engine is private and hosted securely on our servers. Below is a preview of how simple it is to send a top-up request once you receive your Reseller API Key.

### 1. Create Top-Up Order (`POST`)

```http
POST [https://matrixgamingstore.com/api/v1/topup/freefire](https://matrixgamingstore.com/api/v1/topup/freefire)
```

**Request Payload (JSON):**

```json
{
  "api_key": "YOUR_SECRET_API_KEY",
  "player_uid": "1234567890",
  "package_code": "FF_115",
  "client_order_id": "ORD_987654321"
}
```

### 2. Sample JSON Response

```json
{
  "status": "success",
  "message": "Top-up completed successfully",
  "data": {
    "transaction_id": "MTX_88492019",
    "client_order_id": "ORD_987654321",
    "player_uid": "1234567890",
    "nickname": "PRO_GAMER",
    "package": "115 Diamonds",
    "order_status": "COMPLETED"
  }
}
```

---

## 🔑 How to Get API Access & Secret Key?

To protect our system and resellers, the API endpoints and secret keys are provided exclusively to verified partners and store owners.

1. Visit our official website: **[Matrix Gaming Store](https://matrixgamingstore.com)**
2. Create an account or contact our support team via the website for **Reseller / API Access**.
3. Get your `API_KEY`, full integration documentation, and start automating your Free Fire orders instantly!

---

## 📞 Contact & Support

* 🌐 **Website:** [https://matrixgamingstore.com](https://matrixgamingstore.com)
* 💬 **Support:** Contact us directly through the live chat / support section on [matrixgamingstore.com](https://matrixgamingstore.com) for API onboarding and wholesale pricing.

---
*© Matrix Gaming Store. All rights reserved.*


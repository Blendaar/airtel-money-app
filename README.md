# Airtel Money Chad - Transfer Web App

A secure web application for Airtel Money Chad network money transfers.

## 🎯 Features

✅ **Live money transfer execution**
✅ **Real-time transaction confirmation**
✅ **Transaction response display**
✅ **Mobile-friendly interface**
✅ **Secure Bearer Token authentication**
✅ **No data storage on servers**
✅ **Direct HTTPS connection to Airtel API**

## 📱 Access Your App

**Live URL:** 
```
https://blendaar.github.io/Airtel-money-/
```

## 🚀 How to Use

### Step 1: Get Your Bearer Token
1. Go to: https://developers.airtel.td
2. Log in to your account
3. Find your API credentials/Bearer Token
4. Copy the token

### Step 2: Open the App
- Open this URL on your mobile phone browser:
  ```
  https://blendaar.github.io/Airtel-money-/
  ```

### Step 3: Fill in Transfer Details
- **Bearer Token** - Paste your token from Step 1
- **Payer Phone Number** - +23565075462 (your phone)
- **Payer Name** - John (or your name)
- **Payee Phone Number** - +23562558581 (recipient)
- **Payee Name** - Bob (or recipient name)
- **Amount** - 50 XAF (or desired amount)

### Step 4: Execute Transfer
1. Click **"Execute Transfer"** button
2. Review confirmation dialog
3. Click **"Confirm - Send Money"**
4. Wait for response

### Step 5: Check Response
The app displays:
- ✅ Success status and transaction details
- ⚠️ Warnings or additional information
- ❌ Error messages if failed

## 📋 Requirements

- ✅ Valid Airtel Chad Bearer Token
- ✅ Sender phone number: +235XXXXXXXX
- ✅ Recipient phone number: +235XXXXXXXX
- ✅ Amount in XAF currency
- ✅ Sufficient balance
- ✅ Internet connection

## 🔗 API Endpoint

| Parameter | Value |
|-----------|-------|
| Base URL | https://openapiuat.airtel.td |
| Endpoint | /merchant/v1/transactions |
| Method | POST |
| Content-Type | application/xml |
| Country | TD (Chad) |
| Currency | XAF |
| Auth | Bearer Token |

## 🔐 Security

✅ **Local Processing** - All code runs in your browser
✅ **No Server Storage** - Bearer token NOT saved anywhere
✅ **Direct Connection** - Only communicates with Airtel API
✅ **HTTPS Encryption** - Data encrypted in transit
✅ **No Tracking** - No analytics or user tracking

## ⚠️ Important Warnings

🚨 **This executes REAL transactions!**
- Double-check all details before confirming
- Verify phone numbers are correct
- Ensure you have sufficient balance
- This action CANNOT be undone
- Money will be deducted immediately

## 📞 Support

For issues:
- **Airtel Developer Portal:** https://developers.airtel.td
- **Airtel Support:** support@airtel.td

## 📄 License

MIT License - Open source

---

**Created by:** Blendaar
**Last Updated:** 2026-07-14
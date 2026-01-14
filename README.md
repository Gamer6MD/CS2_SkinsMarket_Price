# CS2 SkinsMarket Price Tracker (Data Feed)
This repository serves as a centralized data hub for Counter-Strike 2 skin prices, collected directly from the Steam Community Market. The project is dedicated to providing up-to-date market information in a machine-readable format (.json) completely free.
## 📊 Provided Data
The repository contains the prices.json file, which includes:
 * Real-time Prices: Current listing values on the Steam Market (in USD). Data time is UTC+02:00 (Romania, Bucharest / Moldova, Chisinau)
 * Comprehensive Coverage: Data for both standard (Normal) and StatTrak™ variants.
 * Wear Differentiation: Specific pricing for every skin condition (Factory New, Minimal Wear, etc.).
## ⏱️ Update Frequency
To ensure data accuracy without overloading the source servers, the system operates on the following schedule:
 * Cloud Synchronization: The prices.json file on GitHub is automatically updated every 30 minutes.
 * Data Freshness: Each individual skin is re-scanned at an interval of approximately 6 hours. This means that while the file itself updates frequently, the price for a specific skin will change in the list a few times per day.
## 📂 Data Structure
The prices.json file is structured as an object, where the key is the official Steam Market hash name:
```{
  "AK-47 | Redline (Field-Tested)": {
    "price": 25.45,
    "date": "2024-05-20 14:30:05"
  },
  "StatTrak™ M4A4 | Howl (Factory New)": {
    "price": 5450.00,
    "date": "2024-05-20 14:35:12"
  }
}
```
## ⚠️ Important Notes
 * Currency: All prices are expressed in USD.
 * Source: Data is sourced exclusively from the Steam Community Market.
 * Purpose: This repository is intended for developers who need a consistent price feed or users who wish to track market trends without running their own scripts.

## ☕ Support & Future Development
This project is in active development. If you find it useful and want to support its continuation:
* Support the project: If I see enough support, I will invest more time and resources into this project to make it much better, faster and with extended functionalities.
* Feedback: Any suggestions are welcome in the "Issues" section.
* ERC20/BEP20 wallet (binance): 0x8361392fad7cc5bca67522de8521c2236c23074d


*This repository contains only the resulting data. The collector's source code is private and runs on a separate infrastructure.*

*Disclaimer: This project is not affiliated with Valve Corporation or Steam.*

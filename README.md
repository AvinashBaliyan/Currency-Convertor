# Currency Converter

A simple currency converter web app built with HTML, CSS, and JavaScript.

## Description

This project converts one currency to another using live exchange rate data from a free API. It also displays country flags for the selected currency pair.

## Features

- Select source currency and target currency
- Enter an amount to convert
- Fetch live exchange rates from a public API
- Display the converted amount
- Show country flags for selected currencies

## Files

- `index.html` - Main webpage structure
- `style.css` - Styling for the page
- `countrycode.js` - Currency code to country code mapping for flags
- `logic.js` - JavaScript logic for fetching exchange rates and updating the UI

## How to run

1. Open `index.html` in your browser.
2. Change the amount, source currency, and target currency.
3. Click **Get Exchange Rate**.
4. The conversion result will display below the controls.

## Notes

- The app uses a free exchange rate API in `logic.js`.
- If the API is unavailable, the converter will show an error message.
- Ensure you have an internet connection to fetch live rates.

## Author

- Name: Avinash Kumar Baliyan❤️
- LinkedIn: https://www.google.com/url?sa=t&source=web&rct=j&opi=89978449&url=https://in.linkedin.com/in/avinash-baliyan-1277a8362&ved=2ahUKEwjD88K3jZ2VAxXrR2cHHZvcDCIQFnoECCMQAQ&usg=AOvVaw1Tx5hFu7UnHZZ5pVMK0ac1

## Improvements

Possible future enhancements:

- Add a swap button to switch from/to currencies
- Add more precise formatting for converted values
- Add offline support or local rate caching
- Add error handling for invalid currency codes

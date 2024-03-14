# Currency Converter

This Currency Converter web application allows users to convert currencies based on real-time exchange rates. It features an intuitive interface where users can input the amount to convert and select the currencies they want to convert from and to. The application fetches real-time exchange rates from an external API and utilizes JavaScript promises for efficient handling of asynchronous API requests.

## Features

- Conversion between different currencies based on real-time exchange rates.
- User-friendly interface with dropdown menus for selecting currencies.
- Dynamic updates of exchange rates and converted amounts.
- API integration for fetching real-time exchange rates.

## How to Use

1. Enter the amount you want to convert in the "Enter Amount" field.
2. Select the currency you want to convert from in the "From" dropdown menu.
3. Select the currency you want to convert to in the "To" dropdown menu.
4. Click the "Get Exchange Rate" button to see the converted amount displayed below along with the current exchange rate.

## API Integration

The Currency Converter fetches real-time exchange rates from an external API. Please note that due to an update in the API repository on 03/03/24, only base conversions from Euro (EUR) can be calculated.

## Technologies Used

- HTML5
- CSS3
- JavaScript
- [Currency Exchange Rate API](https://latest.currency-api.pages.dev/v1/currencies/eur.json)

# EUR to AUD currency converter

A simple web-based tool for converting Euros (EUR) to Australian Dollars (AUD) using official Reserve Bank of Australia (RBA) exchange rates. Created specifically for Australian Tax Office (ATO) tax reporting, where official RBA rates are required for currency conversion.

## Why this tool?

When reporting foreign income (EUR) to the ATO, you must use the official RBA exchange rates for currency conversion. This tool simplifies the process by using RBA's official historical rates, making it suitable for tax reporting purposes.

## Data timing and availability

- **Historical data**: The RBA CSV file contains historical exchange rates from January 2023 onwards
- **Recent rates**: For very recent transactions (last few days), you'll need to wait for the official RBA rates to be published
  - The ATO provides an XML feed for the most recent exchange rates (last few days)
  - For tax purposes, it's recommended to wait 2-3 business days after a transaction date before converting the amount
  - This ensures you're using the official published RBA rates rather than preliminary data

## Usage

1. Download `currency_converter_EUR_AUD.html` to your computer
2. Open `currency_converter_EUR_AUD.html` in your browser
3. Download the exchange rates CSV from [RBA](https://www.rba.gov.au/statistics/tables/csv/f11.1-data.csv)
4. Upload the CSV file in the converter
5. Enter the date and EUR amount to convert

## Features

- Uses official RBA exchange rates required by ATO
- Shows data range and last-modified date of loaded CSV
- Keyboard shortcuts for quick data entry
- Copy results directly for tax documentation
- Works offline after loading rates
- No installation needed - works in any modern browser

## License

MIT License. Copyright (c) 2024 Reiner Gaertner

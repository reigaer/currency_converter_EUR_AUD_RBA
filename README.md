# EUR to AUD Currency Converter

A simple web-based tool for converting EUR to AUD using official Reserve Bank of Australia (RBA) exchange rates. Created specifically for Australian Tax Office (ATO) tax reporting, where official RBA rates are required for currency conversion.

## Why This Tool?

When reporting foreign income to the ATO, you must use the official RBA exchange rates for currency conversion. This tool simplifies the process by using RBA's official historical rates, making it suitable for tax reporting purposes.

## Data Timing and Availability

- **Historical Data**: The RBA CSV file contains historical exchange rates from January 2023 onwards
- **Recent Rates**: For very recent transactions (last few days), you'll need to wait for the official RBA rates to be published
  - The ATO provides an XML feed for the most recent exchange rates (last few days)
  - For tax purposes, it's recommended to wait 2-3 business days after a transaction date before converting the amount
  - This ensures you're using the official published RBA rates rather than preliminary data

## Usage

1. Download `currency_converter_EUR_AUD.html` to your computer
2. Open `currency_converter_EUR_AUD.html` in your browser
3. Download the exchange rates CSV from [RBA](https://www.rba.gov.au/statistics/tables/csv/f11.1-data.csv)
4. Upload the CSV file in the converter
5. Select date and enter amount to convert

## Features

- Uses official RBA exchange rates required by ATO
- No installation needed - works in browser
- Supports historical conversions back to January 2023
- Works offline after loading rates
- No external dependencies except PapaParse

## Development

To improve the converter:
- Add backend proxy for auto-fetching rates
- Add rate history visualization
- Support more currencies
- Add data caching

## License

MIT License

Copyright (c) [year] [your name]

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

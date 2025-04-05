The code is for a Currency Converter Web App called "Blood Red Exchange" that allows users to convert between different currencies.

🔑 Key Features:
Input Fields:

Amount Input: User enters the amount to convert.

Currency Selectors: Choose the source and target currencies.

Buttons:

Convert: Fetches live exchange rates from the API and calculates the converted amount.

Swap Currencies: Switches the source and target currencies.

Real-Time Data:

Uses the ExchangeRate-API to fetch live currency rates.

Caching is implemented to reduce unnecessary API calls.

Error Handling:

Shows error messages for invalid inputs or API issues, disappearing after 3 seconds.

Styling:

Dark theme with red accents for a bold, dramatic look.

⚙️ How It Works:
When the page loads, it automatically converts 1 USD to EUR.

Clicking "Convert" triggers the app to fetch the latest exchange rates and display the result.

The "Swap" button switches the selected currencies and recalculates the conversion.

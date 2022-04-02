# Currency Conversion AlfredWorkflow

Currency conversion rates for 161 currencies.

## Requirements

Python3 is required, use [Homebrew](https://brew.sh/) to install Python3

## Usage

1. Get an api key from [https://www.exchangerate-api.com/](https://www.exchangerate-api.com/)
2. Fill the **api_key** value with the api key in the **Workflow Environment Variables**.
3. Run the workflow with the **cc** keyword: `cc 100 usd` or `cc 100usd`

Optional: You can change the **Workflow Environment Variables** to set what kind of currency you want to make a conversion.

**default_currency**

Your default currency.

**target_currency**

A comma separated list of currency codes.

## Supported Currencies

[https://www.exchangerate-api.com/docs/supported-currencies](https://www.exchangerate-api.com/supported-currencies)

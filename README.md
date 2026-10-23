# Stream Deck Gate.com Plugin
A Stream Deck plugin to follow crypto prices and keep track of your Gate.com portfolio assets (formerly Gate.io).

Requires Stream Deck 7.1 or later on macOS 12+ or Windows 10+. Works on keys and on Stream Deck + dials.

# How to install?
## Pre-requisite:
* Sign up for an account on **[Gate.com](https://www.gate.com/signup/7469390)**

## Get your Gate.com API Key (Portfolio Tracker only):
* Go to [Gate.com API Management](https://www.gate.com/myaccount/apiv4keys?ref=7469390)
* Create a new API v4 key and give it a name
* Give it **Read Only** permission for Spot (and for Unified Account, if you use it)
* Do not enable trading or withdrawals: the plugin only reads balances. Restricting the key to your IP address is safer.
* Save the Key and Secret in a safe place and do not share them with anyone.

## Assign an action to a Stream Deck key:
* Install the plugin from the Elgato Marketplace
* In the sidebar, find the "Gate.com" category and expand it if needed
* Drag and drop the desired action onto an empty key (or a dial on Stream Deck +). Its settings appear at the bottom of the window.
* For the Portfolio Tracker, enter your API Key and Secret Key under "Gate.com API key". They are shared by all Portfolio keys.
* Pick a pair or a currency
* Voilà, have fun!


# How does it work?
## Gate.com ticker (Spot)

### Setup
Pick a pair in the dropdown to display its information.

This action will display the following information:
* Selected pair
* The latest price
* The percentage change over the past 24 hours

## Portfolio Tracker (Spot)
### Pre-requisite:
* [API Key & Secret are added](#get-your-gatecom-api-key-portfolio-tracker-only) in the action settings

### Setup
In the *Currency* dropdown menu, select one of the assets you hold. Spot and Unified Accounts are both supported.

This action will display the following information:
* Selected asset
* Its value in USDT
* The percentage change over the past 24 hours
* The total quantity you hold

## Refresh
Both actions refresh every minute. Press the key (or press or tap the dial) to refresh it right away.

If something goes wrong, the key says so: "Set API key", "Check API key", "Rate limited", "Offline" or "Unknown pair".


# How to uninstall?

In the sidebar, right-click on one of the actions and click "Uninstall..."


# Bug & Feature Request

If you encounter a bug, have a feature request or question, please create a new issue in this repository: https://github.com/StephaneTurquay/streamdeck-gateio/issues

# Changelog
## 2.0.0 - Gate.com and Stream Deck +
* Updated to the Gate.com name and logo
* Rebuilt on the latest Stream Deck SDK (needs Stream Deck 7.1 or later)
* Stream Deck + support: prices and balances on the dials, press or tap to refresh
* Portfolio now works with Unified Accounts
* Portfolio fixes: USDT balance, sold assets show 0, values shown in USDT
* Smoother refresh when Gate's API is busy

## 1.1.0 - Latest ticker prices
**Action: Gate.io Ticker (Spot)**
* Select one of the pairs available on Gate.io
* Auto-refresh every minute
* Press on the key to manually refresh

## 1.0.0 - Initial release
**Action: Portfolio Tracker (Spot)**
* Select one of the assets available on the spot account to display its total amount in USDT, 24-hour percentage change and the total quantity held.
* Auto-refresh every minute
* Press on the key to manually refresh

# Buy me a coffee
If you feel like supporting the development of this plugin, I accept donations. Thank you 🙏

BTC: `bc1qn0stst7cnvau09vs4gh7puv5cp4grwx5vx07z7`

ETH: `0xde092e7E607CdD3aFE0D3FBeC81Fb24AbD4139F9` 

BNB: `0xde092e7E607CdD3aFE0D3FBeC81Fb24AbD4139F9`

MATIC: `0xde092e7E607CdD3aFE0D3FBeC81Fb24AbD4139F9`

# Streamdeck Gate.io Plugin 
A Stream Deck plugin to keep track of your Gate.io's portfolio.
# How to install?
## Pre-requisite:
* Sign-up an account on **[Gate.io](https://www.gate.io/signup/7469390)**

## Get your Gate.io's API Key:
* Go to [https://www.gate.io/myaccount/apiv4keys](https://www.gate.io/myaccount/apiv4keys?ref=7469390)
* Click "**Create New API Key**" which will open a modal
* Add the name in the "**Remark**" field
* Check "**Spot/Margin Trade**" checkbox
* Select "**Read Only**" under "Spot/Margin Trade"
* Click "**Confirm & Create**"
* Enter your Fund Password and Complete the Two-Factor Authentication (2FA)
* A modal will appear with your Key and Secret. Save them in a safe place and do not share it with anyone.

## Assign an action to a Streamdeck key:
* Install Gate.io plugin from the Streamdeck store
* From the sidebar, find "Gate.io" category and expand it, if not already the case, by clicking on chevron
* Drag & drop, the desired action on an empty key. At the bottom of the main panel, the settings of the action will appear.
* In the "GATE.IO SETTINGS" section, enter your API Key and Secret in the respective fields
* Select the settings you desire for this action
* Voilà, have fun!


# How it works?
## Portfolio Tracker (Spot)
### Pre-requisite:
* [API Key & Secret are added](#get-your-gateios-api-key) to the "*GATE.IO SETTINGS*" section

### Setup
In the *Currency* dropdown menu, select one of the assets available in the spot account.

This action will display the following information:
* Selected asset
* The USD amount of this asset the spot account owns
* The percentage change over the past 24 hours
* The total quantity of this asset in the spot account

### Auto-Refresh

The data will be refreshed every minute unless an error occured. If so, the key will show you the Gate.io logo.

### Manual refresh

Click on the key to trigger a manual refresh of the corresponding asset.


# How to uninstall?

In the sidebar, right-click on one of the actions available and click "Uninstall..."


# Changelog
# Bug & Feature Request

If you encounter a bug, have a feature request or question, please create a new issue in this repository: https://github.com/StephaneTurquay/streamdeck-gateio/issues


# Web3 Whitelist Chrome Extension

![Project Logo]<img src="logo.png" width="513" height="207">

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
  - [Popup UI](#popup-ui)
  - [Background Script](#background-script)
- [Screenshots](#screenshots)
- [Technologies Used](#technologies-used)
- [Contributing](#contributing)
- [FAQs](#faqs)
- [Changelog](#changelog)
- [License](#license)
- [Contact/Support](#contactsupport)
- [Donations](#donations)

## Introduction

Navigating the web3 ecosystem, including decentralized finance (DeFi), wallet interfaces, and NFT marketplaces, poses security risks from malicious sites. The Web3 Whitelist Chrome Extension addresses these challenges. It restricts browser access to a predefined list of trusted domains, reducing exposure to phishing and scams. Leveraging Chrome's declarative net request API, the extension ensures only whitelisted domains are accessible. Moreover, the extension is completely free to use.

## Features

- **Domain Whitelisting**: Only allows access to a predefined list of trusted domains.
- **Background Initialization**: Loads a fixed whitelist from `fixed_whitelist.txt` upon installation.
- **Toggle Safe Browsing**: Switch between safe and unrestricted browsing from the popup UI.
- **Whitelist Management**: Add or remove domains from the whitelist directly from the popup.
- **Bulk Upload**: Ability to bulk add domains to the whitelist from a file.
- **Display Extension Version**: Shows the current version within the popup.
- **Last Updated**: Displays the last modification date of the fixed whitelist.

## Installation

To install the Whitelist Chrome extension, follow these steps:

1. Navigate to `chrome://extensions/` in your Chrome browser.
2. Enable `Developer mode` by toggling the switch in the top right corner.
3. Click on `Load unpacked` and select the folder containing the Whitelist extension files.

## Usage

### Popup UI

- **Toggle Safe Browsing**: A slider for switching between "Safe Browsing" and "Unrestricted Browsing".
- **Add Custom Domain**: Enter any website or domain into the text field.
- **Add Current Domain**: A button to directly add the active tab's domain to the whitelist.
- **Bulk Upload**: Upload a list of domains from a file to the whitelist.
- **Whitelist Management**: View, add, or remove domains from the whitelist.

### Background Script

- **Initialization**: Sets up a fixed whitelist from `fixed_whitelist.txt` upon installation.
- **Update Rules**: Merges the fixed whitelist and user-defined whitelist, then updates the browsing rules accordingly.
- **Communication with Popup**: Listens to messages from the popup, primarily for updating rules and fetching results.

## Screenshots

![Screenshot1](/screenshot1.png)
![Screenshot2](/screenshot2.png)

## Technologies Used

- JavaScript
- HTML
- CSS

## Contributing

To contribute, please send domain suggestions for inclusion, report any bugs you encounter, or provide feedback on the extension's functionality. Your input helps improve the tool for everyone.

## Changelog

- **0.2.7** - [Description of the changes in version 0.2.7]

## License

The Web3 Whitelist Chrome Extension is licensed under the MIT License. The MIT License is a permissive free software license that allows for reuse within proprietary software provided all copies of the licensed software include a copy of the MIT License terms. Such open-source software is free to use, modify, and distribute, subject to conditions preserving the copyright notice and disclaimer.

## Contact/Support

For inquiries or support, contact: [dorian.band1@gmail.com](mailto:dorian.band1@gmail.com).

## Donations

Support the development by making a donation to `dorianb.eth`. Your support is greatly appreciated!


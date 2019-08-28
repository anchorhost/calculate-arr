<h1><a href="https://github.com/anchorhost/calculate-arr">Calculate ARR</a></h1>

Is your Annual Recurring Revenue (ARR) business healthy? Calculate profitability based on past income and projected expenses. See [Anchor Hosting's public Calculate ARR](https://anchor.host/calculate-arr/). Running Calculate ARR for your business? Add a link to this repo. Pull requests welcomed.

[![emoji-log](https://cdn.rawgit.com/ahmadawais/stuff/ca97874/emoji-log/flat.svg)](https://github.com/ahmadawais/Emoji-Log/)

## Screenshot

![Screenshot](https://github.com/anchorhost/calculate-arr/raw/master/screenshot.png)

## Why this was built.
Baremetrics is amazing however quite pricey for small businesses and doesn't really help with the complexity of annual revenue. Running an ARR business is a cashflow challenge. This was created so that I could be more intention with my business budget and less attached to Google Spreadsheets for forecasting profits and losses. Think YNAB meets Baremetrics but for futurecasting. How it works is simple. The setup:

- Download a copy of Calculate ARR and upload to any web server that supports .html files. See [installations instructions](#Installation) below.
- Calculate your total revenue for the last 12 months.
- Add all recurring business expenses.

Once a month do the following:

- Duplicate most recent version (your budget) and update date range/revenue numbers.
- Add or adjust any new expenses.
- Export and update your `data.json` file.

## Installation

1. Download latest release from [https://github.com/anchorhost/calculate-arr](https://github.com/anchorhost/calculate-arr).
2. Upload folder `/calculate-arr/` to any web server via SFTP.
3. Access your site at `/calculate-arr/` and select `Edit Mode` to begin entering your information.

## Data storage

This is a very simple `.html` file. That means no data change will persist without manually effort. Whenever changes have been made you'll need to export a fresh `data.json` and override the existing one. 

## Backup

Copy your `data.json` anywhere and everywhere you wish. That's all you need. When restoring simply grab a copy of the latest `calculate-arr/index.html` from Github.

## Upgrading

This couldn't be easier. Simply update `index.html` from latest release `calculate-arr`. Be sure to never override your `data.json` with the sample `data.json` file.

## Used by

- [Anchor Hosting](https://anchor.host/calculate-arr/)
# Centre Ecosystem Tracker

The goal of this repository is to track the ecosystem of exchanges, wallets, protocols, platforms, applications and services that support [Centre](https://www.centre.io/) fiat tokens, most importantly [USD Coin (USDC)](https://www.centre.io/usdc).

To add an exchange, wallet, protocol, platform, application or service, propose a PR including:

### 1. Entry to an `ecosystem.json` file

Entries should be added to the file in the appropriate currency (e.g. `usdc`) and blockchain (e.g. `ethereum`) path.

An example entry is shown below:

```
{
  "id": "circle",
  "name": "Circle",
  "category": "service",
  "url": "https://www.circle.com",
  "logo": "circle.png",
  "description": "Circle is the best platform to run an internet business using new standards for money powered by USD Coin (USDC)."
}
```

Valid categories include: `exchange`, `wallet`, `platform`, `protocol`, `application`, `service`. If you want to propose a new category, please explain why on your PR.

If your item supports a currency (e.g. [USDC](https://www.centre.io/usdc)) on multiple blockchains, please add one entry on each appropriate `ecosystem.json` file.

If your item spans across multiple categories (e.g. `exchange` and `wallet`), add one entry per category and consider using more specific values for `url` and `description`.

### 2. High resolution logo file

A high resolution logo file with transparent background should be uploaded to the `logos`folder, and its name should be the `logo` value on the json entry.


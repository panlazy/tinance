<p align="center">
  <img src="https://i.imgur.com/iMxSX2r.png" alt="tinance-logo">
</p>

> CLI tool made by cryptohead for cryptoheads. Also an Arch user. 🤯

- Check cryptocurrency prices from your terminal! 💰
- Price data is provided by [Coincap](https://coincap.io/)'s public API. ✌
- It will auto refresh the data every 5 minutes.

## Install

- Install it with npm.

```bash
❯ npm install -g tinance
```

- For now I only published the package to `npm`. Publishing to `Aur`, `Flatpak` and releasing as `.deb`, `.rpm` is in my roadmap. Soon ™️.

## Usage

- Use with default parameters. (USD, Top 20 currencies)

```bash
❯ tinance
```

- Options

```bash
❯ tinance --top 30 // Get top 30
❯ tinance --currency // Convert to your prefered currency like 'EUR'
```

- Show help text

```bash
❯ tinance --help
```

- Valid currencies to convert price
  - USD
  - AUD
  - BRL
  - CAD
  - CHF
  - CLP
  - CNY
  - CZK
  - DKK
  - EUR
  - GBP
  - HKD
  - HUF
  - IDR
  - ILS
  - INR
  - JPY
  - KRW
  - MXN
  - MYR
  - NOK
  - NZD
  - PHP
  - PKR
  - PLN
  - RUB
  - SEK
  - SGD
  - THB
  - TRY
  - TWD
  - ZAR
  - BTC

## Contribution

- Please use ES6 syntax, we are using babel and prettier. Any PR is welcome.

## License

This project is under the [GPLv3](LICENSE.md) license.
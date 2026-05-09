# EnergyBe — Public Repository

This repository hosts the public-facing resources for **EnergyBe**, a free iOS app 
that visualises electricity and gas consumption from Fluvius smart meters for Belgian households.

The app source code is kept in a private repository. This repo is the place for:

- 🐛 [Bug reports and feature requests](https://github.com/eelcoder/energybe-public/issues)
- 📄 [Support page](https://eelcoder.github.io/energybe-public/support.html)
- 🔒 [Privacy policy](https://eelcoder.github.io/energybe-public/privacy.html)
- 📦 Release notes (see [Releases](https://github.com/eelcoder/energybe-public/releases))

---

## About EnergyBe

EnergyBe connects to your [mijn.fluvius.be](https://mijn.fluvius.be) account and displays 
your smart meter data in a clean, native iOS interface.

**Key features**
- Electricity and gas consumption across daily, weekly, monthly, and yearly views
- End-of-period forecast based on your current pace
- Smart insights: peak hours, tariff split, weekday/weekend patterns, temperature correlation
- City and Flanders benchmark comparison via Fluvius open data
- Cost view using your own tariff rates
- Home Screen widget
- Face ID / Touch ID lock
- Demo mode — no Fluvius account required to explore

**Requirements:** iPhone running iOS 17 or later. A digital Fluvius smart meter in Flanders.

---

## Reporting a bug

Please use the [bug report template](https://github.com/eelcoder/energybe-public/issues/new?template=bug_report.md) 
and include your iOS version, energy type, and which screen or granularity is affected.

---

## Privacy

EnergyBe has no backend server. Your credentials and meter data never leave your device, 
except for the authenticated requests to `login.fluvius.be` and `mijn.fluvius.be`.  
Full details in the [Privacy Policy](https://eelcoder.github.io/energybe-public/privacy.html).

---

*EnergyBe is a free, non-commercial app. It is not affiliated with or endorsed by Fluvius.*

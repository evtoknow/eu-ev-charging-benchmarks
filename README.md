# 2026 European EV Charging Cost Benchmarks (`PT` · `ES` · `FR` · `DE`)

Open reference dataset comparing **overnight off-peak home charging**, **evening peak home charging**, **public DC fast charging**, and **petrol equivalents** across major European electricity markets.

Computed using real vehicle battery capacities, onboard AC charger limits, charging efficiency losses, and 2026 regional retail tariff structures (wholesale day-ahead spot + regulated grid access fees + local VAT).

> **Interactive tools & live day-ahead ENTSO-E spot windows:** [evtoknow.eu](https://evtoknow.eu) · [Smart Charging & Spot Prices](https://evtoknow.eu/smart-charge) · [EV Cost Calculator](https://evtoknow.eu/calculator)

---

## 1. Retail Electricity Tariff Benchmarks (2026 Typical Day)

| Market | Tariff Structure & Taxes Included | Overnight Off-Peak (`02:00–06:00`) | Evening Peak (`18:00–22:00`) | Peak vs. Off-Peak Spread | Full Reference Data |
| :--- | :--- | :---: | :---: | :---: | :--- |
| **Portugal (`PT`)** | OMIE day-ahead + regulated TAR + 23% IVA | **€0.222 / kWh** | €0.341 / kWh | +53.6% | [Portugal EV Charging Guide](https://evtoknow.eu/pt-pt/) |
| **Spain (`ES`)** | PVPC / OMIE + regulated Peajes + 21% IVA | **€0.182 / kWh** | €0.299 / kWh | +64.3% | [Spain EV Charging Guide](https://evtoknow.eu/) |
| **France (`FR`)** | Indexed / Heures Creuses + TURPE + taxes | **€0.205 / kWh** | €0.320 / kWh | +56.1% | [France EV Charging Guide](https://evtoknow.eu/fr/) |
| **Germany (`DE`)** | EPEX Spot + Netzentgelte + levies + 19% MwSt | **€0.316 / kWh** | €0.431 / kWh | +36.4% | [Germany EV Charging Guide](https://evtoknow.eu/) |

---

## 2. Full-Charge Session & Cost per 100 km Benchmarks

| Market | Benchmark Vehicle | Home Off-Peak Full Charge | Public DC vs. Petrol (`€/100 km`) |
| :--- | :--- | :---: | :--- |
| **Portugal (`PT`)** | Volkswagen ID.4 | **€11.81** | **€2.44 / 100 km** (Home off-peak benchmark) |
| **Spain (`ES`)** | Kia EV6 | **€11.61** | €10.74 / 100 km (Public DC) vs. €9.80 / 100 km (Petrol) |
| **France (`FR`)** | Renault Mégane E-Tech | **€11.27** | Home off-peak *Heures Creuses* benchmark |
| **Germany (`DE`)** | Volkswagen ID.4 | **€18.40** | €11.70 / 100 km (Public DC) vs. €11.04 / 100 km (Petrol) |

---

## 3. Solar + EV Self-Consumption Benchmark

- **5 kWp Residential Solar Array (Southern/Western Europe):** Generates approximately **+18 km/day** of EV driving range when charging during peak daytime solar hours (`15,000 km/year` reference profile with 50% daytime plug-in availability).
- Full sizing breakdown (`1–7 kWp`): [How Many Solar Panels to Charge an EV?](https://evtoknow.eu/)

---

## Methodology & Data Sources

- **Wholesale Day-Ahead Prices:** ENTSO-E Transparency Platform (`A44` Day-Ahead Market Coupling auctions).
- **Vehicle & Charging Physics:** Pack usable capacity, AC/DC onboard rectifier limits, and wall-to-wheel conversion efficiency modeled per trim at [evtoknow.eu/methodology](https://evtoknow.eu/methodology).
- **Localized Hubs:** [English](https://evtoknow.eu/guides) · [Français](https://evtoknow.eu/fr/) · [Português (PT)](https://evtoknow.eu/pt-pt/) · [Português (BR)](https://evtoknow.eu/pt-br)

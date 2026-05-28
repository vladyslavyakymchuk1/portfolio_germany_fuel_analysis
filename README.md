# Fuel Price Analysis — Germany & Bavaria
**December 2025 | Python, pandas, Tableau | Data: Tankerkönig API**

An analysis of real-world fuel price data across Germany, with a dedicated deep-dive into Bavaria. The goal was to find patterns in pricing — by time of day, day of month, region, and fuel brand — that could help drivers make smarter refuelling decisions.

---

## Key Findings

**Best time to refuel:** Prices are lowest between **5–9 PM** across all fuel types. Peak prices occur at **6–7 AM**. The difference is up to **€0.10/litre** — worth knowing if you fill a full tank.

**Monthly pattern:** Prices dip toward **Christmas Eve (Dec 24)** and rise again in the final week of December. A brief spike occurs around **December 8**.

**Regional differences:** Western German states (Rheinland-Pfalz, NRW) are consistently **~5 cents/litre cheaper** than eastern states (Brandenburg, Sachsen) for diesel.

**Brand comparison (Bavaria):** ENI and Aral are consistently the most expensive brands. Independent and discount stations (Sprint, ALLGUTH, Raiffeisen) are significantly cheaper — up to **€0.15/litre difference**.

**E5 vs E10:** E5 is always **3–4% more expensive** than E10 in the same region and station.

**Bavaria vs Germany:** Bavaria follows the national trend almost exactly, with slightly smoother daily fluctuations.

---

## Project Structure

```
├── tankkoenig-prices-cleaning.ipynb      # Data collection & cleaning
├── tankkoenig-stations-cleaning.ipynb    # Station metadata cleaning
├── Analysis of fuel prices in Germany.pdf  # Full report — Germany
├── Analysis of fuel prices in Bayern.pdf   # Full report — Bavaria
└── README.md
```

---

## Tools & Methods

- **Python** (pandas, NumPy) — data cleaning, aggregation, transformation
- **Tableau** — choropleth maps, time series charts, bar charts
- **Tankerkönig API** — real-time German fuel price data (MTS-K)
- Analysis covers ~15,000+ stations across all 16 German federal states

---

## Data Source & License

Data provided by [Tankerkönig UG](https://tankerkoenig.de) via their public API, based on data from the German Market Transparency Unit for Fuels (MTS-K).

Licensed under [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Project is non-commercial and for portfolio purposes only. No raw data is redistributed.

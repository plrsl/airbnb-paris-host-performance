# 🏠 Airbnb Paris: why do some hosts rent more than others?

Looker Studio dashboard analysing 500 Paris listings (Sept 2022 – Jan 2023) to find which levers drive host occupancy.

**🔗 [Open the interactive dashboard](https://datastudio.google.com/reporting/fbbae5e4-2b9f-41ba-97b4-ce87e5fced40)**

![Dashboard overview](images/01_overview.png)

## Key findings

| Lever | Effect on occupancy | |
|---|---|---|
| 💶 Price | 81% under 120 € vs 67% above 180 € | 🥇 Main lever |
| ⭐ Rating | ≈ 69% below 4.58 vs ≈ 80% from 4.7, then plateaus | 🥈 Strong, with a ceiling |
| ⚡ Response time | ≈ 78% within an hour vs ≈ 73% beyond | 🥉 Small effect |
| 📅 Weekends / holidays | +1 pt on weekends; prices flat except at Christmas | ❌ Not a driver |

**Recommendation:** price competitively, aim for a rating of 4.7 or more, reply within the hour, and adjust prices for weekends and holidays.

## Dashboard

| Timing | Price |
|---|---|
| ![](images/02_timing.png) | ![](images/03_price.png) |
| **Ratings & responsiveness** | |
| ![](images/04_ratings.png) | |

## Data & method

- **Source:** Inside Airbnb, Paris *(⚠️ to confirm)*. 500 listings, 90% entire homes
- **Occupancy** = share of nights unavailable in the calendar *(⚠️ adapt to your method)*
- **Tools:** Looker Studio *(⚠️ + Sheets / SQL / Python if used)*

**Limitations:** unavailable nights include host-blocked nights; small sample (49 private rooms); correlation, not causation.

---
**YOUR NAME**, MSc Data Management for Business × Le Wagon · [LinkedIn](LINK)

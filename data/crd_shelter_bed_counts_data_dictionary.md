# 📄 Data Dictionary: `crd_shelter_bed_counts.csv`

This file contains shelter bed availability and population estimates for communities in the Capital Regional District (CRD) for 2024.

---

## 🧾 Fields

| Column Name               | Data Type       | Description                                                                 |
|---------------------------|------------------|-----------------------------------------------------------------------------|
| `category`                | String           | A community is categorized as a municipality or an electoral area. |
| `community`               | String           | The name of the municipality or electoral area. |
| `pop_est_2024`            | Integer          | Estimated population of the community in 2024 (see [data sources](https://github.com/bcdatavis/crd-shelter-beds/blob/main/data-sources.md)).                             |
| `shelter_count`           | Integer          | Number of shelters (unique physical addresses) of unhoused people counted in a community.                      |
| `beds_yr_rnd_all`         | Integer          | Total number of year-round shelter beds.            |
| `beds_yr_rnd_men`         | Integer          | Number of year-round shelter beds specifically for men.                                      |
| `beds_yr_rnd_women`       | Integer          | Number of year-round shelter beds specifically for women.                                    |
| `beds_yr_rnd_youth`       | Integer          | Number of year-round shelter beds specifically for youth.                                    |
| `beds_extr_wthr`          | Integer          | Number of shelter beds available during extreme weather conditions. |
| `beds_drop_in`            | Integer          | Number of drop-in shelter beds.   |
| `beds_temp`               | Integer          | Number of temporary shelter beds.        |
| `beds_total`              | Integer          | Total number of beds available across all categories.  |
| `beds_per_1000_residents` | Float  | Number of shelter beds per 1,000 residents. Calculated as:<br>`(beds_total / pop_est_2024) * 1000`. |

---

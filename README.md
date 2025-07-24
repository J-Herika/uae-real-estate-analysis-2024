**Title**
`UAE Real Estate Data Analysis – 2024 Listings`

---

**Overview**
This project analyzes real estate listings in the UAE for 2024 using Python and Pandas. The dataset includes price, property type, furnishing, verification status, and other listing features. The goal was to clean, process, and extract key business metrics for potential use in dashboards or reporting tools.

---

**Dataset Fields**

* `title`: Listing headline
* `displayAddress`: Property location
* `bathrooms`, `bedrooms`: Property specs
* `addedOn`: Listing date
* `type`: Property category
* `price`: Price in AED
* `verified`: Verification status
* `priceDuration`: Sale or rent
* `sizeMin`: Size in sq ft
* `furnishing`: Furnishing status
* `description`: Listing details

---

**Processing Steps**

1. Loaded dataset with `pandas.read_csv()`
2. Renamed columns to lowercase and snake\_case
3. Dropped rows with missing values in critical columns (`price`, `bedrooms`, `bathrooms`)
4. Parsed basic statistics with `describe()`
5. Aggregated key metrics:

   * Average price by property type
   * Listing count by furnishing status
   * Verified vs unverified distribution

---

**Key Metrics Extracted**

* `avg_price_by_type`: Mean price grouped by property type
* `verified_counts`: Verified vs unverified listings
* `furnishing_counts`: Distribution of furnishing states
* Optional: trends by `addedOn` date if converted to datetime

---

**Outputs**

* Cleaned CSV: `cleaned_uae_real_estate_2024.csv`
* Jupyter notebook: `retail_sales_clean.ipynb`
* Sample screenshots included in `/screenshots` folder

---

**Next Step**
Dataset is now ready for Power BI or SQL import for further dashboard creation.

---

**Add These Files to Your Repo**

* `README.md`
* `retail_sales_clean.ipynb`
* `cleaned_uae_real_estate_2024.csv`
* 2–3 PNGs in `/screenshots` (from notebook output)

Once committed and pushed, reply: `Week 1 done`.

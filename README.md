# iPhone Sales Analytics Project | Python Project

Objective: To build a Python analytics system to decode India e-commerce iPhone pricing and demand.

I developed a Pandas + Matplotlib/Seaborn EDA notebook that cleans India-denominated prices (₹), engineers Price Bands & Rating Bands, and produces KPI tiles, Top-N charts, and a correlation heatmap to inform pricing and merchandising decisions. segmenting SKUs into Budget (<₹40K), Mid (₹40K–₹80K), and Premium (>₹80K); quantifying how discounts, ratings, and reviews interact with sale price (₹); and surfacing promotion-ready insights to guide pricing thresholds, assortment mix, and campaign ROI for the India market.

Key Insights:
• Price segmentation for India: Budget <₹40K, Mid ₹40K–₹80K, Premium >₹80K (used across visuals/KPIs).
• Top costliest SKUs peak near ₹1.5L — e.g., iPhone 11 (128 GB Silver) ~₹150,000, iPhone 11 Pro (64 GB Silver) ~₹149,906, iPhone 13 (1 TB Purple) ~₹149,831 — validating a clear premium tier.
• Top-N by reviews and average rating by price band highlight which models earn trust without heavy discounting vs. those relying on deeper markdowns.
• Correlation heatmap explores relationships among Sale Price (₹), Discount %, Ratings count, and Star rating to probe price–trust–promotion dynamics.
• Mini KPI dashboard summarizes band mix (count), avg. discount by segment, and avg. rating by segment—quickly showing where promotions are most efficient.

Tools & Techniques Used:
• Python: Pandas, NumPy, Matplotlib, Seaborn
• Data Cleaning: Parsed ₹ prices, removed commas/symbols, coerced numerics, handled nulls
• Feature Engineering: Price Band (<₹40K / ₹40K–₹80K / >₹80K), Rating Band buckets
• Analysis & Viz: Groupby Top-N (price & reviews), correlation heatmap, band-wise KPIs, labeled bar/line charts.

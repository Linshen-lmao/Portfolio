# Data Scientist Portfolio
Focused on bridging statistical rigor with scalable, domain-specific solutions


### Education
**B.S. in Data Science**
*Expected Graduation: June 2027*
- Relevant Coursework: High-Dimensional Statistics, Distributed Systems for Data, Applied Machine Learning in Genomics


### Project Experience
#### 1. Australian Rainfall Probability Forecasting
*Sole Contributor | Meteorology & Climate Analytics*
- Processed 10+ years of hourly meteorological data (temperature, humidity, wind speed) across 50+ Australian weather stations, cleaning 15% of missing/inconsistent records via time-series imputation.
- Built **Random Forest & XGBoost classifiers** to predict 7-day rainfall probability; optimized feature interactions (e.g., "humidity × pressure gradient") to boost F1-score by 12% (from 0.68 to 0.76).
- Visualized regional forecast accuracy via interactive heatmaps (Tableau), highlighting 3 coastal regions where model performance exceeded local meteorological benchmarks.


#### 2. Distributed Transaction Data System for Supermarket Alliance
*Core Team (3 Members) | Retail Data Infrastructure*
- Designed a **distributed computing architecture** (Spark + Kafka) to ingest real-time transaction data (10k+ records/second) from 20+ retail locations, reducing data latency by 40% vs. the legacy centralized system.
- Implemented data partitioning logic to ensure scalability; tested system resilience via 5x load spikes (simulated holiday traffic) with 0 downtime.
- Collaborated with retail analysts to define 12 core metrics (e.g., "hourly sales per product category") for the system’s real-time dashboard.


#### 3. Genomic Driver Gene Identification for Cancer Subtypes
*Independent Research Project | Bioinformatics*
- Analyzed **10k+ gene expression features** (ultra-high dimensional dataset) from 200+ patient samples across 3 cancer subtypes.
- Applied **LASSO & SCAD variable selection** to narrow down 120+ candidate driver genes; validated 8 top genes via literature cross-reference (matched 6/8 with existing oncogenomics studies).
- Used R (glmnet + ggplot2) to generate subtype-specific gene correlation networks, identifying 2 novel co-expression clusters linked to patient survival rates.


### Technical & Domain Skills
- **Coding & Tools**: Python (Pandas/Scikit-learn/XGBoost), R (glmnet/lme4), SQL (PostgreSQL), Java (Kafka), Spark, Tableau
- **Specializations**: High-dimensional statistical modeling, distributed data system design, machine learning for structured/unstructured domain data

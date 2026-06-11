📌 Project Title
Holistic Mortgage Default Risk Analysis: Uncovering Strategic Defaulters & Risk Paradoxes

📖 Project Summary
This project analyzes 420,436 Fannie Mae mortgage records to identify key drivers of default risk and empirically validate the phenomenon of "Strategic Default"—where affluent borrowers intentionally walk away from their loans as a calculated business decision. By implementing a rigorous data engineering pipeline and multivariate modeling, this study uncovers critical risk paradoxes and provides proactive mitigation strategies for institutional lenders.

🛠️ Data Engineering & Preprocessing
Feature Pruning: Removed 38 out of 75 factors that were more than 50% empty to ensure data quality.

Robust Imputation: Handled missing data via Median Imputation instead of averages to prevent outlier distortion.

Multicollinearity Control: Excluded Property Value to avoid double-counting risk signals already captured by CLTV.

The "Data Diet" (Class Imbalance): Balanced the massive gap between Defaulters (1,656) and Non-Defaulters (416,752) by strategically downsampling the majority class to 30,000 records for an unbiased model training.

📊 Core Insights & Analytics
The Vetting & Term Paradox: Higher interest rates and longer loan terms correlate with lower default risk, proving that rigorous lender screening for high-rate loans is effective and extended terms provide financial flexibility.

The CLTV Paradox: Higher Combined Loan-to-Value reduces risk, driven by financially sophisticated borrowers utilizing leverage for premium properties while prioritizing asset preservation.

The Joint Application Myth: Having two borrowers significantly increases default risk compared to single applicants, rendering households twice as vulnerable to macroeconomic shocks under heavier debt burdens.

Strategic Default in Cash-Out Segments: Borrowers utilizing Cash-Out refinancing are statistically prone to strategic default; having already extracted immediate liquidity, they choose to walk away when property equity drops, regardless of their ability to pay.

💡 Strategic Recommendations
Holistic Risk Scoring: Move away from isolated metrics (like credit scores alone) and evaluate how risk factors compound (e.g., credit score vs. large loan size).

Proactive Loan Modification: Implement early-warning systems to track equity declines and offer timely renegotiation pathways, which serves as the strongest deterrent to default.

Targeted Cash-Out Monitoring: Deploy specific intervention pipelines for Cash-Out segments to preemptively mitigate portfolio instability.

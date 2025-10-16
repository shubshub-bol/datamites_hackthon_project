# datamites_hackthon_project
Problem Statement – Predicting Female Foeticide Risk

🔹 Context

Female foeticide, though illegal, remains a concern in several parts of India due to deep-rooted social biases and economic pressure on families. Predicting regions at high risk helps NGOs and state governments channel welfare programs—scholarships, maternal care, education schemes—where they are most needed.

🔹 Objective

Build a machine-learning model to predict the level of female foeticide risk (Low / Medium / High) for a district or town, using socio-economic and demographic indicators. Analyse the feature importance to identify main causes (poverty, literacy gap, etc.).

🔹 ML Problem Type

Multi-class classification

🔹 Dataset Metadata

Column

Data Type

Description

district_name

string

Indian district / town name

state

string

State the district belongs to

literacy_rate_female

float

% of literate females

literacy_rate_male

float

% of literate males

sex_ratio

integer

Females per 1000 males

avg_household_income

integer

Average monthly household income (₹)

poverty_index

float (0–1)

Normalized poverty indicator

education_expenditure_per_capita

float

Annual education expenditure per person (₹)

female_infant_mortality_rate

float

Infant deaths per 1000 female births

access_to_health_facilities

float

% households with health facilities within 5 km

employment_rate_female

float

% of employable women actually employed

social_awareness_programs

integer

Number of government/NGO programs running in that district

risk_level

categorical target

“Low”, “Medium”, or “High” foeticide risk

🔹 Evaluation Metric

Macro-F1 score or weighted accuracy for imbalanced class handling.
🔹 Expected Output

For each district, output the predicted risk_level.

🔹 Social Impact

A data-driven map of risk levels guides state welfare targeting, especially in rural India.


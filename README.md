# EDA_onIndianAgricultureProduction


# **Project Title: EDA on Indian Agriculture Production**

# **🎯 Objective:**
The primary objective of the Project is to perform Exploratory Data Analysis (EDA) on the Indian Agriculture Production dataset to:

Understand patterns and trends in crop production across Indian states and seasons.

Identify the highest producing crops and regions.

Analyze the impact of crop category, area under cultivation, and seasonal factors.

Generate visual and statistical insights for potential policy-making or agritech solutions.


# **Dataset Overview :**

**Dataset Name:** crop_production.csv

**Shape of Dataset:** Rows = 246091, Columns = 7

# **Features :**

**State_Name :**	Name of the Indian state where the crop is cultivated \\
**District_Name :**	District within the state \\
**Crop_Year	:** Year of crop production \\
**Season :**	Season in which the crop was grown (e.g., Kharif, Rabi) \\
**Crop :**	Name of the crop \\
**Area :**	Area under cultivation (in hectares) \\
**Production :**	Amount of crop produced (in tonnes or applicable units)
# **Null Values Handling :**
Only the Production column had null values. \\
Removed nulls via interpolation
Sorted the dataset by Crop_Year and applied linear interpolation on the Production column to estimate missing values based on surrounding data.

# **Feature Engineering :**
**🔹 Zones :**
Created a new column Zones to divide Indian states into:
North, South, East, West, Central, NE, and Union Territories.

**🔹 Crop Categories :**
Introduced crop_category column to classify crops into:
Cereal, Pulses, Fruits, Vegetables, Oilseeds, Spices, Fibres, Nuts, Commercial, and Other.



# **Key Analytical Insights Aimed for Extraction :**

🔹 Which Indian state leads in overall agricultural production?

🔹 Which state has the largest area under crop cultivation?

🔹 What is the highest-produced crop in each state?

🔹 Which state produces the maximum amount of each specific crop?

🔹 Which geographical zone contributes the most to India's crop production?

🔹 Which crops are the top three in terms of total production across the country?

🔹 In which years did India see peak crop production levels?

🔹 Which season contributes the most to crop production in India?

🔹 Which crop categories (e.g., Cereals, Pulses, Oilseeds) dominate in production volume?


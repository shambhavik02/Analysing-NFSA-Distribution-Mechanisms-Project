# Analysing-NFSA-Distribution-Mechanisms-Project
1.Introduction
This project focuses on analyzing the distribution mechanisms of the National Food
Security Act (NFSA), a major public welfare initiative in India aimed at providing
subsidized food grains to approximately two-thirds of the country's population. The dataset
explores various operational aspects and objectives related to NFSA, including distribution
efficiency, regional disparities, beneficiary coverage, and delivery performance. By
evaluating the data across multiple objectives, the analysis aims to uncover patterns, gaps,
and potential improvements in the food distribution system under NFSA.
2. Source of dataset
 Based on the content and structure, the dataset appears to be compiled from multiple
NFSA-related records, likely gathered from various government portals. These may
include the official National Food Security Act (NFSA)https://ndap.niti.gov.in/India’s
open government data platform — and records from state or district-level Public
Distribution System (PDS) databases. While the dataset provides detailed insights into
the distribution mechanisms under NFSA, the exact source is not explicitly mentioned in
the file. Further confirmation may be available through additional notes or references
found within the 'HOME PAGE' or other related sheets in the Excel file.
3.DATASET PREPROCESSING
To preprocess in Excel:
1. Remove Empty Rows/Columns: Delete fully empty rows and columns.
2. Rename Columns: Replace "Unnamed" headers with meaningful names.
3. Handle Missing Values: Fill missing data or delete rows/columns with blanks.
4. Convert Data Types: Ensure numeric columns are set as "Number" format.
5. Normalize/Standardize (if needed): Use formulas for normalization or
standardization. ANALYSIS ON DATASET (Objective-wise)
The dataset contains monthly public distribution system data across Indian states, with
3,027 records and the following key columns:
Key Columns for Analysis:
1. Food grains allocated
2. Ration cards issued
3. Transaction for ration cards
4. Aadhaar authenticated Transactions & (%)
5. ePoS vs Manual distribution of food grains
6. Distribution of food grains (Total)
Objective 1: . Analyze the Efficiency of Aadhaar-Based Authentication
Goal: Evaluate the effectiveness and adoption of Aadhaar-based authentication in ration
distribution by comparing the percentage of authenticated transactions across states and years.
 State-Wise Pie Chart: This chart would show the percentage of authenticated
transactions for each state. Each slice of the pie would represent a state, with the size
of the slice corresponding to the proportion of authenticated transactions in that
state. It gives a clear, easy-to-digest view of how each state is performing.
 Year-Wise Pie Chart: A pie chart for each year could show the distribution of
authenticated versus non-authenticated transactions across all states. This would
give an overall picture of Aadhaar adoption in ration distribution for that particular
year.
Objective 2: Study the Year-on-Year Trends in Ration Card Issuance
Line Chart (Year-on-Year Trends): A line chart can show the growth or decline in the
number of ration cards issued across years. The x-axis would represent the years,
and the y-axis would represent the number of cards issued, helping to visualize
trends over time.
Stacked Bar Chart (State-Year Performance): A stacked bar chart can show the
number of ration cards issued by each state for each year. This allows for both yearly
comparisons and the distribution of ration cards across states in each year, making it
easier to see state-level trends over time.
Objective 3: Compare Manual vs ePoS Distribution Methods
Goal: Quantify the shift from manual distribution to ePoS systems and analyze which states are
leading or lagging in digital adoption.
Line Chart (Yearly Trends): A line chart can show the year-on-year shift from manual
to ePoS transactions across all states. The x-axis represents the years, and the y-axis
shows the percentage of ePoS transactions, which allows us to track the overall trend
in digital adoption over time. Calculate Percentage: For each year, apply the above
formula to calculate the percentage of ePoS transactions.
Plot the Data: Use the calculated percentages to plot the line chart, where:
 X-axis: Represents the years.
 Y-axis: Represents the percentage of ePoS transactions.
Objective 4: Perform a Regional Comparison of Food Grain Allocation
Goal: Compare food grain allocation across states and identify disparities or regional trends in
government support and distribution efforts.
A donut chart visually shows how much food grain each state receives out of the total
allocation. Each part of the ring represents a state, and the size of that part shows the
percentage of total food grains given to that state. The center space can be used to
display the total or average allocation.
Objective 5: Detect Anomalies in Distribution vs Allocation Objective
Goal: : Identify any unusual or suspicious patterns where distributed quantities
exceed allocated food grains, which could signal data entry issues or systemic
problems.
To detect anomalies in distribution vs allocation, compare the quantity of food grains
distributed to the quantity allocated for each state and time period. If the distributed
amount is greater than the allocated amount, it indicates a potential anomaly.
Objective 6: Examine how electronic Point of Sale (ePoS) adoption has increased over the years
across different states.
To examine how electronic Point of Sale (ePoS) adoption has increased over the
years, we analyze the percentage of total transactions conducted through ePoS
systems across various states and time periods. A rising trend in this percentage
indicates successful digital integration in the Public Distribution System (PDS). States
with consistently high ePoS usage reflect better infrastructure, training, and

# Electoral Bonds Data Analysis

This repository contains an analysis of electoral bonds data, focusing on the purchase and encashment of bonds by various entities and political parties. The analysis includes exploring trends over time, identifying key purchasers and receivers, and visualizing the data through various plots.

## Project Overview

The analysis involves two datasets:
1. **Buyer Data**: Information about companies and entities that purchased electoral bonds.
2. **Party Data**: Information about political parties that received the encashed bonds.

### Datasets

1. **Buyer Data**
   - **File**: `electroral_bonds_buyer_data.csv`
   - **Columns**:
     - `Date of Purchase`: Date when the bond was purchased.
     - `Purchaser Name`: Name of the entity that purchased the bond.
     - `Denomination`: Value of the bond purchased.

2. **Party Data**
   - **File**: `electroral_bonds_receiver_data.csv`
   - **Columns**:
     - `Date of\nEncashment`: Date when the bond was encashed.
     - `Name of the Political Party`: Name of the political party receiving the encashed bond.
     - `Denomination`: Value of the bond encashed.

## Analysis

### Buyer Data

1. **Companies Purchasing Bonds**
   - **Total number of unique companies**: 1316
   - **Total amount of bonds purchased**: 121,555,132,000 INR

2. **Visualizations**
   - **Daily Purchase Amount**: Trends in the total amount of bonds purchased daily.
   - **Top Buyers**: Amount of bonds purchased by each buyer.

3. **Insights**
   - The maximum amount of bonds purchased on a single day: 4,858,500,000 INR on 05/Jan/2022.
   - The company purchasing the maximum amount of bonds: FUTURE GAMING AND HOTEL SERVICES PR with 12,080,000,000 INR.

### Party Data

1. **Political Parties Receiving Bonds**
   - **Total number of unique parties**: 27
   - **Total amount of bonds encashed**: 127,690,893,000 INR

2. **Visualizations**
   - **Amount Received by Political Party**: Total amount of bonds received by each party.
   - **Daily Encashment Amount**: Trends in the total amount of bonds encashed daily.

3. **Insights**
   - The maximum amount of bonds encashed on a single day: 4,116,500,000 INR on 10/May/2019.
   - The party receiving the maximum amount of bonds: BHARTIYA JANTA PARTY with 60,605,111,000 INR.

### The Mysterious Difference

- **Difference Between Encashed and Purchased Bonds**: 6,135,761,000 INR
  - This discrepancy highlights an unexplained gap between the total value of bonds purchased and the total value encashed.



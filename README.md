# Household-Energy-consumption-Predictive-Analysis

**Problem Statement**: 
Households and utilities often lack predictive foresight, making demand spikes, billing shocks, and grid strain harder to manage. This POC tests whether an LSTM sequence model can reliably predict short-term consumption trends using past loads and exogenous variables (e.g., temperature), and whether such forecasts can inform actionable insights.

**Objective**
The objective is to  build robust time series forecasting models that can accurately predict future Energy  consumption trends based on historical data. The insights derived from this analysis can empower  households to optimize energy usage, plan efficiently, and contribute to sustainable energy  practices. The focus is on the Electrical energy Consumption. 

**Source**
The Dataset is downloaded from Kaggle and has a historical data reference from 2006 to 2010.
  https://www.kaggle.com/datasets/uciml/electric-power-consumption-data-set


**Dataset Description**:
1. Date: Date of the electricity consumption recording.
2. Time: Time of the electricity consumption recording.
3. Global_active_power: Total active power consumed by the household.
4. Global_reactive_power: Total reactive power consumed by the household.
5. Voltage: Voltage level during the electricity consumption period.
6. Global_intensity: Total current intensity consumed by the household.
7. Sub_metering_1: Electricity consumption in sub-metering 1 (e.g., kitchen).
8. Sub_metering_2: Electricity consumption in sub-metering 2 (e.g., laundry).
9. Sub_metering_3: Electricity consumption in sub-metering 3 (e.g., water heater).

**Deliverables**:
- Python scripts for data preprocessing, EDA, and time series prediction models.
- Visualizations illustrating consumption patterns, model evaluation metrics, and predicted future trends.

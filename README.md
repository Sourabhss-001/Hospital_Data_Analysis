# Hospital Operations & Patient Inflow Analysis

## Project Overview

This project focuses on analyzing hospital operations data to uncover trends in patient inflow, facility usage, and staff availability. We use data science techniques to derive insights and make predictions that can help hospitals optimize their resources and improve operational efficiency.

### Datasets Used

- **Patient Data (`patient_data.csv`)**:
  Contains information on daily patient inflow, patient demographics (age, gender), visit reasons, and patient outcomes.
  
- **Staff Schedule (`staff_schedule.csv`)**:
  Provides daily information on the availability of medical staff (doctors, nurses, and support staff) across the hospital.
  
- **Facility Usage (`facility_usage.csv`)**:
  Records the usage of critical hospital equipment such as MRI machines, CT Scans, X-rays, and Ultrasound facilities on a daily basis.

### Analysis Objectives

1. **Staff Utilization & Facility Usage Analysis**:
   - Identified patterns and relationships between staff availability and facility usage, aiming to improve resource allocation.
   - Clustering techniques were used to segment usage patterns and find opportunities for optimization.
   
2. **Patient Wait Time Analysis**:
   - Explored factors affecting patient wait times by analyzing variables like age, patient type, and equipment availability.
   
3. **Predicting Daily Patient Inflow**:
   - Implemented **ARIMA** model to forecast daily patient inflow using time series data. Lag features were introduced to capture temporal dependencies.
   - The ARIMA model helped in predicting short-term inflow to assist hospital resource planning.

### Key Findings

- **Clustering**: Grouped hospital days based on staff availability and facility usage. These clusters helped identify high-demand days and potential over-utilization of staff and resources.
  
- **Patient Wait Time**: Insights into which patient demographics or visit types contribute to longer wait times, providing actionable data for reducing patient waiting periods.

- **ARIMA Model**: The ARIMA time series model successfully forecasted daily patient inflow, providing hospital administration with useful predictive analytics for better scheduling and resource allocation.

### How to Use the Code

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/Sourabhss-001/Hospital_Data_Analysis.git

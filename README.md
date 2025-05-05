# Hotel Customer Segmentation Project  

This project focuses on performing customer segmentation for a hotel using various data analysis and machine learning techniques. By understanding different customer groups, the hotel can tailor marketing strategies, improve services, and enhance overall customer satisfaction and revenue.  

## Project Overview  

The main goal of this project is to analyze hotel customer data to identify distinct segments based on their behavior, preferences, and demographics. This segmentation can provide valuable insights for targeted marketing campaigns, personalized offers, and operational improvements.  

## Dataset  

The project utilizes the `HotelCustomersDataset.xlsx` dataset. This dataset contains information about hotel customers, including their demographics, booking history, revenue generated, and special requests.  

Key columns in the dataset include:  

- `ID` (dropped in analysis)  
- `Nationality`  
- `Age`  
- `DaysSinceCreation`  
- `NameHash` (dropped in analysis)  
- `DocIDHash` (dropped in analysis)  
- `AverageLeadTime`  
- `LodgingRevenue`  
- `OtherRevenue`  
- `BookingsCanceled`  
- `BookingsNoShowed`  
- `BookingsCheckedIn`  
- `PersonsNights`  
- `RoomNights`  
- `DaysSinceLastStay`  
- `DaysSinceFirstStay`  
- `DistributionChannel`  
- `MarketSegment`  
- Special Requests:  
  - `SRHighFloor`  
  - `SRLowFloor`  
  - `SRAccessibleRoom`  
  - `SRMediumFloor`  
  - `SRBathtub`  
  - `SRShower`  
  - `SRCrib`  
  - `SRKingSizeBed`  
  - `SRTwinBed`  
  - `SRNearElevator`  
  - `SRAwayFromElevator`  
  - `SRNoAlcoholInMiniBar`  
  - `SRQuietRoom`  

*(Note: The columns `ID`, `NameHash`, and `DocIDHash` were dropped during the data processing phase as they were not relevant for the segmentation analysis.)*  

## Methodology  

The project follows a standard data science methodology, including:  

1. **Data Loading and Initial Inspection:** Loading the dataset and performing initial checks on its structure and content.  
2. **Data Cleaning and Preprocessing:** Handling missing values, dropping irrelevant columns (`ID`, `NameHash`, `DocIDHash`), and preparing the data for analysis.  
3. **Exploratory Data Analysis (EDA):** Visualizing the data to understand distributions, relationships between variables, and identify potential features for segmentation.  
4. **Feature Engineering:** Creating new features from existing ones if necessary to better capture customer behavior.  
5. **Clustering:** Applying clustering algorithms (e.g., K-Means) to group customers into distinct segments based on selected features.  
6. **Segment Analysis:** Analyzing the characteristics of each identified segment to understand their unique profiles.  
7. **Interpretation and Recommendations:** Providing insights and actionable recommendations for the hotel based on the customer segments.  

## Technologies and Libraries Used  

- Python  
- Pandas: For data manipulation and analysis  
- NumPy: For numerical operations  
- Matplotlib: For data visualization  
- Seaborn: For enhanced data visualization  
- Scikit-learn: For clustering algorithms and other machine learning tools  

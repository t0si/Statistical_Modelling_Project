# **Final Project: Statistical Modelling with Python**

## **Overview**
This project explores statistical modeling by leveraging data from **CityBike**, **Yelp**, and **Foursquare** APIs. The goal was to analyze the relationship between the location of businesses near bike rental stations in São Paulo and their ratings.

---

## **Project Goals**
- **Primary Objective**: 
  To identify and analyze patterns among restaurants, coffee shops, and bakeries located within a 200-meter radius of bike rental spots in São Paulo.

- **Key Steps**: 
  1. Retrieve bike station data using the **CityBike API**. 
  2. Collect business data (restaurants, bakeries, and coffee shops) via **Foursquare** and **Yelp APIs**. 
  3. Analyze whether proximity to bike rental stations influences business ratings.

---

## **Process**

### **Step 1: Gather Bike Rental Data**  
- Retrieved all bike rental points in São Paulo using the **CityBike API**. 
- Recorded the latitude, longitude, and station IDs.

### **Step 2: Collect Business Data**  
- Queried **Foursquare** and **Yelp APIs** to locate restaurants, bakeries, and coffee shops within a **200-meter radius** of each bike station. 
- Stored relevant business details for analysis, such as: 
  - Name 
  - Category 
  - Rating 
  - Distance from the station 

### **Step 3: Combine Datasets**  
- Merged data from the **CityBike API** and the **Yelp API** into a unified dataset.

### **Step 4: Database Creation**  
- Generated a **SQLite database** to store and manage all API data.

### **Step 5: Build and Analyze a Regression Model**  
- Developed a **linear regression model** to explore correlations between variables (e.g., proximity, business category) and business ratings.

---

## **Results**

- **Yelp API**: 
  - Easy to use but limited by the free account’s daily call quota. 
- **Foursquare API**: 
  - Returned significant amounts of data, but many critical fields contained null values, limiting its utility. 

---

## **Challenges**
1. **API Usage**: 
   - This was my first project working with APIs, so understanding documentation and returning accurate results took time. 

2. **Data Quality**: 
   - Foursquare data contained too many null values to be effectively used. 

---

## **Future Goals**
- Improve API request precision to retrieve better-quality data. 
- Conduct more thorough preprocessing and cleaning of the dataset prior to analysis. 
- Explore additional statistical techniques or machine learning models to refine insights. 

---

## **Technologies Used**
- **Programming Language**: Python 
- **Libraries**: pandas, numpy, scikit-learn, sqlite3 
- **APIs**: CityBike, Yelp, Foursquare 
- **Database**: SQLite 

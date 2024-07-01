# Big-Sales-Prediction
Big Sales Prediction using Random Forest Regressor

This project aims to predict sales for a retail company using a Random Forest Regressor model. The dataset contains various attributes related to the items and outlets, which will be used to train the model to predict the sales for different products across various stores.

**Dataset Overview**
The dataset includes 12 variables:
****1]Item_Identifier:** Unique product ID.
**2]Item_Weight:** Weight of the product.
**3]Item_Fat_Content:** Whether the product is low fat or regular.
**4]Item_Visibility:** The percentage of total display area of all products allocated to the particular product.
**5]Item_Type:** The category to which the product belongs.
**6]Item_MRP:** Maximum Retail Price (list price) of the product.
**7]Outlet_Identifier:** Unique store ID.
**8]Outlet_Establishment_Year:** The year in which the store was established.
**9]Outlet_Size:** The size of the store in terms of ground area.
**10]Outlet_Location_Type:** The type of area in which the store is located.
**11]Outlet_Type:** Whether the outlet is a grocery store or some sort of supermarket.
**12]Item_Outlet_Sales:** Sales of the product in the particular store (target variable).

**Data Preprocessing**
**Import Libraries:**
1)pandas
2)numpy
3)seaborn
4)matplotlib
5)sklearn

**Load Dataset**: The dataset is loaded into a pandas DataFrame from a CSV file.

**Exploratory Data Analysis (EDA):**
Display the first five rows of the DataFrame.Get information about the DataFrame, including column names, data types, and summary statistics.
Handle missing values by filling them with appropriate statistics (e.g., mean).

**Categorical Variables:**
Analyze and transform categorical variables into numerical values using mapping and encoding techniques.

**Feature Scaling:**
Standardize numerical features to have a mean of zero and a standard deviation of one.

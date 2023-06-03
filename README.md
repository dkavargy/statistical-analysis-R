# Statistical Analysis with R in Saratoga Dataset
Exploring Housing Market Trends: A Statistical Analysis Using R and Descriptive Statistics

## 📝 Description

The aim of this study is to draw conclusions from the Saratoga housing data by conducting a statistical analysis using R and descriptive statistics. The dataset under investigation includes the following variables:

  *  Price: The price of the house in thousands of dollars (dependent variable).
  *  lotSize: The size of the land in square feet.
  *  age: The age of the house in years.
  *  landValue: The value of the land in thousands of dollars.
  *  livingArea: The living area of the house in square feet.
  * pctCollege: The percentage of college graduates among neighbors.
  *  bedrooms: The number of bedrooms.
  *  fireplaces: The number of fireplaces.
  *  bathrooms: The number of bathrooms.
  *  rooms: The number of rooms.
  *  heating type: The type of heating system.
  *  fuel: The heating fuel type.
  *  sewer type: The type of sewer system.
  *  waterfront: The presence of a waterfront.
  *  newConstruction: Whether the house is newly constructed.
  *  centralAir: Whether the house has central air conditioning.

Through the use of descriptive statistics in R, this study aims to provide valuable insights into the Saratoga housing market, examining relationships between variables and identifying key factors that influence house prices. The findings will contribute to a better understanding of the housing trends in the Saratoga area.

##  🔍 Research Questions

In this study, we will examine the relationship between all variables and the house price, aiming to explore the degree of correlation by constructing appropriate predictive models. Furthermore, we will investigate whether the intuitively reasonable correlation between the "newConstruction" variable and the percentage of college graduates in the neighborhood, the number of rooms, the price, and the age of the construction (by definition), is confirmed by our data.

The research questions addressed in this study are as follows:

  *   What is the relationship between each variable (lotSize, age, landValue, livingArea, pctCollege, bedrooms, fireplaces, bathrooms, rooms, heating type, fuel, sewer type, waterfront, newConstruction, centralAir) and the price of the house?
  *   To what extent can these variables be used to predict the house price by constructing suitable predictive models?
  *   Is there a significant correlation between the "newConstruction" variable and the percentage of college graduates in the neighborhood, the number of rooms, the price, and the age of the construction, as expected?

By answering these research questions, we aim to gain insights into the factors influencing house prices in the Saratoga area and examine the interplay between variables in the housing market.

## 📚 Dataset

This dataset provides a comprehensive view of various aspects related to houses in Saratoga, including their physical attributes, location factors, and amenities.
 It serves as a valuable resource for conducting statistical analysis, exploring relationships between variables, and predicting house prices based on the available features.
 
 ## ⚙️ Setup
 Installs R packages using the install.packages() function
 
 ```bash
 packages=("dplyr" "ggplot2" "tidyr" "caret" "glmnet" "randomForest" "lmtest" "psych" "lme4" "survival")

# Loop through the packages and install them
for package in "${packages[@]}"
do
    Rscript -e "install.packages('$package', repos='http://cran.r-project.org')"
done
```
Save the above code in a file with a .sh extension (e.g., install_packages.sh). Make the file executable using the following command:
 ```bash
chmod +x install_packages.sh
```
Then, you can run the script by executing:
```bash
./install_packages.sh
```
## 🔍 Exploratory Data Analysis

### Histogram of Housing Price
![hph](https://github.com/dkavargy/statistical-analysis-R/assets/73905168/caffd46d-2f9f-46a8-856b-3ab0f32b5e46)

### Distribution of bedroom 
![dsb](https://github.com/dkavargy/statistical-analysis-R/assets/73905168/76787d42-85ac-4429-8e35-cea1c94a1ab3)

### Correlation between variables
![cor](https://github.com/dkavargy/statistical-analysis-R/assets/73905168/1716d7d1-9048-4f48-8c54-4f03a6e4564d)

### Correlation Price-Age
![pri-age](https://github.com/dkavargy/statistical-analysis-R/assets/73905168/35737248-fcc4-4c4b-abca-04c4d81309ca)



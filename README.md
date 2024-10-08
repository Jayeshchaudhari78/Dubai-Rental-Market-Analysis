# Dubai-Rental-Market-Analysis
## 1. Project Overview

The Real Estate Rent Analysis Dashboard provides a comprehensive visualization of the rent data for properties in various cities in the UAE. The dashboard offers insights such as average rent, total rent, rent distribution by property type and furnishing status, and city-wise rent distribution. The dashboard allows filtering by multiple categories like city, rent category, beds, baths, and furnishing status.

## 2. Dataset

The dataset used in this dashboard contains information on rent prices, property types, locations, furnishing statuses, and more. Key columns include:

City: The location where the property is situated.

Rent_category: Whether the rent price is categorized as high, medium, or low.

Beds and Baths: Number of bedrooms and bathrooms.

Furnishing: Whether the property is furnished or unfurnished.

Type: Type of property such as Apartment, Villa, Penthouse, etc.

Rent: The rent amount for the respective property.

## 3. Dashboard Components

## A) Top KPIs

Average Rent: Displays the average rent amount of all properties.

Average Rent per Sqft: Shows the average rent per square foot for all properties.

Total Rent: Summarizes the total rent collected from all properties.

## B) Filter Options

City Filter: Dropdown allowing the user to select specific cities for rent analysis.

Rent Category Filter: Filter to select properties based on rent categories (high, medium, low).

Month Year Filter: Allows users to filter rent data based on a specific month or year.

Beds and Baths Filters: Used to filter data by the number of bedrooms and bathrooms.

Furnishing Toggle: A toggle to switch between furnished and unfurnished properties.

## C) Charts and Graphs

Average of Rent by Type: This bar chart shows the average rent prices by property type, such as Residential Buildings, Villas, and Apartments.

Total Rent Distribution by City: This horizontal bar graph illustrates how much rent each city contributes, with Dubai having the highest share.

Rent Distribution by Category: A pie chart displaying the proportion of properties in high, medium, and low rent categories.

Sum of Rent by Furnishing: A doughnut chart dividing the total rent based on whether properties are furnished or unfurnished.

Average Yearly Rent by Top 5 Locations: A bar chart that highlights the yearly rent averages for the top 5 locations, with Emirates Hills leading.

Average of Rent by Year: A line chart displaying rent trends over the years (2022-2024), showing an increase in the average rent.

Rent by Property Type: A table that lists various property types and their corresponding rent totals, providing a breakdown of rent for each category.

## Step-by-Step Creation Process

## A. Data Preparation

Data Import: Load the dataset into Power BI Desktop. The dataset should have columns like city, rent, beds, baths, property type, and furnishing status.

Data Cleaning: Ensure all data is cleaned for any missing or inconsistent values. Create calculated columns for new metrics such as Rent per Square Foot and Average Ren

## B. Data Modeling

Relationships: Define relationships between tables if working with multiple tables. For instance, the relationship between a properties table and a locations table.

### Measures:
Create measures for Total Rent (Total Rent = SUM([Rent])).

Create a measure for Average Rent (Average Rent = AVERAGE([Rent])).

Calculate Average Rent per Square Foot using another measure (Avg Rent per Sqft = AVERAGE([Rent_per_sqft])).

## C. Creating Visuals

KPIs: Create Card visuals to show Total Rent, Average Rent, and Avg Rent per Sqft.

Bar Charts: Use Stacked Bar Chart visuals to show Average of Rent by Type and Total Rent by City.

Pie Chart: Add a Pie Chart to visualize the Rent Distribution by Category.

Line Chart: Implement a Line Chart for Average Rent by Year, showing the trend of rent prices over the years.

Doughnut Chart: Use the Doughnut Chart for the Sum of Rent by Furnishing to compare furnished vs. unfurnished properties.

Table: Create a table to display the Rent by Property Type for an easy view of rent totals across property types.

## D. Interactions and Filters

Add filter slicers for City, Rent Category, Beds, and Baths to allow dynamic data selection.

Implement the Furnishing Toggle (Furnished/Unfurnished) to switch between different furnishing statuses.

Enable cross-filtering across visuals so that selections made in one visual filter the data in the others.

## E. Date Range Selection

Add a Date Slicer to allow filtering data by a specific date range, e.g., from 2022 to 2024.

## 5. Design and Formatting

Theme: Use a consistent color theme throughout the dashboard to make it visually appealing and easy to read.

Titles and Labels: Ensure all visuals have clear titles and data labels to improve readability.

Tooltips: Add custom tooltips for additional information when hovering over visuals.

## Conclusion

This Power BI dashboard effectively provides a detailed overview of the rental market in UAE cities, highlighting trends and patterns in rent prices across various property types and locations. The interactive features and filtering options allow users to drill down into the data for specific insights.



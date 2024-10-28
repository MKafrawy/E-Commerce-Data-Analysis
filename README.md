# E-Commerce Purchases Analysis

This project focuses on analyzing e-commerce customer purchase data to uncover insights about customer behavior, payment patterns, and language preferences. The dataset, sourced from Kaggle, contains information on customers, purchases, and other details such as credit card information, job titles, and email addresses.

## Dataset Overview

The dataset consists of 10,000 records, each representing an individual purchase. It contains 14 columns:
- **Address**: The customer’s address
- **Lot**: Lot number
- **AM or PM**: Time of purchase (AM or PM)
- **Browser Info**: Browser used for the purchase
- **Company**: Company name associated with the purchase
- **Credit Card**: Credit card number
- **CC Exp Date**: Credit card expiration date
- **CC Security Code**: Security code of the credit card
- **CC Provider**: Credit card provider (e.g., Mastercard, Visa)
- **Email**: Customer's email address
- **Job**: Customer's job title
- **IP Address**: Customer's IP address
- **Language**: Preferred language of the customer
- **Purchase Price**: Price of the purchase

## Exploratory Data Analysis

### Data Import and Setup
1. **Importing Libraries**: Pandas is used for data manipulation and analysis.
2. **Loading Data**: The dataset is loaded and displayed for inspection of column names and sample records.

### Initial Data Exploration
- **Data Types**: Checked data types of each column to understand the data structure.
- **Null Values**: Confirmed that there are no null values across the dataset.
- **Dataset Size**: Verified the number of columns (14) and rows (10,000).

## Key Questions and Insights
1. **What is the lowest and highest purchase price?**
2. **What is the average purchase price?**
3. **How many customers speak English?**
4. **How many people use Mastercard and made a purchase above $80?**
5. **How many job titles contain the word 'engineer'?**
6. **What is the email of the person with the credit card number 4664825258997302?**
7. **How many purchases occurred during AM and how many during PM?**
8. **How many credit cards expire in the year 2020?**


## Conclusions

This analysis provided insights into customer preferences, peak purchase times, and payment patterns. Key takeaways include:
- Most purchases were made during the PM hours.
- A significant portion of customers prefer using English, with **Mastercard** being a popular payment choice among high spenders.
- Job titles related to engineering are common among customers.


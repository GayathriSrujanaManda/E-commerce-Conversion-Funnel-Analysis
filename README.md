# E-commerce-Conversion-Funnel-Analysis

## Project Overview
This project focuses on analyzing the conversion funnel of an e-commerce website to improve the conversion rate from product page views to completed purchases. By identifying and addressing drop-off points in the user journey, the project aims to enhance the overall user experience and increase sales.

## Objectives
- Set up a funnel to track the user journey: homepage → product page → add to cart → checkout → purchase.
- Analyze where the highest drop-offs occur.
- Implement changes to reduce drop-offs, such as simplifying the checkout process, adding trust badges, or offering discounts.
- Measure the impact of these changes on conversion rates.

## Dataset
The project uses a dataset containing user interactions with the e-commerce website. The dataset includes the following files:
- `home_page_table.csv`
- `payment_confirmation_table.csv`
- `payment_page_table.csv`
- `search_page_table.csv`
- `user_table.csv`

## Steps

### 1. Load and Preprocess Data
Load the data from CSV files and preprocess it by adding relevant columns and combining the data into a single DataFrame.

### 2. Define Funnel Stages
Identify key stages in the conversion funnel:
- Homepage View
- Product View
- Add to Cart
- Checkout
- Purchase

### 3. Analyze Drop-Off Points
Calculate the number of users at each stage and compute conversion rates between stages to identify significant drop-off points.

## Analysis and Results
The analysis identified significant drop-offs at specific stages in the funnel. The following conversion rates were calculated:

- Homepage View to Product View: 50%
- Product View to Checkout: 13.34%
- Checkout to Purchase: 7.50%

These results highlight areas where improvements can be made to increase conversions.

## INTERPRETATION
Homepage to Product View (50%): Half of the users who visit the homepage proceed to view a product. This is a reasonable rate, but there's room for improvement.
Product View to Checkout (13.34%): There is a significant drop-off here. It suggests that users are browsing products but not adding them to their cart or proceeding to checkout.
Checkout to Purchase (7.50%): There is another substantial drop-off during the checkout process. Simplifying the checkout process or adding trust badges might help improve this rate.

## Visualization
Conversion rates are visualized using bar charts to provide a clear comparison between different stages in the funnel.

## Future Work

### 1. Implement Changes
Based on the analysis, implement changes to the website to reduce drop-offs. Possible changes include:
- Enhance product descriptions and images.
- Offer discounts or promotions.
- Simplify navigation and ensure that product recommendations are relevant.
- Simplify Checkout Process:
- Reduce the number of steps in the checkout process.
- Offer guest checkout options.
- Add trust badges and ensure users that their payment information is secure.
- 
### 2. Measure Impact
- Track conversion rates before and after implementing changes to measure their impact. Continuously monitor and analyze the funnel to identify new drop-off points.
- Implement A/B testing for further optimization.
- Explore additional features that can enhance user experience and increase conversions.


## Tools and Technologies
- Python
- Pandas
- Matplotlib

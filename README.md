# Zomato Data Analysis  Project

## Introduction

In this project, I analyzed a dataset of restaurant information from **Zomato** to uncover insights into customer behavior, restaurant preferences, and spending patterns. The dataset contains various attributes such as restaurant names, ratings, votes, types of restaurants, and spending data.

---

## Business Problem

Zomato aims to improve its customer engagement and personalize restaurant recommendations. The business challenge is to understand the patterns in customer behavior, restaurant ratings, spending habits, and order modes (online vs. offline) to help Zomato enhance its platform and offer targeted promotions. 

The key business questions we need to answer are:
- Which types of restaurants do customers prefer?
- How can Zomato tailor their promotional strategies based on customer feedback and spending?
- What insights can be drawn from customer ratings and votes?

---

## Goal of the Dashboard

The goal of this analysis is to create a dashboard that answers critical questions regarding:
- The most popular types of restaurants.
- The average spending of customers, especially couples.
- The correlation between online/offline orders and customer ratings.
- Identifying which restaurant types perform better in offline orders.

The dashboard should help Zomato make data-driven decisions on promotions, targeting specific customer segments, and improving their service offerings.

---

## Key Visuals

1. **Restaurant Type Distribution**:
   - A **count plot** was used to show the frequency of customer orders for each restaurant type.
   - **Insight**: Quick bites and casual dining options are the most ordered restaurant types, which highlights the customer preference for quick and casual dining experiences.

2. **Votes Distribution**:
   - A **bar plot** was created to display the number of votes each restaurant type has received.
   - **Insight**: Casual dining and quick bites have the highest number of votes, indicating greater customer engagement in these categories.

3. **Rating Distribution**:
   - A **histogram** was used to analyze the distribution of restaurant ratings.
   - **Insight**: Most restaurants have ratings between 3.5 and 4.5, signaling a general customer satisfaction across the platform.

4. **Average Spending per Order by Couples**:
   - A **count plot** was created to show the spending range of couples ordering food for two.
   - **Insight**: Couples typically spend between ₹500 to ₹1200 per order, suggesting opportunities for Zomato to create couple-targeted promotions.

5. **Online vs. Offline Orders: Rating Comparison**:
   - A **box plot** was created to visualize the distribution of ratings for online vs offline orders.
   - **Insight**: Online orders generally have higher ratings, indicating a more satisfactory experience with the app or online ordering.

6. **Offline Orders by Restaurant Type**:
   - A **bar plot** was created to compare the number of offline orders across restaurant types.
   - **Insight**: Restaurants like cafes and casual dining options have higher offline orders, which could inform Zomato’s offline marketing strategies.

---

## Insight and Conclusion

### Key Insights:
- **Restaurant Preferences**: The majority of customers prefer quick bites and casual dining options, which suggests that these restaurant types should be a focus for promotional offers.
- **Customer Engagement**: Casual dining and quick bites not only attract the most customers but also receive the highest number of votes, indicating strong customer engagement.
- **Online vs. Offline**: Online orders consistently receive higher ratings, reflecting a positive user experience with online ordering. Zomato could further enhance this experience to retain customer satisfaction.
- **Couple Spending**: Average spending per couple falls within a specific range, which provides an opportunity to create targeted campaigns for couples, such as discounts or combo offers.

### Conclusion:
This analysis provides actionable insights that can help Zomato refine its promotional strategies, targeting both online and offline customers more effectively. By focusing on customer preferences, Zomato can tailor its offerings, improve customer satisfaction, and optimize its business operations.

---

## Future Work

- **Customer Segmentation**: Segment customers based on their spending behavior and preferences.
- **Time Series Analysis**: Analyze how ratings and orders fluctuate over time to identify trends.
- **Geographical Insights**: Investigate how customer preferences differ by location to refine restaurant recommendations.

---

## Libraries Used

- **Pandas**: For data manipulation and analysis.
- **NumPy**: For numerical operations.
- **Matplotlib/Seaborn**: For data visualization and creating insightful plots.

---

## Why This Project?

This project showcases my ability to work with real-world datasets, clean and transform the data, and visualize key insights that could influence business decisions. By presenting actionable recommendations through clear visualizations, I demonstrate my skills in data analysis, problem-solving, and communicating results effectively.


# Balaji-Restaurant-Sales.
## About dataset

1. Description:

This dataset captures sales transactions from a restaurant based in India named Balaji.
It includes details such as the order ID, date of the transaction, item names (representing various food and beverage items), item types (categorized as Fast-food or Beverages), item prices, quantities ordered, transaction amounts, transaction types (cash, online, or others), the gender of the staff member who received the order, and the time of the sale (Morning, Evening, Afternoon, Night, Midnight). The dataset offers a valuable snapshot of the restaurant's daily operations and customer behavior.

2. Columns: 

![Balaji github pres background](https://github.com/user-attachments/assets/6fa469eb-c560-446b-9f74-5fe1bde61917)

## Data Loading | Cleaning


![balaji workbook bad screenshot](https://github.com/user-attachments/assets/e676c846-2888-40f6-8bbe-5d5c749ad6d2)

The dataset was not appropriately cleaned so I took some steps in cleaning the dataset, some of the steps include:
- Remove or Correct the Blank First Row.
- Correct the Misaligned Headers.
- Handle the #NAME? Errors.
- Assess Missing Values
- Ensuring the data is allocated to it's appropriate data type.
- Check for Duplicate Rows by using the order id, as a check row.
- Create Derived Columns (e.g: month column, year column, and day column, for precise analysis)

This is a link to the clean and edited dataset.
[Balaji resturant sales - clean xl](https://github.com/user-attachments/files/20374171/Balaji.Fast.resturant.sales.-.worked.on.xlsx)


# Objectives and Methodology
## Objectives
This analysis was conducted to review the following findings:
- Analyze sales trend over time.
- Understand customer preference item.
- Evaluate the impact of payment method on sales.
- Evaluating sales rate based on staff gender.
- Analyzing sales rate at different times of the day.

## Methodology:
To achieve these objectives, the project employed Power Bi for advanced data visualization and trend analysis. The methodology involved:

- Descriptive Analytics: Generating summary statistics and visual reports to highlight key performance indicators.
- Trend Analysis: Using line graphs to track growth and performance over time.
- Sales Rank Comparisons: Creating interactive dashboards to showcase the most purchased items, and customer most preferred items using treemaps to rank their order
Power Bi’s interactive visualization capabilities made it the ideal tool for presenting data-driven insights in an engaging manner.

# Overview of findings:
1️⃣ Sales/Perfomance and growth trend:
  - There has been an unstable change in the growth rate of Balaji Restaurant within the months, the growth rates was unstable.
  - There has been a decline In the yearly sales trend, from between the years of 2023 - 2024.

2️⃣ The impact of method of payment on sales:
  - From the analysis it can be denoted that payment with cash had more sales than payment online.
  - It showed that customers paid more in cash than they paid online, with this konwledge, Balaji restaurants can set in place more systems that'll encourage and promote easier payment with cash.

3️⃣ Sales rate based on gender:
  (Dislaimer: this is not to favour any gender but only to rate general perfomance of workers in "Balaji Restaurants" based on gender and based on the dataset available)
  - From the dataset we could denote that the male workers made more sales than the female workers, in terms of quantity sold.

4️⃣ Sales rate ranking by of sale:
  - The time of sale was mainly disributed in three cadres which are the morning, afternoon and the night.
  - from the dataset it was evident that 40.85% of the restaurant sales were made in the night, and the next highest time sale was in the 
    morning with a total of 39.87% out of the total sales time, and then the least was in the afternoon.

# Conclusion:
This project provided valuable insights for the performance trends of Balaji Food Restaurant, growth rate, and relative importance in the industry from 2023 to 2024. By leveraging Power Bi for visualization.

Future work can further explore:

- Deep Learning Models for growth rankings based on past performance.
- Comparative Analysis between Balaji food restaurant and other restaurants within the region
- By understanding historical performance trends, Balaji restaurants can enhance their strategies and enhance their systems in order to 
  make more sales.

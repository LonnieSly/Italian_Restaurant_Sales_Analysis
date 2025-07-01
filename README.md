# Italian_Restaurant_Sales_Analysis
🔍 In my latest project, I analyzed point-of-sale data from an Italian restaurant to identify revenue trends and drive smarter decision-making.
# Italian Restaurant Sales: A Data-Driven Analysis for Business Growth

### Project Overview | Problem & Solution

**Problem:** A restaurant possesses a wealth of daily sales data but lacks the actionable insights needed to make strategic decisions. Key business questions about peak hours, menu popularity, and customer behavior remain unanswered, hindering opportunities for revenue growth and operational optimization.

**Solution:** This project performs an end-to-end analysis of a restaurant's sales data to transform raw numbers into a strategic asset. By cleaning the data, performing exploratory analysis, and visualizing key trends, I identified clear, actionable recommendations to improve menu engineering, optimize staffing, and enhance the customer payment experience.

**My Unique Approach:** Leveraging my background in restaurant management, I focused not just on technical execution but on asking the right business questions that directly impact a restaurant's bottom line.

### Dataset
The dataset used for this analysis is the "Restaurant Orders" dataset from Kaggle, containing detailed, anonymized order information.
[Link to Dataset on Kaggle](https://www.kaggle.com/datasets/ahmedabbas7/restaurant-1-orders-and-menu)

### Tools & Libraries
*   **Programming Language:** Python
*   **Libraries:** Pandas (Data Manipulation), Matplotlib & Seaborn (Data Visualization)
*   **Environment:** Google Colab (for collaboration and cloud-based analysis)

---

### The STAR Method: My Analytical Process

####  situasi (Situation)
An Italian restaurant needs to understand its sales performance deeply to navigate a competitive market. They need to know which menu items are driving profit, when their busiest periods are, and how their customers prefer to pay.

#### Task (Task)
My task was to analyze one year of order data to answer these critical business questions and provide data-driven recommendations. The key objectives were:
1.  Identify sales trends based on time (day of the week, month).
2.  Determine the most and least popular menu items and categories.
3.  Analyze customer payment preferences.

#### Action (Action)
I executed a structured analysis process:
1.  **Data Cleaning & Preprocessing:**
    *   Loaded the dataset into a Pandas DataFrame.
    *   Checked for and handled missing values and duplicates.
    *   Standardized data types, converting the `Order Date` column to a proper datetime format.
    *   Engineered new features like `day_of_week`, `day_name`, and `month` to facilitate time-series analysis.
2.  **Exploratory Data Analysis (EDA):**
    *   Aggregated sales data to identify peak days of the week and busiest months of the year.
    *   Analyzed menu item quantities to rank the top 10 best-sellers.
    *   Grouped items by category to understand which sections of the menu (e.g., Pizza, Pasta, Beverages) are most popular.
    *   Visualized the distribution of payment methods to see how customers pay.
3.  **Visualization & Reporting:**
    *   Created clear and insightful visualizations using Matplotlib and Seaborn to communicate findings effectively.
    *   Synthesized the results into a final report with actionable business recommendations.

*Example Visualization: Peak Sales Days*
  <!-- **Instruction:** Take a screenshot of your "Total Orders by Day of the Week" chart, upload it to a site like imgur.com, and paste the link here. -->

#### Result (Result)
The analysis yielded several critical insights and actionable recommendations:

*   **Finding 1: Predictable Peaks in Demand.** Fridays and Saturdays are the highest-volume days, while July and August are the peak months.
    *   **Recommendation:** Implement a dynamic staffing model to increase staff during these known peaks. Launch "Weekday Special" promotions to drive traffic on slower days like Monday and Tuesday.

*   **Finding 2: The "Margherita Pizza" is a Superstar.** It is the single best-selling item by a significant margin. The 'Pizza' category as a whole dominates sales.
    *   **Recommendation:** Heavily promote the Margherita Pizza. Create combo deals featuring it (e.g., "Margherita Madness Monday"). Analyze the profitability of the lowest-selling items to consider menu consolidation.

*   **Finding 3: Cash and Online are Key Payment Channels.** Cash is the most used payment method, but "Online" payments are a very strong second.
    *   **Recommendation:** While maintaining efficient cash handling, it is crucial to invest in and optimize the online payment user experience. A seamless digital transaction can encourage repeat business and larger orders.

### How to Run this Project
1. Clone the repository: `git clone https://github.com/your-username/your-repo-name.git`
2. Open the `Italian_Restaurant_Sales_Analysis.ipynb` file in Google Colab or Jupyter Notebook.
3. Ensure you have the required libraries (`pandas`, `matplotlib`, `seaborn`) installed.
4. Upload the `restaurant-1-orders.csv` file to your environment and run the cells.

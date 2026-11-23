Zomato Restaurant Data Analysis
Exploratory Data Analysis (EDA) using Python

This project explores a sample Zomato restaurant dataset to understand restaurant categories, customer votes, ratings, online-ordering availability, table booking, and approximate cost for two people.
Project Overview
- Dataset size: 148 rows and 7 columns
- Analysis level: Restaurant records
- Main tools: Python, Jupyter Notebook, Pandas, NumPy, Matplotlib, Seaborn
Objectives
- Inspect the dataset structure and summary statistics.
- Clean and prepare rating values and column names.
- Check missing values and duplicate records.
- Compare restaurant categories by votes, record count, average rating, and approximate cost.
- Explore the relationship between ratings, votes, and online-ordering availability.
Repository Structure
zomato-restaurant-data-analysis/
├── zomato_restaurant_eda.ipynb
├── zomato_restaurant_data.csv
├── NarendraK_Zomato_Restaurant_EDA_Report.pdf
├── zomato_analysis_presentation.pptx
└── README.md
If your uploaded files have different names, either rename them to match this list or update the filenames in this README.

Technologies Used
- Python – analysis and scripting
- Pandas – data loading, cleaning, grouping, and aggregation
- NumPy – numerical operations
- Matplotlib – charts and plots
- Seaborn – statistical visualizations
- Jupyter Notebook – interactive analysis environment
Dataset Description
The CSV contains these fields:
Column	Description
Restaurant Name	Restaurant name
Online_Order	Whether online ordering is available
Book_Table	Whether table booking is available
Rate	Restaurant rating, initially stored in an x/5 format
Votes	Number of customer votes
Approx_Cost(For Two People)	Approximate cost for two people
Listed_In(Type)	Restaurant category


How to Run the Project
1. Clone or download this repository.
2. Open a terminal in the project folder.
3. Install the required libraries:
   pip install pandas numpy matplotlib seaborn jupyter
4. Start Jupyter Notebook:
   jupyter notebook
5. Open zomato_restaurant_eda.ipynb.
6. Make sure zomato_restaurant_data.csv is in the same folder, then run the notebook cells in order.
Analysis Questions
The notebook explores these questions:
1. How many customer votes has each restaurant type received?
2. How many restaurants offer table booking?
3. Which five restaurants have the highest number of votes?
4. Is there a relationship between restaurant ratings and customer votes?
5. What is the average rating for each restaurant type?
6. Which restaurant type is most common in the dataset?
7. What ratings do restaurants most commonly receive?
8. Which restaurant type has the highest average cost for two people?
9. Do restaurants offering online ordering have higher ratings?
10. Which restaurant types have more records without online ordering?
Key Findings
Based on the supplied project report:
- Dining represents 110 of 148 records (74.3%) and has the highest total votes (20,363).
- Table booking is available in 8 records (5.4%).
- Empire Restaurant has the highest vote count in the sample (4,884).
- The reported correlation between ratings and votes is approximately 0.49.
- The Other category has the highest reported average rating (approximately 3.91/5).
- Buffet has the highest reported average approximate cost for two (671.43 dataset currency units).
- Records with online ordering have a higher reported average rating (3.86) than records without online ordering (3.49).
Conclusion and Limitations
The analysis describes the 148 restaurant records in the supplied dataset. It is a descriptive EDA project: the reported relationships do not establish cause and effect, and the sample should not be treated as representative of every restaurant on Zomato.
Project Files
- Jupyter Notebook: Python code and analysis workflow.
- CSV Dataset: Input data used by the notebook.
- PDF Report: Written explanation, analysis questions, findings, and conclusion.
- PowerPoint: Project presentation.
Author: Narendra K
Project: Zomato Restaurant Data Analysis using Python

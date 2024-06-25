# stackoverflow_ds_python_packages

**Summary and Overview**

This project aims to analyze the popularity and sentiment of various Python packages used in data science by leveraging StackOverflow data. I used StackOverflow's online database to fetch data using SQL queries and analyzed and visualized the data using Python.

The analysis included the following Python packages, which are commonly used in data science and were the focus of the sentiment and popularity analyses:

- pandas
- numpy
- scipy
- matplotlib
- seaborn
- scikit-learn
- tensorflow
- keras
- pytorch
- flask
- plotly
- sqlalchemy
- scrapy

Note that the data retrieved from StackOverflow does not necessarily suggest that certain Python packages have become more or less commonly used in general; this data only reflects how often each package was discussed on StackOverflow.

**Popularity of Python Packages Over Time**

![download](https://github.com/audreybayne14/stackoverflow_ds_python_packages/assets/148846840/e114639d-7839-4209-aa8f-8a618a16fb39)

This line chart tracks the popularity of Python packages on StackOverflow from 2008 to 2024. The chart reveals the growth trends and eventual decline in popularity for some packages. Notably, Pandas, NumPy, and TensorFlow show significant increases in usage over time.

**Popularity of Python Packages in 2020**

![download](https://github.com/audreybayne14/stackoverflow_ds_python_packages/assets/148846840/8a220967-2981-4c89-b6f0-a971220fffbb)

This bar chart shows the popularity of Python packages in 2020, which was the peak year for StackOverflow activity. Pandas was the most popular package by a significant margin, followed by NumPy and TensorFlow.

**Correlation Matrix of Python Packages Popularity**

![download](https://github.com/audreybayne14/stackoverflow_ds_python_packages/assets/148846840/17c3493d-cc54-4541-a5ca-dbf3a183b0e1)

This correlation matrix illustrates the relationships between the popularity of different Python packages. High correlation values indicate that packages are often mentioned together in posts. For example, Flask and Matplotlib have a high correlation, suggesting they are frequently used in similar contexts.

**Yearly Popularity of Python Packages Heatmap**

![download](https://github.com/audreybayne14/stackoverflow_ds_python_packages/assets/148846840/5eee573b-bcd3-4818-9490-c3af5c7125a9)

This heatmap shows the yearly popularity of Python packages based on the number of questions tagged with each package from 2008 to 2024. Darker colors indicate higher popularity. Pandas, NumPy, and Matplotlib show significant growth over the years, peaking around 2020.

**Sentiment Analysis of Python Packages**

![download](https://github.com/audreybayne14/stackoverflow_ds_python_packages/assets/148846840/83d2322e-eafd-4241-b16b-e7688e364f51)

This bar chart represents the average sentiment scores of posts related to various Python packages. Sentiment scores range from -1 (very negative) to 1 (very positive). Most packages have positive sentiment scores, suggesting favorable discussions. Conversely, Keras has a negative sentiment score, indicating more challenges or issues discussed in posts.

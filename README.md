# Applied Data Science Capstone: SpaceX Falcon 9 First Stage Landing Prediction 🚀

Welcome to my Applied Data Science Capstone project! In this project, I aim to predict whether the Falcon 9 first stage will land successfully. SpaceX advertises Falcon 9 rocket launches at a cost of **$62 million**, significantly lower than other providers, which can charge upwards of **$165 million**. This cost efficiency is largely due to SpaceX's ability to reuse the first stage of the rocket. By determining the likelihood of a successful landing, we can provide valuable insights for competitive pricing and operational efficiency.

## Table of Contents
- 📜 Project Overview
- 🎯 Learning Objectives
- 📂 About the Dataset
- 📁 Files
- ✅ Conclusion
- 📝 License

## Project Overview 📜
In this capstone, I take on the role of a data scientist for a fictional rocket company, **Space Y**. My primary goal is to gather information about SpaceX and create dashboards to analyze launch data. I also developped machine learning models to predict the success of Falcon 9 first-stage landings, which will help Space Y determine competitive launch pricing.

## Learning Objectives 🎯
By the end of this project, I was be able to:
- Develop Python code to manipulate data in a Pandas DataFrame.
- Convert JSON files into Pandas DataFrames.
- Utilize data science methodologies to define and formulate real-world business problems.
- Collect data through the SpaceX API and web scraping techniques.
- Load datasets, clean them, and extract meaningful insights.
- Conduct exploratory data analysis (EDA) and visualize data using Python libraries.
- Build and evaluate predictive models using machine learning techniques.

## About the SpaceX Launch Dataset 📂

The [`spacex_launch_dash.csv`](https://github.com/Zakaria-Engineer/Applied-Data-Science-Capstone/blob/main/spacex_launch_dash.csv) dataset provides detailed information on Falcon 9 launches conducted by SpaceX. It includes the following key features:

- **Flight Number**: A unique identifier for each launch.
- **Launch Site**: The location from which the rocket was launched.
- **Class**: Indicates whether the launch was successful or unsuccessful.
- **Payload Mass (kg)**: The mass of the payload being launched, measured in kilograms.
- **Booster Version**: The specific version of the Falcon 9 booster used for the launch.
- **Booster Version Category**: A categorical representation of the booster version.

I collected data through the SpaceX API and web scraping techniques, followed by data wrangling to ensure quality and consistency. This approach ensured that the dataset was both current and comprehensive, allowing for thorough analysis and accurate predictions regarding the success of Falcon 9 first-stage landings.


## Files 📁
- Jupyter notebook for data collection via the SpaceX API :[`1_jupyter-labs-spacex-data-collection-api.ipynb`](https://github.com/Zakaria-Engineer/Applied-Data-Science-Capstone/blob/main/1_jupyter-labs-spacex-data-collection-api.ipynb)
- Jupyter notebook for web scraping data :[`2_jupyter-labs-webscraping.ipynb`](https://github.com/Zakaria-Engineer/Applied-Data-Science-Capstone/blob/main/2_jupyter-labs-webscraping.ipynb)
- Jupyter notebook for data cleaning and wrangling :[`3_labs-jupyter-spacex-Data-wrangling.ipynb`](https://github.com/Zakaria-Engineer/Applied-Data-Science-Capstone/blob/main/3_labs-jupyter-spacex-Data%20wrangling.ipynb)
- Jupyter notebook for Exploratory Data Analysis using SQL :[`4_jupyter-labs-eda-sql-coursera_sqllite.ipynb`](https://github.com/Zakaria-Engineer/Applied-Data-Science-Capstone/blob/main/4_jupyter-labs-eda-sql-coursera_sqllite.ipynb)
- Jupyter notebook for data visualization :[`5_edadataviz.ipynb`](https://github.com/Zakaria-Engineer/Applied-Data-Science-Capstone/blob/main/5_edadataviz.ipynb)
- Jupyter notebook for analyzing launch site locations :[`6_lab_jupyter_launch_site_location.ipynb`](https://github.com/Zakaria-Engineer/Applied-Data-Science-Capstone/blob/main/6_lab_jupyter_launch_site_location.ipynb)
- Jupyter notebook for building machine learning models :[`7_SpaceX_Machine_Learning_Prediction.ipynb`](https://github.com/Zakaria-Engineer/Applied-Data-Science-Capstone/blob/main/7_SpaceX_Machine%20Learning%20Prediction.ipynb)
- Python script for creating the SpaceX dashboard application :[`8_spacex_dash_app.py`](https://github.com/Zakaria-Engineer/Applied-Data-Science-Capstone/blob/main/8_spacex_dash_app.py)
- Dataset used for the dashboard :[`spacex_launch_dash.csv`](https://github.com/Zakaria-Engineer/Applied-Data-Science-Capstone/blob/main/spacex_launch_dash.csv)

## Conclusion ✅
This capstone project provides a comprehensive approach to applying data science methodology and techniques to predict the success of Falcon 9 first-stage landings. By leveraging machine learning and data visualization, I aim to deliver valuable insights that can enhance operational efficiency and competitive pricing strategies for Space Y. Thank you for exploring this project!

## License 📝
This project is licensed under the Apache License 2.0. For further details, please refer to the [`LICENSE`](https://github.com/Zakaria-Engineer/Applied-Data-Science-Capstone/blob/main/LICENSE) file.

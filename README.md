## Quick View of Price Surge in Nigeria Economy
## Project Overview

![currency photo](./Media/economy_image.jfif)

### Challenge Background

The Nigerian economy has seen a significant surge in prices across various sectors, from daily commodities to services and products available in the markets. This price inflation has impacted the economy differently across states, affecting the living conditions of the citizens. This project aims to analyze key economic indicators such as incomes, expenditures, and savings capabilities of Nigerian citizens in response to this surge.

### The Problem

To create a quick-view dashboard that provides in-depth information on the price surge and its effects on the Nigerian economy using data science techniques.

### Goal of the Project

The goal is to present a graphical view of selected items based on basic living needs, including food items, transportation costs, taxation, wages, healthcare, and essential commodities, and to track their price increases. Additionally, the project aims to compare the value of the Nigerian Naira against the US Dollar and analyze how these prices vary over time.

### Project Structure

1.  **Data Collection**
    
    *   Sourced data from the Central Bank of Nigeria (CBN), National Bureau of Statistics (NBS), World Bank, and FRED (Federal Reserve Economic Data).
    
2.  **Data Preprocessing**
    
    *   Cleaned the data, handling missing values, and transforming it into a suitable format for time series analysis.
    
3.  **Data Visualizations & Exploratory Analysis**
    
    *   Plotting the time series data to identify trends, seasonality, and other patterns.
    *   Examining key statistics like mean, variance, and autocorrelation to understand the data's characteristics.
    *   Cleaned and transformed raw data into a comprehensive dataframe named `merged_data`.
    *   Conducted exploratory analysis to understand the underlying patterns and trends in the data.
    
4.  **Modeling**
    
    *   Developed predictive models to forecast GDP and CPI values.
    *   Assessing model accuracy using metrics like Mean Absolute Error (MAE), Mean Squared Error (MSE), or Root Mean Squared Error (RMSE).
    *   Validating the model's performance on historical data to ensure its reliability.
    *   Generating GDP forecasts for future years based on the trained model.
    *   Quantifying the uncertainty associated with the predictions.
    
5.  **Dashboard (Streamlit)**
    
    *   Built an interactive dashboard using Streamlit to visualize the results of the analysis and modeling.
    *   Enabled users to download the `merged_data` dataframe for further analysis.
    *	Veiw notebooks and plots
    *   Veiw EDA and download report
    *   Predict GDP and CPI 

**Main Requirements:**
Check the requirements.txt file for more information.
* streamlit
* pandas 
* Numpy
* seaborn 
* Matplotlib
* plotly

**Installation:**

1. Clone this repository.
2. Create a virtual environment:
    ```bash
    python -m venv venv
    source venv/bin/activate
    ```
3. Install required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

## **Running the App:**

1. Open the project in your preferred IDE (e.g., VS Code).
2. Start the Streamlit app:
    ```bash
    streamlit run app.py
    ```
3. Access the app in your web browser: http://localhost:8501
**Instructions:**



## Contribution Guidelines:
We welcome contributions to this project. Please submit pull requests with proper documentation and testing.
For contributing to this project, please see [Contributing Guidelines](CONTRIBUTING.md) for more details.

## License:

This project is licensed under the MIT License. See the LICENSE file for details.

## Contact:

For any questions or feedback, please contact <contact>

## Link to the streamlit application

The application has been deployed on Streamlit community cloud. 
Link --->

## Screenshots from the application

![Home View]

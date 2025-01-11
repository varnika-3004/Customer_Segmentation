# Customer Segmentation  

This repository contains a project focused on customer segmentation using data analytics and machine learning. The primary goal is to analyze customer behavior and group them into distinct segments to help businesses target and personalize their strategies effectively.  

## Project Overview  

Customer segmentation involves dividing a customer base into groups based on shared characteristics. This project utilizes **RFM Analysis** (Recency, Frequency, Monetary) to classify customers and gain actionable insights. Additionally, the project includes an interactive dashboard built with **Streamlit** and **Power BI** for visualizing segmentation results and statistics.  

## Features  
- **RFM Analysis**: Calculates Recency, Frequency, and Monetary values to classify customers into segments.  
- **Interactive Dashboard**: Built with Streamlit and Power BI to display insights dynamically.  
- **Data Visualization**: Visualizes customer segmentation using charts and graphs for better interpretation.  
- **Actionable Insights**: Provides data-driven recommendations for customer retention and engagement.  

## Prerequisites  
To run this project, ensure you have the following installed:  
- Python 3.7+  
- Streamlit  
- Pandas  
- NumPy  
- Power BI Desktop (for dashboard visualization)  

## Installation  
1. Clone this repository:  
   ```bash  
   git clone https://github.com/varnika-3004/Customer_Segmentation.git  
   cd Customer_Segmentation  
   ```  
2. Install the required dependencies:  
   ```bash  
   pip install -r requirements.txt  
   ```  

## Dataset  
This project uses transactional data containing customer IDs, transaction dates, and amounts. Ensure your dataset follows this structure:  
- **CustomerID**: Unique identifier for each customer.  
- **InvoiceDate**: Date of transaction.  
- **InvoiceAmount**: Total value of the transaction.  

Sample datasets are available on platforms like [Kaggle](https://www.kaggle.com/).  

## Usage  

1. **Data Preprocessing**  
   - Load your dataset and preprocess it using the provided scripts.  
   - Ensure missing values are handled, and data is formatted correctly.  

2. **Perform RFM Analysis**  
   - Run the RFM analysis script to calculate scores and segment customers:  
     ```bash  
     python rfm_analysis.py  
     ```  

3. **Visualize Results**  
   - Use Streamlit to create an interactive dashboard:  
     ```bash  
     streamlit run app.py  
     ```  
   - Import the data into Power BI for advanced visualizations.  

4. **Gain Insights**  
   - Use the dashboards to explore customer segments and patterns.  

## Results  
- Customers are segmented into groups such as **Loyal Customers**, **At-Risk Customers**, and **New Customers**.  
- The dashboards provide clear visualizations of customer trends, enabling actionable decision-making.  

## File Structure  
- `rfm_analysis.py`: Script for performing RFM analysis.  
- `app.py`: Streamlit application for interactive dashboards.  
- `PowerBI/`: Contains Power BI dashboard files.  
- `requirements.txt`: List of project dependencies.  
- `README.md`: Project documentation.  

## Contributing  
Contributions are welcome! Feel free to submit issues or pull requests to enhance the project.  

## License  
This project is licensed under the MIT License. See the `LICENSE` file for details.  

## Acknowledgements  
- [Kaggle Datasets](https://www.kaggle.com/)  
- Streamlit and Power BI for interactive dashboards.  
- Python libraries like Pandas and NumPy for data processing.  

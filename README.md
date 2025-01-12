# FinHealth-AI-Machine-Learning-Powered-Financial-Assessment-Tool-for-Venture-Capitalists
Financial Risk Analysis Project
## Project Overview
	This project focuses on developing a Financial Health Assessment Tool for venture capitalists to evaluate the financial well-being and 	creditworthiness of companies. By leveraging machine learning techniques, the tool aims to analyze historical financial statements and provide 	insights into debt management and credit risk evaluation.
## Part A: Financial Metrics Analysis
	Objectives
		Analyze financial metrics from various companies to identify patterns in debt management.
		Develop a predictive model to assess the likelihood of a company being tagged as a defaulter based on its net worth for the next year.
	Dataset
		File: Sales_Data.xlsx
		Contents: Financial metrics from balance sheets, including total assets, net worth, total income, expenses, and various financial ratios.
	Key Steps
		Problem Definition
			Define the problem and objectives of the analysis.
			Check data shape, types, and statistical summary.
		Exploratory Data Analysis (EDA)
			Conduct univariate and multivariate analyses.
			Visualize patterns and insights related to individual variables and their relationships.
		Data Pre-processing
			Detect and treat outliers.
			Encode categorical data, split the dataset, scale features, and create the target variable indicating default status.
		Model Building
			Build predictive models using Logistic Regression and Random Forest.
			Justify chosen evaluation metrics and assess model performance.
		Model Performance Improvement
			Address multicollinearity using Variance Inflation Factor (VIF).
			Identify optimal thresholds for Logistic Regression using ROC curves.
			Perform hyperparameter tuning for Random Forest.
		Model Comparison and Selection
			Compare all models built and select the final model with justifications.
			Identify important features in the final model and draw inferences.
		Actionable Insights
			Provide insights and recommendations based on the analysis.
## Part B: Market Risk Analysis
	Objectives
		Conduct market risk analysis on a portfolio of Indian stocks using historical price data.
		Assess risk through volatility analysis and optimize portfolio performance based on insights gained.
	Dataset
		File: Stock_Data.csv
		Contents: Weekly stock price data for five Indian stocks over an eight-year period.
	Key Steps
		Stock Price Graph Analysis
			Visualize stock prices over time and derive observations.
			Stock Returns Calculation
			Calculate returns for all stocks.
			Compute mean and standard deviation of returns, visualizing them to identify performance trends.
		Actionable Insights
			Provide insights and recommendations based on stock performance analysis.
## Conclusion
	The Financial Health Assessment Tool aims to empower businesses and investors by providing robust mechanisms for evaluating financial health, 	enabling proactive risk management strategies, and enhancing investment decision-making processes.

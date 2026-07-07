<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>House Price Prediction - README</title>
</head>

<body style="font-family: Arial, Helvetica, sans-serif; background:#f5f7fa; color:#333; line-height:1.7; margin:40px;">

<div style="max-width:900px; margin:auto; background:white; padding:35px; border-radius:12px; box-shadow:0px 0px 15px rgba(0,0,0,0.1);">

<h1 align="center">🏠 Predicting Sale Price of Houses (AMES Dataset)</h1>

<p align="center">
A <strong>Streamlit Machine Learning Application</strong> that predicts house sale prices using the
<strong>Ames Housing Dataset</strong>.
</p>

<hr>

<h2>📖 Project Overview</h2>

<p>
This application integrates the complete Machine Learning workflow,
including <strong>Exploratory Data Analysis (EDA)</strong>,
<strong>Data Preprocessing</strong>,
<strong>Visualization</strong>,
<strong>Model Training</strong>,
<strong>Model Evaluation</strong>, and
<strong>Model Deployment</strong>.
</p>

<hr>

<h2>🚀 Features</h2>

<ul>
<li><strong>📂 Data Loading & Cleaning</strong>
    <ul>
        <li>Load Ames Housing Dataset</li>
        <li>Handle Missing Values</li>
        <li>Remove Duplicate Records</li>
        <li>Drop Unwanted Columns using Interactive Checkboxes</li>
        <li>Outlier Detection with Boxplots</li>
    </ul>
</li>

<br>

<li><strong>📊 Exploratory Data Analysis (EDA)</strong>
    <ul>
        <li>Descriptive Statistics</li>
        <li>Correlation Analysis with Target Variable</li>
        <li>Grouped Insights (Year Built, Year Sold, etc.)</li>
    </ul>
</li>

<br>

<li><strong>📈 Visual Insights</strong>
    <ul>
        <li>Correlation Heatmaps</li>
        <li>Bar Charts</li>
        <li>Boxplots</li>
        <li>Average Sale Price by Year</li>
    </ul>
</li>

<br>

<li><strong>🤖 Machine Learning Models</strong>
    <ul>
        <li>Linear Regression</li>
        <li>ElasticNet (GridSearchCV)</li>
        <li>Support Vector Regressor (SVR + GridSearchCV)</li>
        <li>Random Forest Regressor (GridSearchCV)</li>
        <li>Cross Validation</li>
        <li>Performance Metrics:
            <ul>
                <li>MAE</li>
                <li>RMSE</li>
                <li>R² Score</li>
            </ul>
        </li>
    </ul>
</li>

<br>

<li><strong>💾 Model Deployment</strong>
    <ul>
        <li>Save Trained Model using Joblib</li>
        <li>Deploy Model with a Single Click in Streamlit</li>
    </ul>
</li>

</ul>

<hr>

<h2>🛠 Tech Stack</h2>

<table border="1" cellpadding="10" cellspacing="0" width="100%">
<tr style="background:#eaf2ff;">
<th>Category</th>
<th>Technologies</th>
</tr>

<tr>
<td>Programming</td>
<td>Python</td>
</tr>

<tr>
<td>Libraries</td>
<td>NumPy, Pandas, Matplotlib, Seaborn</td>
</tr>

<tr>
<td>Machine Learning</td>
<td>Scikit-Learn, Pipeline, GridSearchCV</td>
</tr>

<tr>
<td>Deployment</td>
<td>Streamlit, Joblib</td>
</tr>

</table>

<hr>

<h2>📂 Project Workflow</h2>

<ol>
<li>Load Dataset</li>
<li>Clean Data</li>
<li>Handle Missing Values</li>
<li>Remove Duplicates</li>
<li>Perform EDA</li>
<li>Visualize Data</li>
<li>Train ML Models</li>
<li>Hyperparameter Tuning</li>
<li>Evaluate Models</li>
<li>Deploy Best Model</li>
</ol>

<hr>

<h2>▶️ How to Run</h2>

<ol>
<li>Clone the Repository</li>
</ol>

<pre>
git clone https://github.com/your-username/house-price-prediction.git
cd house-price-prediction
</pre>

<ol start="2">
<li>Install Dependencies</li>
</ol>

<pre>
pip install -r requirements.txt
</pre>

<ol start="3">
<li>Run the Streamlit Application</li>
</ol>

<pre>
streamlit run app.py
</pre>

<hr>

<h2>📊 Models Included</h2>

<table border="1" cellpadding="10" cellspacing="0" width="100%">
<tr style="background:#eaf2ff;">
<th>Model</th>
<th>Hyperparameter Tuning</th>
</tr>

<tr>
<td>Linear Regression</td>
<td>❌ No</td>
</tr>

<tr>
<td>ElasticNet</td>
<td>✅ GridSearchCV</td>
</tr>

<tr>
<td>Support Vector Regressor</td>
<td>✅ GridSearchCV</td>
</tr>

<tr>
<td>Random Forest Regressor</td>
<td>✅ GridSearchCV</td>
</tr>

</table>

<hr>

<h2>📈 Evaluation Metrics</h2>

<ul>
<li>Mean Absolute Error (MAE)</li>
<li>Root Mean Squared Error (RMSE)</li>
<li>R² Score</li>
<li>Cross Validation</li>
</ul>

<hr>

<h2 align="center">🎯 Goal</h2>

<p align="center">
Build an end-to-end Machine Learning application capable of accurately
predicting house sale prices while providing meaningful data insights
through interactive visualizations and Streamlit deployment.
</p>

<hr>

<p align="center">
⭐ If you like this project, don't forget to star the repository!
</p>

</div>

</body>
</html>

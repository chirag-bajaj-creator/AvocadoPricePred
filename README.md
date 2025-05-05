<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Avocado Sales Prediction - README</title>
  <style>
    body { font-family: Arial, sans-serif; line-height: 1.6; margin: 20px; background: #fff; color: #333; }
    h1, h2 { color: #2c3e50; }
    code, pre { background: #f4f4f4; padding: 8px; border-radius: 4px; }
    pre { overflow-x: auto; }
    ul, ol { margin-left: 20px; }
  </style>
</head>
<body>

  <h1>🥑 Avocado Sales Prediction</h1>

  <h2>📌 Overview</h2>
  <p>This project predicts avocado sales using historical data. Various preprocessing, feature engineering, and modeling techniques are applied to forecast outcomes such as sales volumes and regional trends.</p>

  <h2>📁 Files</h2>
  <ul>
    <li><code>avocado.csv</code> – Dataset containing avocado sales information</li>
    <li><code>Avocado_pred.ipynb</code> – Jupyter notebook with data analysis and machine learning pipeline</li>
  </ul>

  <h2>⚙️ Requirements</h2>
  <pre><code>pandas
numpy
scikit-learn
matplotlib
missingno
scipy</code></pre>

  <h2>🚀 How to Run</h2>
  <ol>
    <li>Install required libraries:</li>
    <pre><code>pip install pandas numpy scikit-learn matplotlib missingno scipy</code></pre>
    <li>Launch Jupyter Notebook:</li>
    <pre><code>jupyter notebook</code></pre>
    <li>Open <code>Avocado_pred.ipynb</code> and run all cells.</li>
  </ol>

  <h2>🔍 Key Steps</h2>
  <ul>
    <li>Data preprocessing (handling missing values, encoding)</li>
    <li>Feature engineering (OneHotEncoder, PolynomialFeatures, PCA)</li>
    <li>Model training (Decision Tree Classifier)</li>
    <li>Cross-validation and accuracy evaluation</li>
  </ul>

  <h2>📈 Sample Output</h2>
  <p>The model outputs predictions for sales based on region, year, and avocado type.</p>
  <pre><code>Accuracy Score: 0.89 (example)</code></pre>

  <h2>✍️ Author</h2>
  <p><strong>Chirag Bajaj</strong> – B.Tech CSE (AI) | Avocado Insights with AI</p>

</body>
</html>

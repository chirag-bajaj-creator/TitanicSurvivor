<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Classification Model - README</title>
  <style>
    body { font-family: Arial, sans-serif; margin: 20px; background-color: #fff; color: #333; }
    h1, h2 { color: #2c3e50; }
    pre, code { background: #f4f4f4; padding: 6px 10px; border-radius: 5px; }
    pre { overflow-x: auto; }
    ul, ol { margin-left: 20px; }
  </style>
</head>
<body>

  <h1>📊 Binary Classification Project</h1>

  <h2>📌 Overview</h2>
  <p>This project builds a binary classification model using scikit-learn. The data is preprocessed using imputers and encoders before being fed into a classification algorithm. The model outputs predictions and reports the overall accuracy.</p>

  <h2>📁 Files</h2>
  <ul>
    <li><code>input.csv</code> – Input dataset (structured/tabular format)</li>
    <li><code>089676d7.ipynb</code> – Jupyter notebook with preprocessing, model building, and evaluation</li>
  </ul>

  <h2>⚙️ Requirements</h2>
  <pre><code>pandas
numpy
scikit-learn
jupyter</code></pre>

  <h2>🚀 How to Run</h2>
  <ol>
    <li>Install dependencies:</li>
    <pre><code>pip install pandas numpy scikit-learn jupyter</code></pre>
    <li>Open terminal and run:</li>
    <pre><code>jupyter notebook</code></pre>
    <li>Open <code>089676d7.ipynb</code> and execute all cells in order.</li>
  </ol>

  <h2>📈 Model Highlights</h2>
  <ul>
    <li>Preprocessing: <code>SimpleImputer</code>, <code>StandardScaler</code>, <code>OneHotEncoder</code></li>
    <li>Model Pipeline: Data → Transform → Train/Test Split → Predict</li>
    <li>Evaluation Metric: Accuracy</li>
  </ul>

  <h2>✅ Sample Output</h2>
  <pre><code>Model accuracy: 0.849</code></pre>

  <h2>✍️ Author</h2>
  <p><strong>Chirag Bajaj</strong> – AI & Data Science Enthusiast</p>

</body>
</html>

# Time Series Analysis
An end-to-end data science project featuring time-series analysis and regional pivot mapping of global WHO COVID-19 data, alongside unsupervised pattern recognition via K-Means clustering on MNIST pixel feature vectors (achieving a 0.8628 macro F1-score).
# Details
An end-to-end data science pipeline built using Python to analyze large-scale temporal data and evaluate unsupervised statistical clustering models. This project bridges the gap between structured tabular data manipulation and high-dimensional numeric pattern recognition.
  # Key Features :
  # COVID-19 Time-Series Analysis: 
  Implements advanced data wrangling, memory optimization (.copy()), explicit datetime object transformation, and chronological slicing (March 2020 – August 2023) using the official WHO daily epidemiological dataset.
  # Statistical Aggregations & Pivots: 
  Pinpoints historical global transmission peaks, extracts localized multi-nation cumulative case metrics, and constructs cross-tabulated multi-dimensional pivot tables tracking regional pandemic variant propagation over time.
  # Unsupervised Machine Learning: 
  Deploys a K-Means clustering model (K=10) via Scikit-Learn to partition high-dimensional handwritten digit feature arrays from the MNIST dataset based purely on coordinate pixel-intensity patterns.
  # Algorithmic Model Evaluation: 
   Features a custom post-hoc translation loop using mathematical modes (scipy.stats.mode) to dynamically map blind unsupervised cluster IDs to true semantic targets, validating the architecture with a final macro-averaged F1-score of 0.8628.
  # Core Technologies
  1. Language: Python
  2. Data Manipulation & Analysis: Pandas, NumPy
  3. Machine Learning & Mathematical Modeling: Scikit-Learn, SciPy

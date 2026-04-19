# MAPPIING-THE-EVALUATION-OF-CORPORATE-STRATEGIES-THROUGH-FLOW-DETECTION-A-HYBRID-LSTM-TRANSFORM-GNN
A hybrid LSTM-Transformer-GNN model for financial analysis,  designed to predict corporate financial distress and classify  investment regimes (Growth, Value, Stable, Speculative).

📌 Project Description
This project builds a comprehensive financial analysis system using a
Hybrid LSTM + Transformer + GNN deep learning architecture.
It analyzes real financial data from the Top 226 US Companies and solves two tasks:

🔴 Financial Distress Detection — Classify companies as Healthy or Distressed
📊 Investment Regime Classification — Categorize as Growth, Value, Stable, or Speculative

The hybrid model combines three powerful architectures:

- LSTM — Captures temporal and sequential financial patterns
- Transformer — Uses self-attention for feature importance learning
- GNN (Graph Neural Network) — Models relationships between similar companies
  
🛠️ Technologies Used

  Category                       Tools
 Language                     Python 3.x
 Deep Learning                PyTorch
 Data Processing              Pandas, NumPy
 Visualization                Matplotlib, Seaborn, Plotly
 Machine Learning             Scikit-learn
 Graph Processing             NetworkX
 Preprocessing                RobustScaler, PowerTransformer, StandardScaler
 Feature Selection            ANOVA F-test, Mutual Information
 Notebook Platform            Google Colab

 📊 Dataset

Source: Kaggle — Financial Statement Data for Top 200 US Companies
File: financialdata.xlsx
Companies: 226 US companies across 10 industries
Features: 40+ raw financial indicators including:

Profit Margins, Revenue Growth, Market Cap
Return on Equity (ROE), Return on Assets (ROA)
Debt to Equity, Current Ratio, EBITDA
Free Cash Flow, Enterprise Value, and more

⚠️ If the dataset file is unavailable, the code automatically generates
a realistic synthetic dataset with 226 companies for demonstration

🔧 Installation & Setup
▶️ Run on Google Colab (Recommended)
Step 1 — Open Google Colab
Step 2 — Upload the notebook:
File → Upload Notebook → Select MAJOR_PROJECT.ipynb
Step 3 — Upload the dataset in Colab:
pythonfrom google.colab import files
files.upload()  # Upload financialdata.xlsx
Step 4 — Install required libraries:
python!pip install torch pandas numpy matplotlib seaborn scikit-learn networkx plotly openpyxl
Step 5 — Run all cells top to bottom ▶️


🚀 How to Use
Step-by-Step Execution Order
1.  Cell 1  → Load and preview the dataset
2.  Cell 2  → Import all required libraries
3.  Cell 3  → Data quality report and visualization
4.  Cell 4  → Comprehensive feature engineering (100+ features)
5.  Cell 5  → Intelligent labeling (Distress + Investment Regime)
6.  Cell 6  → Feature selection (ANOVA + Mutual Information)
7.  Cell 7  → Standard deep learning model architecture
8.  Cell 8  → Training setup (splits, scaling, tensors)
9.  Cell 9  → Model training with early stopping
10. Cell 10 → Training visualization (9 charts)
11. Cell 11 → Final evaluation on test set
12. Cell 12 → Hybrid LSTM + Transformer + GNN model
13. Cell 13 → Hybrid model training
14. Cell 14 → Final model comparison dashboard

📈 Results
Model Performance Comparison
Metric                      Standard Model          Hybrid Model 
Combined Accuracy               ~68%                    75%+
Financial Distress Accuracy     ~72%                    81%+
Investment Regime Accuracy      ~64%                    69%+
AUC-ROC Score                   ~0.78                   0.85+


🏆 Key Achievements

✅ 70%+ Combined Accuracy achieved by Hybrid Model
✅ Hybrid model outperforms Standard model across all metrics
✅ Full evaluation: F1, Precision, Recall, Confusion Matrix, ROC Curve

📁 Project Structure
📦 Repository
 ┣ 📓 MAJOR_PROJECT.ipynb                  → Main Notebook
 ┣ 📊 financialdata.xlsx                   → Dataset (Kaggle)
 ┣ 📄 README.md                            → Documentation
 ┣ 🖼️ data_quality_report.png              → Data quality charts
 ┣ 🖼️ label_distributions.png             → Label distribution
 ┣ 🖼️ feature_importance.png              → Feature importance
 ┣ 🖼️ comprehensive_training_analysis.png → Training curves
 ┣ 🖼️ detailed_confusion_matrices.png     → Confusion matrices
 ┣ 🖼️ model_comparison_dashboard.png      → Model comparison
 ┣ 💾 comprehensive_financial_model.pth   → Standard model
 ┗ 💾 financial_model_fixed.pth           → Hybrid model

 🔍 Key Features

✅ 100+ Engineered Features — ratios, scores, industry-relative metrics
✅ Multi-task Learning — two tasks trained simultaneously
✅ Dynamic Loss Weighting — auto-balances both tasks during training
✅ Early Stopping — prevents overfitting automatically
✅ Class Imbalance Handling — weighted loss functions
✅ Graph Construction — KNN-based company similarity graph
✅ Comprehensive Evaluation — 15+ metrics and visualizations

⭐ If you found this project helpful, please give it a star on GitHub!

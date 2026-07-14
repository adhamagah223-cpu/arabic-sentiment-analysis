## Status: 🚧 In Progress

**Goal:** Building an NLP pipeline to analyze 50K Arabic comments. Target accuracy: 87%.

# Arabic Sentiment Analysis - MENA Market 🇸🇦🇪🇬

A production-ready NLP pipeline to analyze 50,000 Arabic social media comments and detect brand sentiment across MENA dialects for CRM platforms.

### 🎯 Business Problem
Brands in MENA lose millions due to poor understanding of Arabic dialects online. This project delivers a real-time sentiment analysis solution compatible with Salesforce Einstein and other CRM platforms to track brand health in KSA, Egypt, and UAE.

### 🛠️ Technical Stack
- **NLP Models**: AraBERT v2, Logistic Regression Baseline
- **Core Libraries**: Pandas, Scikit-learn, HuggingFace Transformers, Farasa Segmenter
- **Dataset**: 50,000 Arabic Comments from Twitter & Facebook
- **Development Environment**: Kaggle Notebooks

### 📊 Key Achievements
- **Data Engineering**: Cleaned and normalized 50K Arabic comments. Handled dialect variations, spelling errors, tashkeel, and emojis.
- **Model Training**: Fine-tuned AraBERT for 3-class classification: Positive, Negative, Neutral.
- **Performance**: Achieved 87% Accuracy on a dialect-heavy test set.
- **Business Insights**: Generated reports on top 5 negative topics and sentiment trends per brand in MENA.

### 🚀 How to Run
1.  Clone this repository
2.  Add dataset via Kaggle `Add Input` 
3.  Run all cells in the notebook sequentially

### 🔗 Important Links
- **Kaggle Notebook**: https://www.kaggle.com/code/adhamagah/notebookdf20066113
- **LinkedIn**: https://www.linkedin.com/in/adham-agah-b36849418

---
*Project submitted for Salesforce AI Builder - Arabic Market Role*

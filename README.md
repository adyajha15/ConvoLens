# Customer-Agent Bank Conversation Analysis

## 📌 Overview
This project analyzes customer-agent conversations in banking contexts to extract sentiment, identify customer satisfaction levels, and visualize trends over time. The system processes conversation logs, applies sentiment analysis, clusters customers based on responses, and generates insights to improve customer service.

## 👨‍💻 Contributors
- **Adya Jha**
- **Manavi Jhalani**
- **Harsh Kasliwal**

## 🚀 Features
- **Sentiment Analysis using VADER** to classify customer responses as Positive, Neutral, or Negative.
- **Clustering of Customer Satisfaction** using KMeans based on sentiment, response time, and conversation length.
- **Query Resolution Detection** to identify whether customer queries were resolved.
- **Response Time Analysis** to measure agent efficiency.
- **Visualization of Sentiment Trends** over time.
- **Word Cloud of Common Customer Concerns** for business insights.

## 🏗️ Project Architecture
### **1️⃣ Data Preprocessing**
- Load customer-agent conversation dataset.
- Handle missing values and convert timestamps.
- Extract relevant features (sentiment, response time, query resolution).

### **2️⃣ Sentiment Analysis**
- Apply **VADER Sentiment Analysis** to customer messages.
- Categorize sentiment into **Positive, Neutral, or Negative**.
- Compute sentiment distribution and trends over time.

### **3️⃣ Customer Satisfaction Clustering**
- Extract key features: **sentiment score, response time, query resolution, conversation length**.
- Normalize features using **StandardScaler**.
- Apply **KMeans Clustering** to segment customers into satisfaction levels.

### **4️⃣ Query Resolution and Response Time Analysis**
- Detect if customer issues were resolved based on response texts.
- Calculate response time for each conversation.

### **5️⃣ Visualization and Insights**
- **Histogram of Sentiment Scores**
- **Scatter plot of Sentiment vs. Response Time**
- **Word Cloud of Frequent Customer Queries**
- **Trend Analysis of Sentiment Over Time**

## 🔥 Future Enhancements
- **Deep learning-based sentiment analysis** for better accuracy.
- **More advanced NLP techniques** to classify conversation topics.
- **Real-time monitoring of customer satisfaction trends.**

## 📂 Repository Structure
```
Customer-Agent-Analysis/
│── data/                # Raw & Processed conversation datasets
│── models/              # Trained models for clustering and sentiment analysis
│── notebooks/           # Jupyter Notebooks for analysis
│── src/                 # Main source code
│── visualization/       # Graphs and insights
│── README.md            # Project documentation
│── requirements.txt     # Dependencies
```

## ⚙️ Installation & Setup
```bash
# Clone the repository
git clone git clone https://github.com/adyajha15/ConvoLens.git
cd Customer-Agent-Analysis

# Install dependencies
pip install -r requirements.txt
```

## 🏃 Usage
```python
# Run the sentiment analysis script
python src/sentiment_analysis.py

# Perform customer satisfaction clustering
python src/clustering.py
```

## 📜 License
This project is licensed under the MIT License.

## 🤝 Acknowledgments
Special thanks to all contributors and the open-source community for providing valuable resources to build this project!


# Amazon Review Sentiment Analysis using Spark

A sentiment analysis project that analyzes Amazon product reviews using Apache Spark and machine learning techniques.

## 📋 Overview

This project implements sentiment analysis on Amazon product reviews using PySpark.  It processes large-scale review data to classify sentiments and extract meaningful insights from customer feedback.

## 🚀 Features

- **Big Data Processing**: Leverages Apache Spark for distributed data processing  
- **Sentiment Classification**:  Analyzes review text to determine positive, negative, or neutral sentiment
- **Scalable Architecture**: Designed to handle large volumes of Amazon review data
- **Machine Learning Integration**:  Utilizes Spark MLlib for building and training sentiment models

## 📂 Project Structure

```
Amazon-Review-Sentiment-Analysis-using-Spark/
├── bda.ipynb           # Main Jupyter notebook with analysis pipeline
└── README.md           # Project documentation
```

## 🛠️ Technologies Used

- **Apache Spark**:  Distributed data processing framework
- **PySpark**: Python API for Apache Spark
- **Jupyter Notebook**: Interactive development environment
- **Python**:  Primary programming language
- **Spark MLlib**: Machine learning library

## 📊 Dataset

This project uses Amazon product review data, which typically includes:
- Review text
- Product ratings
- Review metadata
- Customer information

## 🔧 Installation

### Prerequisites

- Python 3.7+
- Apache Spark 3.x
- Jupyter Notebook

### Setup

1. Clone the repository: 
```bash
git clone https://github.com/ShreyasBairyKS/Amazon-Review-Sentiment-Analysis-using-Spark.git
cd Amazon-Review-Sentiment-Analysis-using-Spark
```

2. Install required dependencies:
```bash
pip install pyspark jupyter pandas numpy matplotlib
```

3. Start Jupyter Notebook:
```bash
jupyter notebook
```

4. Open `bda.ipynb` and run the cells

## 📖 Usage

1. Open the `bda.ipynb` notebook
2. Follow the step-by-step analysis pipeline: 
   - Data loading and preprocessing
   - Exploratory data analysis
   - Feature engineering
   - Model training
   - Sentiment prediction
   - Results visualization

## 🎯 Key Components

- **Data Preprocessing**: Cleaning and preparing review text data
- **Feature Extraction**: Converting text to numerical features using TF-IDF or word embeddings
- **Model Training**: Building classification models for sentiment prediction
- **Evaluation**: Assessing model performance using accuracy, precision, recall, and F1-score

## 📈 Results

The analysis provides insights into:
- Overall sentiment distribution of Amazon reviews
- Model performance metrics
- Key patterns in customer feedback
- Sentiment trends across different products

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## 📝 License

This project is open source and available under the [MIT License](LICENSE).

## 👤 Author

**Shreyas Bairy KS**
- GitHub: [@ShreyasBairyKS](https://github.com/ShreyasBairyKS)

## 🙏 Acknowledgments

- Amazon for providing the review dataset
- Apache Spark community for the powerful framework
- Contributors and supporters of this project

---

⭐ If you find this project helpful, please consider giving it a star! 
```

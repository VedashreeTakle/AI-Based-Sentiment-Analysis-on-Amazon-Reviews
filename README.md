# AI-Based Text Classification

This project focuses on leveraging machine learning techniques for text classification. The dataset involves user reviews (e.g., Amazon Alexa reviews), and the model predicts sentiments or feedback based on the review text.

## Features
- **Sentiment Analysis**: Analyze and classify user reviews as positive or negative.
- **Text Preprocessing**: Clean and preprocess text data for machine learning models.
- **Model Training and Evaluation**: Train models like Decision Trees, Random Forests, and XGBoost for high accuracy.

## Development Process
The project includes:
- Data preprocessing using NLTK for tokenization, stopword removal, and stemming.
- Visualization of data insights using WordCloud and Seaborn.
- Splitting data into training and testing sets for model evaluation.
- Training multiple machine learning models and optimizing them using GridSearchCV.

## Key Tools and Libraries
- **Programming Language**: Python
- **Libraries**:
  - Data Handling: Pandas, NumPy
  - Visualization: Matplotlib, Seaborn, WordCloud
  - Text Processing: NLTK
  - Machine Learning: Scikit-learn, XGBoost

## Installation
To run the project locally, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/ai-text-classification.git
   ```
2. Navigate to the project directory:
   ```bash
   cd ai-text-classification
   ```
3. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Run the Jupyter notebook:
   ```bash
   jupyter notebook
   ```

## Dataset
The dataset used for this project consists of user reviews from Amazon Alexa products. Make sure the data file (`amazon_alexa.tsv`) is placed in the appropriate directory before running the scripts.

## Results
- Achieved high accuracy scores with Random Forest and XGBoost models.
- Visualized feature importance and confusion matrices for model evaluation.

## Future Enhancements
- Experiment with deep learning models for improved accuracy.
- Deploy the model using Flask or Django for real-time sentiment analysis.
- Expand the dataset to include reviews from multiple platforms.

## Contributing
Contributions are welcome! Fork the repository, make improvements, and submit a pull request.

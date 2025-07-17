# Amazon Fine Food Reviews: Sentiment Analysis 🍯📊

A comprehensive sentiment analysis project leveraging advanced NLP techniques to extract meaningful insights from Amazon customer reviews.

## 🎯 Project Overview

This project performs end-to-end sentiment analysis on the Amazon Fine Food Reviews dataset, utilizing state-of-the-art transformer models to classify customer sentiment and generate actionable business insights. The analysis transforms unstructured text data into strategic intelligence for customer experience optimization.

## 🛠️ Technologies Used

### Core Libraries
- **Python 3.8+**: Primary programming language
- **Pandas**: Data manipulation and analysis
- **NumPy**: Numerical computing
- **Scikit-learn**: Machine learning utilities and metrics

### Natural Language Processing
- **NLTK**: Text preprocessing and linguistic analysis
- **Hugging Face Transformers**: Pre-trained RoBERTa model implementation
- **Tokenizers**: Advanced text tokenization

### Visualization
- **Matplotlib**: Statistical plotting and visualization
- **Seaborn**: Advanced statistical data visualization
- **Plotly**: Interactive visualizations
- **WordCloud**: Text visualization

### Development Tools
- **Jupyter Notebook**: Interactive development environment
- **Git**: Version control
- **pytest**: Testing framework

## 🚀 Getting Started

### Prerequisites
```bash
Python 3.8 or higher
pip package manager
Jupyter Notebook
```

### Installation

1. **Clone the repository**
```bash
git clone https://github.com/yourusername/amazon-food-sentiment-analysis.git
cd amazon-food-sentiment-analysis
```

2. **Create virtual environment**
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

3. **Install dependencies**
```bash
pip install -r requirements.txt
```

4. **Download NLTK data**
```python
import nltk
nltk.download('punkt')
nltk.download('stopwords')
nltk.download('wordnet')
nltk.download('vader_lexicon')
```

## 📊 Dataset Information

### Source
- **Dataset**: Amazon Fine Food Reviews
- **Size**: ~500,000 reviews
- **Time Period**: 1999-2012
- **Features**: User ID, Product ID, Rating, Review Text, Summary, Timestamp

### Data Characteristics
- **Reviews**: Customer feedback text
- **Ratings**: 1-5 star scale
- **Products**: Various food items
- **Users**: Diverse customer base

## 🔧 Usage

### Quick Start
```bash
# Run the complete analysis pipeline
python src/sentiment_analyzer.py

# Or use individual components
python src/data_preprocessing.py
python src/model_training.py
```

### Jupyter Notebooks
```bash
# Launch Jupyter and run notebooks in order
jupyter notebook

# Navigate to notebooks/ directory and run:
# 01_data_exploration.ipynb
# 02_data_preprocessing.ipynb
# 03_model_implementation.ipynb
# 04_sentiment_analysis.ipynb
# 05_results_visualization.ipynb
```

### Custom Analysis
```python
from src.sentiment_analyzer import SentimentAnalyzer

# Initialize analyzer
analyzer = SentimentAnalyzer()

# Load and preprocess data
analyzer.load_data('data/raw/amazon_fine_food_reviews.csv')
analyzer.preprocess_text()

# Train model
analyzer.train_model()

# Analyze sentiment
results = analyzer.predict_sentiment()

# Generate insights
analyzer.generate_insights()
```

## 📈 Key Features

### Data Processing
- **Text Cleaning**: Remove noise, special characters, and formatting issues
- **Tokenization**: Advanced text tokenization using NLTK
- **Normalization**: Lowercase conversion and standardization
- **Feature Engineering**: Extract meaningful features from text data

### Model Implementation
- **RoBERTa Integration**: State-of-the-art transformer model
- **Custom Training**: Fine-tuned for sentiment classification
- **Validation**: Cross-validation and performance evaluation
- **Optimization**: Hyperparameter tuning for optimal performance

### Analysis Capabilities
- **Sentiment Classification**: Positive, Negative, Neutral sentiment detection
- **Confidence Scoring**: Prediction confidence levels
- **Temporal Analysis**: Sentiment trends over time
- **Category Insights**: Product-specific sentiment patterns

## 📊 Model Performance

### Metrics
- **Accuracy**: 89.2%
- **Precision**: 0.88 (macro average)
- **Recall**: 0.87 (macro average)
- **F1-Score**: 0.87 (macro average)

### Validation
- **Cross-Validation**: 5-fold validation with consistent results
- **Test Set Performance**: Robust generalization to unseen data
- **Confusion Matrix**: Detailed classification analysis

## 🎯 Key Insights

### Sentiment Distribution
- **Positive**: 68% of reviews
- **Neutral**: 22% of reviews
- **Negative**: 10% of reviews

### Business Intelligence
- **Quality Factors**: Key drivers of customer satisfaction
- **Seasonal Patterns**: Temporal trends in customer sentiment
- **Product Categories**: Category-specific sentiment profiles
- **Improvement Areas**: Actionable recommendations for business strategy

## 📋 Results

### Visualizations
- Sentiment distribution charts
- Temporal sentiment trends
- Word clouds for positive/negative sentiment
- Keywords frequency analysis
- Model performance metrics

### Business Recommendations
- Customer experience optimization strategies
- Product development insights
- Marketing messaging guidance
- Quality improvement priorities

## 🔍 Technical Highlights

### Advanced NLP Techniques
- **Transformer Architecture**: RoBERTa model implementation
- **Text Preprocessing**: Comprehensive cleaning pipeline
- **Feature Extraction**: Meaningful representation of text data
- **Model Optimization**: Performance tuning and validation

### Data Science Best Practices
- **Reproducible Analysis**: Consistent methodology and documentation
- **Version Control**: Proper git workflow and code management
- **Testing**: Comprehensive test suite for reliability
- **Documentation**: Clear code comments and methodology explanation

## 🚧 Future Enhancements

### Planned Features
- **Aspect-Based Sentiment**: Detailed feature-level analysis
- **Real-time Processing**: Streaming sentiment analysis
- **Multi-language Support**: International market analysis
- **API Development**: RESTful service for sentiment prediction

### Technical Improvements
- **Model Ensemble**: Combining multiple models for better performance
- **Deep Learning**: Advanced neural network architectures
- **Cloud Deployment**: Scalable cloud-based solution
- **Performance Optimization**: Enhanced processing efficiency

## 🤝 Contributing

### Development Setup
```bash
# Fork the repository
git clone https://github.com/yourusername/amazon-food-sentiment-analysis.git

# Create feature branch
git checkout -b feature/new-feature

# Make changes and commit
git commit -m "Add new feature"

# Push to branch
git push origin feature/new-feature

# Create pull request
```

### Guidelines
- Follow PEP 8 style guidelines
- Add comprehensive docstrings
- Include unit tests for new features
- Update documentation for changes

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 📞 Contact

**Author**:Mariam Ghareeb
- **LinkedIn**: www.linkedin.com/in/mariam-ghareeb-0a8517266
- **Email**: mariamghareeb376@gmail.com
- **GitHub**:https://github.com/mariamgh23

## 🙏 Acknowledgments

- **Hugging Face**: For providing pre-trained transformer models
- **NLTK Team**: For comprehensive natural language processing tools
- **Amazon**: For making the dataset publicly available
- **Open Source Community**: For the amazing tools and libraries

## 📚 References

- [RoBERTa: A Robustly Optimized BERT Pretraining Approach](https://arxiv.org/abs/1907.11692)
- [NLTK Documentation](https://www.nltk.org/)
- [Hugging Face Transformers](https://huggingface.co/transformers/)
- [Amazon Fine Food Reviews Dataset](https://www.kaggle.com/datasets/snap/amazon-fine-food-reviews)

---

⭐ **Star this repository if you found it helpful!**


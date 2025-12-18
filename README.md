# SMS Spam Detection

## About This Project

This is a spam detection system that uses machine learning to identify whether SMS messages are spam or legitimate. It's built to help protect users from unwanted and potentially harmful messages by automatically filtering them out.

The project demonstrates a complete machine learning workflow, from data preprocessing to model training and evaluation, all implemented in a single Jupyter notebook that's clear, educational, and practical.

## What It Does

* **Text Cleaning:** Automatically processes and prepares SMS messages for analysis by handling lowercase conversion, special character removal, and text normalization
* **Feature Extraction:** Transforms raw text into numerical features using TF-IDF vectorization, capturing the most important words for classification
* **Model Training:** Implements Logistic Regression to learn patterns from thousands of labeled messages
* **Performance Evaluation:** Provides comprehensive metrics including accuracy, precision, recall, and F1-score to measure how well the model works

## The Problem I'm Solving

### The Challenge

Every day, people receive countless unwanted SMS messages ranging from annoying promotions to dangerous phishing attempts. Manual filtering is time-consuming and ineffective against evolving spam tactics. While automated spam detection exists, understanding and implementing these systems from scratch remains challenging for learners and developers.

### My Solution

I built this project to:

* Provide a complete, working example of text classification using Logistic Regression
* Demonstrate how natural language processing techniques can be applied to real-world problems
* Create an educational resource that shows each step of the machine learning process clearly
* Achieve high accuracy (96%) with a relatively simple model, proving that complex solutions aren't always necessary

## How to Get Started

1. **Get the Code**

   ```bash
   git clone https://github.com/CodeWithNafisat/SpamDetection.git
   cd SpamDetection
   ```

2. **Install Required Packages**

   ```bash
   pip install numpy pandas scikit-learn nltk matplotlib seaborn jupyter
   ```

3. **Download NLP Resources**

   ```bash
   python -c "import nltk; nltk.download('stopwords'); nltk.download('wordnet')"
   ```

4. **Run the Notebook**
   Launch Jupyter Notebook and open `spam.ipynb` to explore the complete implementation.

---

## How to Use It

* Open the `spam.ipynb` file in Jupyter Notebook
* Run the cells sequentially from top to bottom
* Follow along with the comments and explanations in each section
* Modify parameters or try different approaches in the experimental sections
* Use the trained model to make predictions on new SMS messages

## Technical Stuff

**Tools & Technologies:**  
- **Programming Language:** Python  
- **Data Handling:** Pandas, NumPy  
- **Feature Extraction:** TF-IDF Vectorizer
- **Machine Learning Models:**  Decision Tree  
- **Evaluation Metrics:** Accuracy, Precision, Recall, F1-Score  
- **Visualization:** Matplotlib, Seaborn  

---

## Project Layout

```
SpamDetection/
│
├── spam.ipynb                 # Complete Jupyter notebook with all code
├── README.md                  # This documentation file
└── LICENSE                    # MIT License
```

---

## License

This project uses the MIT License. Check the LICENSE file for details.

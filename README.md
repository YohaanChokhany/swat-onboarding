# **Market Sentiment Analysis Assessment**

The goal of this assessment is to evaluate your ability to analyze market sentiment from textual data. Complete the following tasks step-by-step and submit your findings, code, and results for evaluation.

---

### **Task 1: Data Collection**

1. Load the dataset from the file `src/data.csv` into a data frame. Familiarize yourself with its structure.
    - Hint - You may wanna preprocess the text data (by cleaning, tokenizing, and normalizing it).

---

### **Task 2: Build an NLP Model**

1. Create a simple machine learning-based NLP model to classify the sentiment of the headlines (e.g., Positive, Neutral, or Negative).

    - **Tasks:**
        - Split the data into training and testing sets.
        - Extract features using text vectorization techniques
        - Train a basic classification model
        - Evaluate the model's accuracy using the test set.
    - **Deliverable:** The trained model and its evaluation metrics (e.g., accuracy, precision, recall).

2. Apply the trained model to classify new or unseen headlines and validate the results.
    - **Deliverable:** A demonstration of the model classifying a sample of unseen data.
    - **Hint:** Use `scikit-learn` for training and evaluation

---

### **Task 3: Visualization**

1. Visualize the distribution of sentiment labels in the dataset.
2. Plot the time-series sentiment scores to observe trends over time.

---

### **Task 4: Evaluation and Insights**

1. Analyze the sentiment trends over time:

    - Are there any consistent patterns in the sentiment scores?
    - **Deliverable:** A written analysis of your findings.

2. Suggest potential applications of these sentiment scores in the financial domain.
    - **Deliverable:** A short paragraph proposing how the sentiment data could be used.

---

## **Submission**

-   Submit your work as a single **Jupyter Notebook (.ipynb)** file.
-   Ensure the notebook contains:
    -   Code for all tasks.
    -   Outputs such as charts, metrics, and analysis results.
    -   A brief summary of your methodology and findings.

---

This assessment reflects the dataset's location (`src/data.csv`) and ensures clarity on loading and preprocessing steps.

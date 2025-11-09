# 🎬 Movie Genre Prediction Model

This project builds a machine learning model that predicts a movie’s **genre** based on its **title** and **plot summary**.  
It uses a classic **Natural Language Processing (NLP)** workflow with **TF-IDF** vectorization and a **Logistic Regression** model wrapped in a **One-vs-Rest (OvR)** classifier to handle multiple genres.

---

##  Overview

The goal is to predict one of **27 possible movie genres** — such as *Drama*, *Comedy*, or *Documentary* — using only the movie’s text data.

---

## ⚙️ How It Works

1. **Load the Data**  
   Movie data is read from three text files:
   - `train_data.txt`
   - `test_data.txt`
   - `test_data_solution.txt`

2. **Combine Text Features**  
   The movie *title* and *description* are merged into one field for better context.

3. **Clean the Text**  
   Removes punctuation, converts everything to lowercase, and prepares the text for vectorization.

4. **Vectorize with TF-IDF**  
   Converts text into numerical features that reflect the importance of words across all movies.

5. **Train the Model**  
   A Logistic Regression model (using the OvR strategy) is trained to handle multiple genres.

6. **Evaluate the Results**  
   The model is tested on separate data and produces detailed metrics and accuracy scores.

---


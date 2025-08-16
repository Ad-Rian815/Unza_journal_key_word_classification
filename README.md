# 1. Business Understanding

1.1 Problem Statement
Currently, keywords associated with research articles in UNZA journals are not automatically organized or classified. This makes it difficult for researchers, students, and librarians to quickly identify relevant articles or track research trends. A manual process is time-consuming, inconsistent, and limits the usefulness of the institutional repository. Navigation of journals will be a piece of cake!

1.2 Business Objectives
The goal of this project is to build a system that can automatically classify keywords from articles into meaningful categories (e.g., *Agriculture, Medicine, Computer Science*).  

From a real-world perspective, success means:
- Improving searchability and retrieval of research articles.
- Helping researchers discover related works faster.
- Supporting administrators in analyzing research output trends at UNZA.

1.3 Data Mining Goal
  The technical approach to achieving these objectives is structured into the following data mining goals:
  
  1.Classification Model Development: A classification model will be built to categorize article keywords into predefined classes.
  
  2.Text Preprocessing: The raw text data will be prepared for machine learning using standard preprocessing techniques, including tokenization, stop-word removal, and TF-IDF (Term          Frequency-Inverse Document Frequency) for vectorization.
  
  3.Algorithm Experimentation: The performance of several classification algorithms will be evaluated to determine the most effective one. The algorithms to be tested include Naïve          Bayes, Support Vector Machines (SVM), and Decision Trees.
  
  To wrap things up, the main goal of this project is to build a machine learning model that can automatically classify article keywords. We've broken the work down into two key           parts. First, we'll focus on data preparation by cleaning the text using tokenization and stop-word removal, and then we'll use TF-IDF to turn everything into numbers for the models     to work with.
  
  For the second part, we'll experiment with different algorithms like Naïve Bayes, SVM, and Decision Trees. By testing them with metrics like precision and F1-score, then we'll           figure out which one is the most accurate. We're hoping that by following these steps, we can successfully create a model that not only classifies keywords effectively but also          shows we've got a solid grasp of the data mining process.

  1.3.1 Data Preparation
       Before bilding the model, we will first make sure the data is clean (through tokenization) and then turining the words into numbers through Term Frequency-Inverse Document               Frequency (TF-IDF).



1.4 Project Success Criteria
- The model should achieve at least **80% accuracy** on the test dataset.
- The classification results must be **interpretable and consistent** across different domains.
- The system should reduce the time required to organize keywords compared to manual methods.

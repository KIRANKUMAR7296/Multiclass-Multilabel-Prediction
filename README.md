# Multiclass Multilabel Prediction for Stack Overflow Questions 🔎📝

End to End **Multiclass Multilabel Prediction** for **Stack Overflow Questions**.

### 1. Problem

Given Text for the Questions, Predict **Tags** Associated with them.

### 2. Data
**[Kaggle's Stack Overflow Sample](https://www.kaggle.com/stackoverflow/stacksample)** : 10% of Stack Overflow Questions and Answers.

### 3. Features
**Questions :** 
- Title
- Body
- Creation Date
- Closed Date (if applicable)
- Score
- Owner ID 
for all Non Deleted **Stack Overflow Questions** whose ID is A Multiple of 10.

**Answers :** 
- Body
- Creation Date
- Score
- Owner ID 
for each of the Answers to these Questions. 
The ParentID Column Links back to the Questions Table.

**Tags :** 
contains the **Tags** on each of these Questions.

### Tokenize
- Splitting up a larger body of text into smaller tokens ( lines or words ).

### CountVectorizer
- Provides a simple way to both tokenize a collection of text documents and build a vocabulary of known words.

### TfidfVectorizer 
- Transforms text to feature vectors that can be used as input to estimator.

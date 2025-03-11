# Song-Recommendation-System-based-on-Moods

## 📌 Overview
This project builds a **Mood-Based Song Recommendation System** using **Machine Learning**.  
It analyzes **Spotify song features** like **Danceability, Energy, Valence, Tempo, Loudness,** etc.,  
to classify songs into different moods:

- **Happy/Upbeat** 🎉  
- **Sad/Down** 😢  
- **Energetic/Excited** ⚡  
- **Calm/Relaxed** 🌿  
- **Romantic/Love** ❤️  
- **Angry/Intense** 🔥  

## 🚀 Project Workflow
### 1️⃣ Exploratory Data Analysis (EDA)
- **Loaded dataset & inspected features**  
- **Handled missing values** (`genres` column had missing values)  
- **Detected & handled outliers** in numeric columns  
- **Visualized distributions & correlations**  

### 2️⃣ Mood Labelling & Feature Engineering
- **Defined six mood categories** based on song features  
- **Created new features** like:
  - `tempo_category` (Slow, Medium, Fast)  
  - `loudness_category` (Soft, Normal, Loud)  
  - `speechiness_category` (Speech vs Music)  
  - `acoustic_instrumental_ratio`  

### 3️⃣ Machine Learning Model (Upcoming)
- Training a model for **Mood-Based Song Recommendation System**  
- Exploring **classification models (Logistic Regression, SVM, Random Forest, etc.)**  
- Evaluating model performance  

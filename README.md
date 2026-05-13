## AI Skincare Recommendation Engine

Skincare today can feel overwhelming. With thousands of products on the market and ingredient lists that are difficult to understand, finding products that actually suit specific skin concerns becomes confusing and time-consuming.

As someone interested in both skincare and artificial intelligence, I wanted to build a project that combined personal interest with applied machine learning. This project explores how AI and NLP techniques can be used to create smarter, more personalized skincare recommendations based on ingredient analysis rather than marketing claims.

The result is an AI-powered skincare recommendation engine that analyzes product ingredients, identifies similarities between formulations, and generates personalized recommendations for concerns such as acne, dryness, pigmentation, and sensitive skin.

---

##  Project Objectives

* Build a personalized skincare recommendation system
* Analyze skincare products using ingredient-based similarity
* Apply machine learning and NLP techniques to real-world data
* Generate explainable recommendations based on active ingredients
* Visualize skincare product clusters using dimensionality reduction

---

## Features

* Ingredient-based skincare recommendations
* TF-IDF vectorization for ingredient representation
* Cosine similarity for product matching
* Concern-aware recommendation scoring
* Safety filtering for potentially irritating ingredients
* Explainable AI recommendations
* Interactive product similarity visualization using Bokeh
* Product clustering using Truncated SVD and t-SNE

---

##  Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* TF-IDF Vectorization
* Cosine Similarity
* Truncated SVD
* t-SNE
* Bokeh
* Jupyter Notebook

---

## ⚙️ How the Recommendation System Works

The recommendation pipeline follows these steps:

1. Ingredient preprocessing and cleaning
2. TF-IDF vectorization of ingredient lists
3. Cosine similarity computation between products
4. Concern-based scoring using active ingredients
5. Safety penalty filtering for sensitive ingredients
6. Recommendation ranking and explainable outputs
<img width="1536" height="1024" alt="image" src="https://github.com/user-attachments/assets/f3a125d0-40a0-4e62-beb7-1674e0406a74" />
The system recommends products that are not only similar in formulation but also aligned with specific skincare concerns.

Example:

> Recommended because it contains niacinamide and salicylic acid which are commonly associated with acne care.

---

## 📊 Visualization & Product Clustering

To better understand product relationships, dimensionality reduction techniques were applied:

* Truncated SVD for feature reduction
* t-SNE for 2D product clustering visualization

Interactive visualizations were created using Bokeh to explore product similarities and skincare categories.

---

## 📂 Dataset

The dataset contains skincare product information including:

* Product names
* Brands
* Product categories
* Ingredient lists
* Product prices

---

## 🔮 Future Improvements

* Streamlit web application
* Personalized skincare routine generation
* User skin profile system
* Budget-aware recommendations
* Ingredient conflict detection
* Deep learning-based recommendation models

---

## ▶️ Installation

Clone the repository:

```bash
git clone https://github.com/your-username/AI-Skincare-Recommendation-Engine.git
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Run the Jupyter Notebook to explore the recommendation system.

---

## 👩‍💻 Author

Nandini Yadav


# Udemy Course Recommendation System

This project builds a machine learning-based recommendation engine that suggests Udemy courses to users using **Natural Language Processing (NLP)** and **popularity metrics**. It demonstrates two powerful recommendation methods suitable for educational platforms.

---

### Objective  
To help learners discover relevant and trending courses on Udemy by analyzing course data from Kaggle’s Udemy Dataset and applying text-based and quantitative recommendation techniques.

---

### Dataset  
The dataset includes course information such as:  
- Course Title  
- URL  
- Subject  
- Level (Beginner, Intermediate, Expert)  
- Price  
- Number of Subscribers  
- Number of Reviews  
- Duration (in hours)  

Source: Kaggle Udemy Courses Dataset.

---

### Technologies Used  
- Python  
- Pandas, NumPy  
- Scikit-learn  
- NeatText (for NLP preprocessing)  
- Matplotlib, Seaborn (for visualization)

---

### Methodology  

1. **Data Cleaning & Preprocessing**  
   Removed missing and duplicate records, parsed course details, and standardized features.

2. **Exploratory Data Analysis (EDA)**  
   Visualized course price distribution, subjects, and paid vs. free course ratios.

3. **Recommendation Techniques**

   **Popularity-Based Recommendation**  
   Calculates a score combining course subscriber and review counts.  
Popularity Score = 0.6 * Subscribers + 0.4 * Reviews

Example recommended popular courses:  
- The Web Developer Bootcamp  
- Complete Web Developer Course 2.0  
- Coding for Entrepreneurs Basics  

**Content-Based Recommendation**  
Uses text similarity (TF-IDF or CountVectorizer + cosine similarity) on course titles and subjects to suggest similar courses.  
Input: “Learn HTML”
Output:

WordPress Development for Beginners

Website Coding - Web Design Skills

Kids Coding – Basics of CSS


---

### Results  
- Returns both **personalized** and **trending** Udemy course recommendations.  
- Demonstrates accurate keyword-based NLP matching.  
- Provides valuable insights into Udemy’s course landscape.

---

### Future Enhancements  
- Integrate with Streamlit or Flask for a web interface.  
- Add collaborative filtering for user-based recommendations.  
- Include real-time updates with user ratings and reviews.

---

### How to Run  
1. Download the notebook and dataset.  
2. Install dependencies:
pip install -r requirements.txt

3. Run the notebook in Jupyter or Google Colab:
jupyter notebook Course_recommendation.ipynb









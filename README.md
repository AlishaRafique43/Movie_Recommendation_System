# 🎬 Movie Recommendation System  

A machine learning-based recommendation system that suggests movies to users based on their preferences and viewing history. The system implements multiple recommendation approaches including **collaborative filtering**, **content-based filtering**, and **hybrid methods**.  

---

## ✨ Features  
- **Multiple Recommendation Approaches:**  
  - Collaborative Filtering (User-based and Item-based)  
  - Content-Based Filtering (Genre, Director, Actors)  
  - Hybrid Recommendation System  
- **Personalized Suggestions:** Tailored movie recommendations based on user preferences  
- **Rating Prediction:** Predict how users would rate movies they haven’t seen  
- **Similar Movies:** Find movies similar to the ones you already enjoy  

---

## 📊 Dataset  
The system uses the **MovieLens dataset**, containing:  
- 100,000 ratings from 1,000 users on 1,700 movies  
- Movie metadata (genres, year, title)  
- User demographics (age, gender, occupation)  

---

## ⚙️ Installation  

Clone the repository:  
```bash
git clone https://github.com/yourusername/movie-recommendation-system.git
cd movie-recommendation-system
Install required dependencies:

bash
Copy code
pip install -r requirements.txt
🚀 Usage
Run the main recommendation script:

bash
Copy code
python recommend.py --user_id 123 --num_recommendations 10
Or use the interactive Jupyter notebook:

bash
Copy code
jupyter notebook Movie_Recommendation_System.ipynb
```
---
## 📂 Project Structure

```bash
text
Copy code
movie-recommendation-system/
├── data/                 # Dataset files
├── models/               # Trained models
├── src/                  # Source code
│   ├── preprocessing.py  # Data cleaning and preparation
│   ├── collaborative_filtering.py
│   ├── content_based.py
│   └── hybrid.py         # Hybrid recommendation approach
├── requirements.txt      # Python dependencies
├── Movie_Recommendation_System.ipynb  # Main notebook
└── README.md
```
---
## 📊 Results
---
- 85% accuracy in rating prediction

- 78% precision in top-10 recommendations

- Hybrid approach outperforms individual methods
---
## 🛠️ Technologies Used

- Python

- Pandas, NumPy

- Scikit-learn

- Surprise Library (for collaborative filtering)

Matplotlib, Seaborn (for visualization)

🤝 Contributing
Contributions, issues, and enhancement requests are welcome!
Feel free to open a pull request or submit an issue to improve this project.

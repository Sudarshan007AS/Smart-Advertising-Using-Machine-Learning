# Smart-Advertising-Using-Machine-Learning
The Smart Advertising System is an innovative machine learning-based web application designed to enhance the effectiveness of digital marketing campaigns by delivering personalized ad recommendations in real-time. The system analyzes user behavior, ad content, and historical interaction data to predict the likelihood of engagement, improving ad targeting accuracy and maximizing click-through rates (CTR) and marketing ROI.

A personalized digital advertising platform that recommends relevant ads based on user demographics and behavior using machine learning.

## Technologies Used

- **Frontend**: HTML, CSS  
- **Backend**: Python, Flask  
- **Machine Learning**: Scikit-learn, Pandas, NumPy, TF-IDF  
- **Database**: SQLite  
- **Visualization (optional)**: Matplotlib, Seaborn  

## Key Features

- User registration and login system  
- Dynamic ad display with real-time click tracking  
- Click prediction using ML models (e.g., Logistic Regression)  
- TF-IDF based content filtering for ad similarity  
- Feedback integration for continuous model improvement  
- Admin panel and ad management  
- Dashboard to view click-through rates and performance metrics  

## Machine Learning Workflow

1. **Data Preprocessing**: Clean and structure ad metadata, user demographics, and click logs  
2. **Feature Engineering**: Encode categorical data and extract TF-IDF features  
3. **Model Training**: Train classification models on labeled interaction data  
4. **Recommendation Engine**: Combine TF-IDF similarity and click probability  
5. **Evaluation**: Accuracy, precision, recall, and AUC score  

## Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/Sudarshan007AS/Smart-Advertising-Using-Machine-Learning.git
cd Smart-Advertising-Using-Machine-Learning
```

### 2. Install dependencies

```bash
pip install flask pandas numpy scikit-learn
```

### 3. Run the application

```bash
python app.py
```

Visit `http://localhost:5000` in your browser.

## Project Structure

- `app.py`: Main Flask backend  
- `ads_model.pkl`: Trained ML model for click prediction  
- `templates/`: HTML pages  
- `static/`: CSS and JS files  
- `utils.py`: TF-IDF and recommendation logic  
- `data/`: Contains sample data or SQLite DB  

## Sample Use Case

A 25-year-old user interested in sports visits the site:  

- Their demographic and interest data is stored  
- The system recommends sports-related ads based on click patterns  
- Click probability is calculated using the trained model  
- Ads are ranked by TF-IDF and click prediction  

## Future Improvements

- Deep learning-based recommendation system  
- Collaborative filtering integration  
- Real-time bidding simulation  
- Admin analytics dashboard  
- A/B testing module

## 👤 Author

**Sudarshan A S**  <br>
[LinkedIn](https://www.linkedin.com/in/sudarshanas) • [GitHub](https://github.com/Sudarshan007AS)  
---


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

## 👤 Author

**Sudarshan A S**  <br>
[LinkedIn](https://www.linkedin.com/in/sudarshanas) • [GitHub](https://github.com/Sudarshan007AS)  
---



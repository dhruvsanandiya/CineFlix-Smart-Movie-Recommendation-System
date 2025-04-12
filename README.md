# 🎬 CineFlix | Smart Movie Recommendations

This is a simple web-based movie recommendation system built using **Flask**, **pandas**, and **scikit-learn**. The app takes a movie title as input and returns a list of similar movies based on content-based filtering.

## 🚀 Features

- 🔍 Content-based movie recommendation
- 📊 Uses TMDB dataset (CSV)
- 🌐 Built with Flask
- 🎨 Responsive UI with HTML templates
- ⚙️ Ready for deployment (includes `Procfile` and `.env` support)

---

## 📁 Project Structure

```bash
CineFlix-Smart-Movie-Recommendation-System/
│
├── __pycache__/                 # Python cache files
├── .venv/                       # Virtual environment
│
├── model/                       # Model-related files
│   └── tmdb.csv
│
├── static/                      # Static assets
│   ├── builtin/
│   │   └── background.jpg
│   └── favicon/
│       ├── android-chrome-192x192.png
│       ├── android-chrome-512x512.png
│       ├── apple-touch-icon.png
│       ├── favicon-16x16.png
│       ├── favicon-32x32.png
│       ├── favicon.ico
│       └── site.webmanifest
│   └── uproots/                     # (Custom folder - usage undefined)
│
├── templates/                   # HTML templates
│   ├── found.html
│   ├── index.html
│   ├── notFound.html
│
├── .env                         # Environment variables
├── app.py                       # Main Flask application
├── image.jpg                    # Main image (root level)
├── Procfile                     # For deployment (e.g., Heroku)
├── README.md                    # Project documentation
├── requirements.txt             # Python dependencies
```

---

## 🔧 Installation

1. **Clone the repo:**

   ```bash
   git clone https://github.com/dhruvsanandiya/cineflix-smarrt-movie-recommendation.git
   cd cineflix-smarrt-movie-recommendation
   ```

2. **Create and activate a virtual environment:**

   ```bash
   python -m venv .venv
   source .venv/bin/activate  # On Windows: .venv\Scripts\activate
   ```

3. **Install dependencies:**

   ```bash
   pip install -r requirements.txt
   ```

4. **Run the application:**
   ```bash
   flask run
   ```

---

## 🧠 How It Works

- Loads movie metadata from tmdb.csv
- Vectorizes movie overview/descriptions
- Computes cosine similarity
- Returns the top N most similar movies based on input

---

## 🛠️ Tech Stack

- Python 3.10+
- Flask
- Pandas
- Scikit-learn
- HTML/CSS (Jinja2 templating)
- Gunicorn (for production)

---

## 🌐 Deployment

**To deploy on Heroku:**
- Login to Heroku and create an app
- Push code to Heroku Git or link to GitHub
- Ensure Procfile, requirements.txt, and .env are properly configured
- Deploy!

---

## 📝 Environment Variables

**Create a .env file in the root directory and add any necessary environment variables (e.g., API keys if needed). Example:**
   ```bash
   FLASK_APP=app.py
   FLASK_ENV=development
   ```

---

## 🖼️ Screenshots

**Home Page**

   ![Screenshot 2025-04-12 062713](https://github.com/user-attachments/assets/976cb99c-44ec-4138-ac96-145c72857a97)

**Recommendations**

   ![Screenshot 2025-04-12 062753](https://github.com/user-attachments/assets/b77ed660-fac8-41d7-acae-b230326729bf)

---

## 📌 TODO
 - Add support for TMDB API
 - Improve UI styling
 - Add genres-based filtering
 - Dockerize the project

---

## 🤝 Contributing
   Pull requests are welcome! For major changes, please open an issue first to discuss what you’d like to change.

---

## 📄 License
   This project is licensed under the MIT License.

---

## 🙌 Acknowledgements
   - The Movie Database (TMDB)
   - Scikit-learn documentation
   - Flask official docs

---

## 🙌 Developed By
   **Dhruv Sanandiya**
   - https://github.com/dhruvsanandiya/CineFlix-Smart-Movie-Recommendation-System


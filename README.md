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

CineFlix/ │ ├── model/ │ ├── image.jpg │ └── tmdb.csv │ ├── static/ │ ├── builtin/ │ │ └── image.jpg │ └── favicon/ │ ├── android-chrome-\*.png │ ├── apple-touch-icon.png │ ├── favicon.ico │ └── site.webmanifest │ ├── templates/ │ ├── found.html │ ├── notFound.html │ ├── index.html │ └── image.jpg │ ├── uproots/ │ ├── pycache/ ├── .venv/ ├── .env ├── app.py ├── image.jpg ├── Procfile ├── requirements.txt └── README.md

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

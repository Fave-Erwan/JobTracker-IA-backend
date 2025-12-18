# 🐍 Job Matcher - Backend API

API REST en Python pour l'analyse intelligente de CV et le scrapping d'offres d'emploi.

## 🚀 Installation
```bash
# Créer l'environnement virtuel
python -m venv venv

# Activer (Mac/Linux)
source venv/bin/activate

# Activer (Windows)
venv\Scripts\activate

# Installer les dépendances
pip install -r requirements.txt

# Lancer le serveur
uvicorn app.main:app --reload --port 8000
```

## 📡 Documentation

Une fois lancé : http://localhost:8000/docs

## 🛠️ Stack

- FastAPI
- Python 3.10+
- pdfplumber
- spaCy
- BeautifulSoup4
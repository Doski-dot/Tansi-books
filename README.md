# 📚 Tansi Book Search Engine

This is a mobile-friendly Flask web app that lets you search through the Tansi Seminary Library book catalog by title, author, or subject.

## 🔍 Features
- Live search with autocomplete
- Responsive layout for mobile and desktop
- Fast book lookup from a JSON database

## 🚀 Deployment (Render.com)
To deploy this site on [https://render.com](https://render.com):

1. Push this code to your GitHub repo
2. Go to [https://render.com](https://render.com)
3. Click **New Web Service**
4. Connect your GitHub and select this repo
5. Use the following settings:

```
Build Command:   (leave empty)
Start Command:   python app.py
Environment:     Python 3
```

The app will be deployed and accessible at your Render URL (e.g. `https://tansi-books.onrender.com`).

## 📁 Files

- `app.py` – Flask server
- `books_data.json` – Book catalog
- `requirements.txt` – Python dependencies
- `render.yaml` – Render.com deploy config

## 🙌 Credits
Created for Tansi Seminary to simplify access to its book catalog.

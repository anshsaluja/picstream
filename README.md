# PicStream

PicStream is a face recognition photo manager that helps users organize, tag, and retrieve images effortlessly. Built with Flask, OpenCV, and SQLite, it combines computer vision with intuitive search and auto-generated captions to make photo collections smarter.

**Live Demo → Coming soon 🚀**

---

## ✨ Features
📸 **Face Recognition:** Detect and tag individuals in images using the `face_recognition` library  
🔎 **Similarity Search:** Retrieve and cluster photos based on facial features  
📝 **Auto-Captions:** Generate text descriptions for uploaded images to enrich metadata  
📂 **Photo Management:** Upload, sort, and organize large photo collections with a clean interface  
💾 **SQLite Database:** Lightweight backend for storing face encodings and metadata  
🌐 **Web Interface:** Simple HTML/CSS frontend served with Flask  

---

## 🧱 Tech Stack
- **Backend:** Flask (Python)  
- **Computer Vision:** OpenCV, face_recognition  
- **Database:** SQLite  
- **Frontend:** HTML, CSS (basic responsive UI)  

---

## 📂 Project Structure
```
/
├── app.py               # Flask entry point  
├── face.py              # Face recognition & clustering logic  
├── image_metadata.py    # Metadata extraction & captioning  
├── templates/           # HTML templates (index, search, add_people)  
├── static/              # CSS, JS, and assets  
└── README.md            # Project overview  
```

---

## ⚙️ Getting Started

### 1. Clone the repo
```bash
git clone https://github.com/anshsaluja/picstream.git
cd picstream
```

### 2. Create a virtual environment & install dependencies
```bash
python3 -m venv venv
source venv/bin/activate
pip install -r requirements.txt  # Flask, OpenCV, face_recognition, numpy
```

### 3. Run the app
```bash
python app.py
```

App will be available at `http://127.0.0.1:5000/`

---

## 📸 Demo & Screenshots
Coming soon — GIFs and screenshots of the app in action will be added here.

---

## 🛠️ Environment Variables
Currently minimal setup — SQLite DB is used locally. Future versions will include `.env` configuration for cloud storage and model options.

---

## 📦 Deployment
- Local Flask server for now  
- Future: containerized with **Docker** and deployed on **Render/Heroku/Vercel**  

---

## 📄 License
This project is licensed under the [MIT License](LICENSE).

---

## 👤 Author
Built with ❤️ by **Ansh Saluja**  
*(Prototype project — actively refining & expanding features)*  

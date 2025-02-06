# **AI-Powered Food Ordering Chatbot** 🍔🤖  

This project is an AI-driven food ordering chatbot built using **FastAPI** and **Dialogflow**, with a frontend for users to browse and place orders. The application is containerized using **Docker** and deployed on **Render** for easy access.  

🔗 **Live Demo**: [Click Here](https://your-app-name.onrender.com) 🚀  

---

## **📂 Files in the Repository**  

### **Backend** (`backend/`)  
- `main.py` → Entry point for the API  
- `db_helper.py` → Database functions (excluded from GitHub for security)  
- `generic_helper.py` → Utility functions  

### **Frontend** (`frontend/`)  
- `home.html` → Main frontend page  
- `styles.css` → Styling for the web page  
- `menu1.jpg`, `menu2.jpg`, `menu3.jpg` → Menu images  

### **Other Files**  
- `dialogflow_assets/` → Training phrases for chatbot responses  
- `Dockerfile` → Used to containerize the application  
- `requirements.txt` → Python dependencies for the project  
- `ngrok.exe` → Used for local tunneling (for Dialogflow testing)  
- `README.md` → Project documentation  

---

## **✨ Features**  

✔️ **AI-powered Chatbot** → Uses Dialogflow for natural language processing  
✔️ **FastAPI Backend** → Lightweight and efficient API for handling food orders  
✔️ **Interactive Web Interface** → Users can browse the menu and place orders  
✔️ **Database Integration** → Stores user orders and menu details (SQLite/MySQL)  
✔️ **Containerized with Docker** → Runs consistently across different environments  
✔️ **Deployed on Render** → Live and accessible online  

---

## **🛠️ Technologies Used**  

- **Backend**: FastAPI, Python  
- **Chatbot**: Dialogflow (Natural Language Understanding)  
- **Database**: SQLite/MySQL  
- **Frontend**: HTML, CSS  
- **Deployment**: Docker, Render  

---

## **🚀 Deployment Guide**  

### **1️⃣ Dockerize the Project**  

```sh
docker build -t food-ordering-bot .
docker run -p 5500:5500 food-ordering-bot

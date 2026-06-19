
# 📝 Flask To-Do App (Dockerized)

A simple **To-Do List Web Application** built using **Flask** and containerized using **Docker**.

---

## 🚀 Features

* Add new tasks
* Mark tasks as completed
* Simple modern UI
* Runs inside Docker container
* Accessible via browser

---

## 🛠️ Tech Stack

* Python 3
* Flask
* HTML + CSS
* Docker

---

## 📁 Project Structure

```
todo-app/
│
├── app.py
├── requirements.txt
├── Dockerfile
└── README.md
```

---

## ⚙️ Setup Instructions

### 1. Clone or open project

```bash
cd todo-app
```

---

### 2. Build Docker Image

```bash
docker build -t todo-app .
```

---

### 3. Run Docker Container

```bash
docker run -d -p 7000:5000 --name my-todo todo-app
```

---

## 🌐 Open Application

Open your browser:

```
http://localhost:7000
```

---

## 📌 Docker Commands

### Check running containers

```bash
docker ps
```

### Stop container

```bash
docker stop my-todo
```

### Remove container

```bash
docker rm my-todo
```

### Remove image

```bash
docker rmi todo-app
```

---

## 🧠 How It Works

* Flask runs a web server on port **5000**
* Docker maps it to **7000**
* Tasks are stored in memory (temporary)
* UI updates dynamically when tasks are added or completed

---

## ⚠️ Limitation

* Data is not persistent
* Tasks will reset when container stops

---

## 🚀 Future Improvements

* Add database support (SQLite / PostgreSQL)
* User login system
* Persistent storage
* REST API version
* React frontend

---

## 👨‍💻 Author

Built while learning **Docker + Flask basics**

---



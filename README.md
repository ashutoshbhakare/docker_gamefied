# 🐧 Interactive Linux & Docker Task Game  

**Developed by:** *Unnati Development & Training Center*  
**Platform:** Firebase Studio  
**Category:** Educational / Gamified Learning  

---

## 🎯 Overview  

The **Interactive Linux & Docker Task Game** is a web-based learning platform designed for students who want to sharpen their **Linux** and **Docker** skills through fun, hands-on challenges.  

Built on **Firebase Studio**, this application transforms the learning experience into an interactive journey where users complete real-world system administration and containerization tasks — all inside a gamified interface.  

The application runs inside a **Docker container**, making it portable, fast, and super easy to deploy anywhere.  

---

## 🚀 Quick Start  

### **Step 1: Pull the Docker Image**

The public image is available on **Docker Hub**.  
You can pull it directly using:

```bash
docker pull abhaydandgedocker/dcom10
```

---

### **Step 2: Run the Application**

Launch the container with the following command:

```bash
docker run -p 9002:9002 -e NEXT_PUBLIC_BRAND_URL="https://your-url.com" -e ADMIN_USERNAME="new_admin" -e ADMIN_PASSWORD="new_password" -e GEMINI_API_KEY="A"   abhaydandgedocker/dcom10
```

🧠 **Explanation of Environment Variables:**

| Variable | Description |
|-----------|--------------|
| `NEXT_PUBLIC_BRAND_URL` | Your application’s base URL |
| `ADMIN_USERNAME` | Username for the admin dashboard |
| `ADMIN_PASSWORD` | Password for admin access |
| `GEMINI_API_KEY` | API key used for AI-powered interactions within the app |

---

### **Step 3: Access the Application**

Once the container is running, open your browser and visit:

👉 [http://localhost:9002](http://localhost:9002)

You’ll now have access to the **Interactive Linux & Docker Game Interface**!

---

## 🧩 Features  

- 🐧 **Linux Challenges:** Solve beginner-to-advanced level Linux tasks interactively.  
- 🐳 **Docker Task Arena:** Learn Docker commands by completing real-time container-based puzzles.  
- 🎮 **Gamified Interface:** Earn points and track progress as you master each challenge.  
- 🔐 **Admin Dashboard:** Manage users, monitor tasks, and track performance.  
- ☁️ **Firebase Integrated:** Secure authentication and real-time updates powered by Firebase.  

---

## 🛠️ Requirements  

- **Docker** (v20+ recommended)  
- **Internet Connection** (for pulling image and For the API Call)  
- **Valid GEMINI API Key** (for AI-based task hints and chat)  

---

## 🧑‍💻 Developed & Maintained By  

**Unnati Development & Training Center**  
Empowering students to learn DevOps, Cloud, and Open Source technologies through hands-on education.  

---

## 📢 Connect & Contribute  

If you’re a student or trainer and would like to contribute new Linux or Docker challenges, feel free to fork the repository or contact the Unnati Dev Team.  

**Feedback and feature requests are always welcome!**  

---

### 🐋 Example Command Recap

```bash
docker run -p 9002:9002 -e NEXT_PUBLIC_BRAND_URL="https://your-url.com" -e ADMIN_USERNAME="new_admin" -e ADMIN_PASSWORD="new_password" -e GEMINI_API_KEY="A"   abhaydandgedocker/dcom10
```

Access it at: **http://localhost:9002**
Access admin panal at: **http://localhost:9002/admin**




---

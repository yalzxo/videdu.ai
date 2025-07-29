
# 🐍 VidEdu - AI-Powered Python Learning Platform 🚀  

🚀 Hackathon Project by:

👤 Guru Divya Darshini U
👤 Srinithi A
👤 Yalini Madan
👤 Navanthiga J M


## 🌟 Overview  
VidEdu is an **AI-driven Python learning platform** that automatically generates **educational videos**, **adaptive quizzes**, and **learning insights**. It creates **tutorials with animations, scripts, and voice narration** to make Python learning interactive and effective.

---

## ✨ Features  

✅ **AI-Generated Python Tutorial Videos** 🎥  
✅ **Adaptive Quizzes with Performance Analysis** 📝  
✅ **Manim-Powered Animations** 🎨  
✅ **Text-to-Speech Narration (gTTS)** 🗣  
✅ **Personalized Learning Paths & Progress Tracking** 📊  
✅ **Peer Collaboration (Study Groups & Live Sessions)** 🤝  
✅ **Interactive AI Chatbot for Assistance** 💬  

---

## 🚀 Live Demo  

🔗 **Access the Web App**: [ngrok URL - To be provided]  

📌 **Note:** The ngrok URL may change upon restart. If you face any issues, contact the team for an updated link.

---

## 🏃‍♂️ Running the Application Locally  

To run the project on your local machine, follow these steps:

### **1️⃣ Prerequisites**  
- **Python 3.8 or higher**  
- **FFmpeg** (for video/audio processing)  

### **2️⃣ Clone the Repository**  
```bash
git clone https://github.com/navanthiga/gdg_final.git
cd backend
cd content_generator
```

### **3️⃣ Set Up Environment**  
Create a `.env` file in the project root and add your **Gemini API key**:  
```
GEMINI_API_KEY=your_api_key_here
```

### **4️⃣ Install Required Dependencies**  
Download the `requirements.txt` file and install dependencies:  
```bash
pip install -r requirements.txt
```



### **5️⃣ Run the Application**  
```bash
streamlit run main2.py
```
This will launch the web app at **http://localhost:8501**.

---

## 🌍 Deploying via ngrok  

If you want to **deploy the app using ngrok**, follow these steps:

### **1️⃣ Install ngrok**  
Download ngrok from [ngrok.com](https://ngrok.com/download) and set it up.

### **2️⃣ Run the Web App Locally**  
```bash
streamlit run main2.py
```

### **3️⃣ Start ngrok**  
Open a new terminal and run:  
```bash
ngrok http 8501
```
This will generate a **public URL** like:  
```
https://random-string.ngrok.io
```
Share this link with **evaluators** to access the app.

📌 **Note:** The ngrok URL expires after some time. Restart ngrok if needed.

---



## 🛠 How It Works  

1️⃣ **User selects a Python topic.**  
2️⃣ **Gemini API generates a tutorial script.**  
3️⃣ **Manim creates animations.**  
4️⃣ **gTTS generates voice narration.**  
5️⃣ **MoviePy merges video & audio.**  
6️⃣ **Streamlit serves the final output.**  
7️⃣ **Users take adaptive quizzes & track progress.**  

📌 **Component Breakdown:**

| Component        | Function |
|-----------------|----------|
| **Gemini API**  | Generates Python tutorial script |
| **Manim**       | Creates animations |
| **gTTS**        | Converts text to speech |
| **MoviePy**     | Merges video & audio |
| **Streamlit**   | Runs the web interface |

---



## ❓ FAQ  

**Q: The app isn’t running! What should I do?**  
A: Make sure you installed `requirements.txt`, have `FFmpeg`, and set up the `.env` file correctly.  

**Q: ngrok link expired. How can I get a new one?**  
A: Restart ngrok by running `ngrok http 8501` again.  

**Q: How do I get my Gemini API key?**  
A: Sign up on Google AI’s Gemini API portal and generate a key.

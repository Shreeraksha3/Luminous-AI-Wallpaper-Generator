<p align="center">
  <img src="assets/banner.png" alt="Luminous - AI Wallpaper Generator" width="100%" />
</p>

# 🎇 Luminous – AI Wallpaper Generator  

**Luminous** is a web app that lets you create **unique wallpapers** with the help of **AI**.  
Just pick your favorite **colors 🎨, styles 🖌, and moods 🌈**, add a short description, and watch your wallpaper come to life!  

![Python](https://img.shields.io/badge/Python-3.9%2B-blue?logo=python)  
![Framework](https://img.shields.io/badge/FastAPI-Backend-green?logo=fastapi)  
![License](https://img.shields.io/badge/License-MIT-yellow)  
![Status](https://img.shields.io/badge/Status-Prototype-orange)  

---

## ✨ Features  

- 🎨 **Color Picker:** Choose from **VIBGYOR** colors (Violet, Indigo, Blue, Green, Yellow, Orange, Red).  
- 🖼 **Styles & Moods:** Select from different **design styles** (abstract, nature, etc.) and **moods** (calm, energetic, etc.).  
- ✍️ **Custom Description:** Add a few words to guide the wallpaper design.  
- 👀 **Preview Before Download:** See how your wallpaper looks before saving it.  
- 📱 **Responsive UI:** Works smoothly on **desktop & mobile**.  
- 🤖 **AI-Powered (Pluggable):** Backend ready for integration with real AI models. *(Currently uses placeholders.)*  

---

## 🚀 Installation  

1. **Clone the repository:**  
   ```sh
   git clone https://github.com/yourusername/luminous.git
   cd luminous
2. **(Optional) Create a virtual environment:**
   ```sh
   python -m venv venv
   venv\Scripts\activate   # On Windows
   # source venv/bin/activate   # On macOS/Linux
3. **Install dependencies:**
   ```sh
   pip install -r requirements.txt

---

## ▶️ Usage

1. **Run the server:**
   ```sh
   python app/main.py
2. **Open in browser:**
   ```sh
   http://localhost:8000
3. **Generate Wallpapers:**
   - Pick your color 🌈, style 🖌, and mood 💫.
   - Add a short description ✍️.
   - Get a preview 👀 and download your custom wallpaper.
   
---

## 📂 Project Structure
1. Project Structure
 
   ```sh
      Wallpaper/
   ├── app/
   │   ├── main.py          # Main application
   │   ├── static/          # Static files (CSS, JS, images)
   │   └── templates/       # HTML templates
   ├── requirements.txt     # Dependencies
   └── README.md            # Documentation

   
---
## ⚡ AI Integration

  - The backend is structured to support AI-based image generation.
  - Replace the placeholder image logic in app/main.py with your own AI model (e.g., Stable Diffusion, DALL·E, etc.).
---

## 🌟 About Luminous
- Luminous makes wallpaper creation effortless 💡.
- Instead of searching the internet, you can design your own wallpaper in seconds — guided by colors, mood, and creativity ✨.

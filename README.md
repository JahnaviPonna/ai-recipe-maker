# 🍽️ AI Recipe Generator  

The **AI Recipe Generator** is a web-based application that generates delicious recipes based on user input using **Google Gemini AI**. Users can enter a dish name, ingredients, and dietary preferences, and the AI will generate a well-structured recipe with cooking instructions and tips.  

---

## 🚀 Features  
- 🍲 Generate AI-based recipes by entering dish names and ingredients.  
- 🌱 Choose dietary preferences: Vegetarian, Vegan, or Gluten-Free.  
- ⏳ Provides **prep time, cook time, and serving size**.  
- ✅ Well-structured **ingredients list and step-by-step instructions**.  
- 🔄 **Real-time API call to Gemini AI** for fresh recipe generation.  
- 🎨 User-friendly UI with a **modern and responsive design**.  

---

## 📂 Project Structure  

📂 ai-recipe-maker
│── 📄 app.py              # Backend (Flask API)
│── 📄 index.html          # Frontend UI
│── 📄 script.js           # JavaScript (Fetch API)
│── 📄 styles.css          # Styling (CSS)
│── 📄 README.md           # Project Documentation
│── 📄 requirements.txt    # Python dependencies

---

## ⚙️ Installation & Setup  

### 1️⃣ Clone the Repository  
```bash
git clone https://github.com/JahnaviPonna/recipe-maker-ai.git
cd AI-Recipe-Generator
```

2️⃣ Install Dependencies
Make sure you have Python installed. Then, install the required libraries:
```bash
pip install flask google-generativeai flask-cors
```

3️⃣ Set Up Google Gemini AI API
Get an API key from Google AI Studio.
Open app.py and replace the API key:
```python
genai.configure(api_key="YOUR_GEMINI_API_KEY")
```

4️⃣ Run the Flask Backend
```bash
python app.py
```
The backend will start at http://127.0.0.1:5000

5️⃣ Open the Frontend
Open index.html in your browser.
Enter a dish name, ingredients, and choose a diet preference.
Click "Generate Recipe" to see the AI-generated recipe.


🛠️ Technologies Used
Frontend: HTML, CSS, JavaScript
Backend: Python (Flask)
AI Model: Google Gemini AI
API Handling: Flask & Fetch API


Hosting: Localhost📸 Screenshots (Optional)
(Add images of your project in action!)


📌 Future Enhancements
✅ Add voice input for recipe requests.
✅ Improve UI with animations & themes.
✅ Save favorite recipes for later.

🤝 Contributing
Feel free to fork the repository and submit pull requests! 🚀

📜 License
This project is open-source and free to use.

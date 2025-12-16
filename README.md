# 🏃‍♂️ Math Sprint Game

**Math Sprint Game** is a fast-paced web-based math game built with **HTML, CSS, and JavaScript**. Players solve as many multiplication questions as possible in the shortest time. Correct answers help you advance, while wrong guesses add a time penalty. The game tracks your best scores and provides multiple difficulty levels.  

---

## 🎮 Overview
Math Sprint Game allows players to:  
- Choose the number of questions per round (10, 25, 50, 99)  
- Solve multiplication equations under time pressure  
- Track best scores with localStorage persistence  
- Play repeatedly to improve speed and accuracy  
- Experience a visually responsive design for desktop and mobile  

---

## 🚀 Features
- ✅ **Multiple Question Amounts**: 10, 25, 50, or 99 questions per round  
- ⏱ **Time Tracking**: Measures base time and applies penalties for wrong answers  
- 📊 **Best Score System**: Stores top scores for each question amount in localStorage  
- 🖱 **Simple Controls**: Use "Right" and "Wrong" buttons to answer  
- 🎨 **Responsive Design**: Works on desktops, laptops, and mobile devices  
- 🧩 **Dynamic Equations**: Randomly generated correct and incorrect multiplication equations  
- ⏳ **Countdown Timer**: 3-2-1-GO start sequence for each round  

---

## 📂 Project Structure
```markdown
index.html       # Main HTML file
style.css        # CSS styling and responsive design
script.js        # Main game logic (timer, equations, scoring)
shuffle.js       # Utility to shuffle equations array
favicon.png      # Game icon
## ⚙️ Requirements
- Modern web browser (Chrome, Firefox, Edge, Safari)  
- No server required, runs locally  

---

## 🛠 Installation / Play Locally
1. Clone or download the repository  
2. Open `index.html` in a web browser  
3. Choose a question amount on the splash page  
4. Click **Start Round** to begin  
5. Use the **Right** and **Wrong** buttons to answer each equation  
6. View your time, penalties, and final score at the end  

---

## ⏱ Gameplay Mechanics
- **Countdown**: 3-2-1-GO before the round starts  
- **Equations**: Randomly generated multiplication equations, some correct and some incorrect  
- **Player Selection**: Clicking "Right" or "Wrong" scrolls to the next question  
- **Scoring**:  
  - Base time is measured from start to finish  
  - Incorrect guesses add a 0.5s penalty each  
  - Final time = Base time + Penalty time  
- **Best Score Tracking**: Stored per question amount using localStorage  

---

## 🎨 UI / Pages
- **Splash Page**: Select number of questions and view best scores  
- **Countdown Page**: Displays 3-2-1-GO  
- **Game Page**: Scrollable question list with answer buttons  
- **Score Page**: Displays base time, penalties, final time, and Play Again button  

---

## 📋 Controls
- **Right Button** → Marks equation as correct  
- **Wrong Button** → Marks equation as incorrect  
- **Start Round Button** → Begins a new round  
- **Play Again Button** → Resets game and returns to splash page  

---

## 📱 Responsive Design
- **Desktop / Laptop**: Fixed game container  
- **Mobile**: Full-width layout, adjusted spacing and font sizes  
- **iPhone**: Optimized button and score display  

---

## 💾 Local Storage
- Best scores are saved using the browser’s localStorage  
- Each question amount (10, 25, 50, 99) has its own saved best score  

---

## 🔧 Scripts Overview
- `script.js`: Core game logic (timer, equation generation, player selection, score calculation)  
- `shuffle.js`: Utility function to shuffle equation arrays randomly  
- `style.css`: Styling for all pages, buttons, countdown, and responsive layouts  
- `index.html`: Page structure including splash, countdown, game, and score pages  

---

## ⚡ How to Extend
- Add division or addition/subtraction questions  
- Add sound effects for correct/incorrect answers  
- Implement difficulty levels or timed challenges  
- Add animations or visual feedback for penalties  

---

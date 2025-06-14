# 🌍 Emoji Riddle Quiz – Guess the Country

Welcome to the **Emoji Riddle Quiz**, a fun and interactive single-page JavaScript game 
that challenges players to guess countries based on creative emoji-style riddles. 
This project blends logic, emoji pattern recognition, 
and a user-friendly design to deliver an engaging experience.

## 📖 Table of Contents  
- [📌 Project Overview](#-project-overview)  
- [🎨 UX/UI Design](#-uxui-design)  
  - [🛠️ User Stories](#-user-stories)  
  - [🎨 Colours](#-colours)  
  - [🔠 Fonts](#-fonts)  
  - [📐 Wireframes](#-wireframes)  
  - [🖼️ Imagery](#-imagery)  
- [🎮 Features](#-features)  
- [🚀 How to Play](#-how-to-play)  
- [🛠️ Technologies Used](#-technologies-used)  
- [🗂️ Project Structure](#-project-structure)  
- [📦 Setup Instructions](#-setup-instructions)  
- [🔍 Example Riddle](#-example-riddle)  
- [Game Rules](#game-rules)  
- [✨ Future Enhancements](#-future-enhancements)  
- [✅ Core Features & Operations Checklist](#-core-features--operations-checklist)  
- [⚙️ Development & Tech Stack](#-development--tech-stack)  
- [🛠️ Bug Prevention & Optimization](#-bug-prevention--optimization)  
- [Contributing](#contributing)  
- [📄 License](#-license)

---

## 📌 Project Overview  
**🎯 Objectives:**  
- Build a professional one-page interactive game using HTML, CSS, and JavaScript  
- Incorporate user experience (UX), accessibility, responsive design, and Web API integrations  
- Utilize Firebase for real-time score tracking  
- Include Speech Recognition API for voice input answers  

---

## 🎨 UX/UI Design  

### 🛠️ User Stories  
**As a user, I want to:**  
✅ See emojis clearly and guess countries from them  
✅ Enter or speak my guess  
✅ Get instant feedback and score updates  
✅ Change languages by clicking flags  
✅ Access "How to Play" instructions at any time  
✅ Track remaining time with visual countdown  
✅ Enjoy responsive design across all devices  
✅ Experience smooth animations and transitions  

### 🎨 Colours  
| Colour  | Hex Code | Usage |
|---------|----------|--------|
| 💙 Electric Blue | `#1E90FF` | Main buttons and links |
| 💛 Lemon Yellow | `#FFF44F` | Highlights and backgrounds |
| ⚪ White | `#FFFFFF` | Card backgrounds |
| ⚫ Black | `#000000` | Text and accents |

### 🔠 Fonts  
- **Segoe UI** (UI and body)  
- **Fredoka One** (headers and emojis)  

### 📐 Wireframes  
📌 [View Wireframes](assets/wireframes/) – Mobile, Tablet, Desktop  

### 🖼️ Imagery  
- Emoji-based UI and live emoji background  
- Language flags for selection  

---

## 🎮 Features

- 🧠 Emoji-based country riddles
- 🎯 Real-time scoring and answer validation  
- 📱 Responsive layout (mobile + desktop)  
- 🎨 Custom styling with emoji icons  
- 🧩 Modular and beginner-friendly JavaScript structure  
- 🕹️ Multiple difficulty levels (Easy, Medium, Hard)  
- ⏳ Timer-based gameplay (30 seconds per round)  
- 🎵 Sound effects and background music (Tone.js)  
- 📊 Score tracking & high scores (LocalStorage, Firebase)  
- 🎭 Light/Dark theme support  
- 🔢 Lives system (3 lives per level)  
- 🌐 Internationalization support with 14 languages
- 🎮 User Interface Layout with responsive design
- 🎮 Language Selector with flag-based selection
- 📝 Form Validation & Input Handling
- 🕹️ Game Flow Logic with question-by-question progression

---

## 🚀 How to Play  

1. Enter your name, age, and gender.  
2. Select your difficulty level (Easy, Medium, Hard).
3. Click **Continue** to begin the game.  
4. View the emoji clue and type the country you think it represents.  
5. Click **Submit** or press Enter to check your answer.  
6. Use **Hint** if needed, or click **Next** to move to the next riddle.
7. Complete all levels to win!

---

## 🛠️ Technologies Used  

- **HTML5, CSS3** – Structuring and styling the game interface.  
- **Vanilla JavaScript (ES6+)** – Core game mechanics.  
- **Firebase Firestore** – Storing player scores.  
- **Tone.js** – Sound effects and background music.  
- **Unicode Emoji Rendering** – No external emoji libraries.  
- **LocalStorage** – Language and score persistence.  

---

## 🗂️ Project Structure

```
📦 ONEPAGE-JS
├── 📂 assets
│   ├── 📂 css
│   │   └── style.css           # Contains all styles for the game UI
│   ├── 📂 images              # Stores game-related images or graphics
│   └── 📂 js
│       ├── firebase-config.js  # Handles Firebase setup
│       └── script.js           # Main game logic (Vanilla JavaScript)
├── firebase.json               # Firebase configuration file
├── index.html                  # Main game interface (entry point)
├── LICENSE                     # License information for project usage
└── README.md                   # Main project documentation
```

---

## 📦 Setup Instructions

1. **Clone this repository:**
   ```bash
   git clone https://github.com/anaylsethis2020/onepage-js.git
   cd onepage-js
   ```

2. **Open `index.html` in your browser.**

3. **Start playing!**

✅ No build tools or dependencies required.

---

## 🔍 Example Riddle

```js
{ emoji: "🍐🦘", answer: "peru" }
{ emoji: "🔗🅰️", answer: "china" }
{ emoji: "4️⃣🐜🐜", answer: "france" }
```

---

## Game Rules

1. **Timer:** You have 30 seconds to guess each country
2. **Lives:** You have 3 lives per level  
3. **Levels:** Complete Easy → Medium → Hard difficulty levels
4. **Scoring:** Score points for correct answers
5. **Progression:** Complete all levels to win!
6. **Lives Reset:** Lives are restored when advancing to a new level

---

## ✨ Future Enhancements

- 🎵 Enhanced background music (MP3 files)
- 🎊 Advanced celebratory effects (confetti, animations)
- 📊 Firebase database support for leaderboard and analytics 
- 🌐 Extended language support with country-specific quiz variations
- 🎨 Animated emojis for responses
- 📖 'How to Play' tutorial screen
- 🎭 Advanced Light/Dark theme selector
- 🎮 Custom avatars or emoji packs
- 🗣️ Voice input using Speech Recognition API

---

## ⚙️ Development & Tech Stack

- **JavaScript (Vanilla)** for logic and DOM manipulation
- **Firebase Firestore** for storing scores and user data
- **CSS3** with responsive design principles
- **Tone.js** for interactive sound effects
- **LocalStorage** for offline data persistence
- **Target Browser:** Chrome (optimized)

---

## 🛠️ Bug Prevention & Optimization

- Modular function-based scripting (avoid large script blocks)
- Detailed code comments for clarity
- Error-handling boundaries for Firebase interactions
- Input validation before processing changes
- DOM updates triggered only after validation
- Event listener management to prevent memory leaks
- Responsive design testing across devices

---

## ✅ Core Features & Operations Checklist

1. **User Interface Layout**
   - Retain existing CSS layout unless bug fixes are required.
   - Responsive layout optimized for Chrome.
   - Minimal layout changes unless necessary for functionality.

2. **Language Selector**
   - Dropdown or sidebar list for language selection.
   - One selected language must persist throughout the session.
   - Prevent duplicate selection buttons.

3. **User Input Form (Pre-Game)**
   - Name input field.
   - Age confirmation (optional).
   - Language selection (mandatory before continuing).
   - 'Continue' button activates **only** after all required fields are filled.

4. **Game Window**
   - Displays one emoji-country riddle at a time.
   - Text input field for guesses.
   - Submit button for answer checking.
   - 'Next' button appears only after feedback is displayed.
   - Animated feedback (`✅ correct / ❌ incorrect`)

5. **Score Tracking**
   - Visual score counter (correct answers only).
   - Local scoring system using vanilla JavaScript.
   - Optional: Firebase Firestore integration for score history.

6. **Game Timer**
   - Countdown starts upon game initiation.
   - Timer visually displayed.
   - Automatic end when timer hits 0.

7. **Game Summary Screen**
   - Displays final score.
   - Restart option available.
   - Optional: Save score with initials (if Firebase is used).

8. **Difficulty Levels**
   - Three selectable difficulties: **Easy, Medium, Hard**.
   - Hard mode applies stricter time limits and fewer hints.

9. **Lives System**
   - Each player gets **three lives per level**.
   - Losing all lives ends the round early.
   - Lives reset when advancing to a new level.

10. **Sound Effects & Background Music**
    - Uses **Tone.js** for interactive sounds.
    - Background music can be toggled **on/off** in settings.
    - Sound feedback for correct/incorrect answers.

11. **Firebase Firestore Integration**
    - Stores player name, score, language, and timestamp.
    - Displays top five leaderboard scores.
    - Input sanitization to prevent invalid submissions.

12. **Form Validation & Input Handling**
    - Prevent empty submissions.
    - Validate text answers (case insensitive).
    - Auto-clear input field after submission.

13. **Game Flow Logic**
    - Starts only after required inputs (name, age, mode selection).
    - Operates question-by-question.
    - Timer resets each round (30s per question).
    - Auto-advance to next question if timer runs out (+1 incorrect score).
    - Prevents resubmission bugs by disabling buttons after interactions.
    - Displays real-time progress (`Question X of Y`).
    - Smooth transitions between questions, score updates, and game-end states.

---

## Contributing

Feel free to submit issues and enhancement requests! 

**Development Guidelines:**
- Follow existing code style and structure
- Test thoroughly before submitting PRs
- Update documentation for new features
- Ensure cross-browser compatibility

---

## 📄 License

MIT License © 2025 Abel Beyene

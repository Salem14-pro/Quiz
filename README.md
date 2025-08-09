# 🧠 Trivia Master Quiz App

<div align="center">

![Quiz App Banner](https://img.shields.io/badge/Quiz-Master-brightgreen?style=for-the-badge&logo=quiz&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

**A modern, interactive trivia quiz application inspired by Trivia Crack**

[Live Demo](#) • [Features](#features) • [Installation](#installation) • [Usage](#usage) • [Contributing](#contributing)

</div>

---

## 📋 Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Demo](#demo)
- [Installation](#installation)
- [Usage](#usage)
- [Game Mechanics](#game-mechanics)
- [Categories](#categories)
- [Technical Details](#technical-details)
- [File Structure](#file-structure)
- [Customization](#customization)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgments](#acknowledgments)

## 🎯 Overview

Trivia Master is a comprehensive quiz application that brings the excitement of trivia games to your browser. Built with vanilla HTML, CSS, and JavaScript, it offers an engaging quiz experience with multiple categories, difficulty levels, and interactive features that rival popular quiz apps like Trivia Crack.

### Why Trivia Master?

- 🚀 **Zero Dependencies**: Pure vanilla JavaScript, no frameworks required
- 📱 **Fully Responsive**: Perfect experience on desktop, tablet, and mobile
- 🎨 **Modern UI/UX**: Clean, engaging design with smooth animations
- 🧠 **120+ Questions**: Diverse questions across 6 categories
- 🏆 **Achievement System**: Badges and performance tracking
- 💾 **Local Storage**: Saves your progress and high scores
- ⚡ **Fast Performance**: Lightweight and optimized for speed

## ✨ Features

### 🎮 Core Game Features
- **6 Quiz Categories**: Science, History, Sports, Entertainment, Geography, Art & Literature
- **3 Difficulty Levels**: Easy (10pts), Medium (20pts), Hard (30pts)
- **Smart Scoring System**: Points based on difficulty with streak bonuses
- **Progress Tracking**: Visual progress bar and question counter
- **Timer System**: Optional 30-second countdown per question
- **Question Bank**: 20+ unique questions per category (120+ total)

### 🛠️ Interactive Elements
- **Lifelines**: 50/50, Skip Question, Extra Time
- **Instant Feedback**: Visual indicators for correct/incorrect answers
- **Smooth Animations**: CSS transitions and engaging micro-interactions
- **Sound Effects**: Optional audio feedback with mute toggle
- **Achievement Badges**: Unlock special badges for outstanding performance

### 📊 Analytics & Tracking
- **Detailed Statistics**: Track performance across all categories
- **High Score System**: Local leaderboard with persistent storage
- **Performance Analytics**: Success rate, favorite categories, and more
- **Session History**: Review your recent game performances

### 🎨 User Experience
- **Dark/Light Mode**: Toggle between themes for comfortable viewing
- **Responsive Design**: Seamless experience across all devices
- **Accessibility**: ARIA labels, keyboard navigation, and screen reader support
- **Offline Capable**: Works without internet connection after initial load

## 🎥 Demo

### Game Flow
1. **Welcome Screen** → Choose your settings and start playing
2. **Category Selection** → Pick from 6 engaging categories
3. **Quiz Questions** → Answer progressively challenging questions
4. **Real-time Feedback** → See your progress and score updates
5. **Results Dashboard** → Comprehensive performance analysis

### Screenshots
```
[Welcome Screen] → [Category Selection] → [Quiz Interface] → [Results Page]
```

## 🚀 Installation

### Option 1: Direct Download
1. Clone or download this repository
2. Open `index.html` in your web browser
3. Start playing immediately!

### Option 2: Local Server (Recommended)
```bash
# Clone the repository
git clone https://github.com/yourusername/trivia-master-quiz.git

# Navigate to the project directory
cd trivia-master-quiz

# Start a local server (Python 3)
python -m http.server 8000

# Or with Node.js
npx http-server

# Open browser to http://localhost:8000
```

### Option 3: GitHub Pages
Fork this repository and enable GitHub Pages in your repository settings to get an instant live demo.

## 📖 Usage

### Quick Start
1. Open the application in your browser
2. Click "Start Game" on the welcome screen
3. Select your preferred settings (timer, difficulty)
4. Choose a category to begin
5. Answer questions and track your progress
6. View your results and try to beat your high score!

### Game Controls
- **Mouse/Touch**: Click/tap to select answers
- **Keyboard**: Use number keys (1-4) to select options
- **Spacebar**: Use lifelines or skip questions
- **Esc**: Pause game or return to menu

### Lifelines
- **50/50**: Removes two incorrect options
- **Skip Question**: Move to the next question without penalty
- **Extra Time**: Adds 15 seconds to the current question timer

## 🎯 Game Mechanics

### Scoring System
- **Easy Questions**: 10 points each
- **Medium Questions**: 20 points each  
- **Hard Questions**: 30 points each
- **Streak Bonus**: +5 points for each consecutive correct answer
- **Speed Bonus**: Extra points for quick answers (when timer is enabled)

### Performance Tracking
The game tracks various metrics:
- Total games played
- Overall accuracy percentage
- Best score achieved
- Favorite category
- Average response time
- Longest streak

### Achievement System
Unlock special badges:
- 🏆 **Perfect Score**: Answer all questions correctly
- 🔥 **Speed Demon**: Complete game under 5 minutes
- 🧠 **Category Master**: 90%+ accuracy in a specific category
- ⚡ **Lightning Round**: 5+ quick answers in a row
- 🎯 **Sharpshooter**: 10+ correct answers in a row

## 📚 Categories

### 🔬 Science
Biology, Chemistry, Physics, Astronomy, Environmental Science
*Sample*: "What is the chemical symbol for gold?"

### 📜 History  
World History, Ancient Civilizations, Wars, Historical Figures
*Sample*: "In which year did World War II end?"

### ⚽ Sports
Olympics, Football, Basketball, Tennis, International Sports
*Sample*: "Which country has won the most FIFA World Cups?"

### 🎬 Entertainment
Movies, Music, TV Shows, Celebrities, Pop Culture
*Sample*: "Who directed the movie 'Inception'?"

### 🌍 Geography
Countries, Capitals, Landmarks, Physical Geography, Flags
*Sample*: "What is the capital of Australia?"

### 🎨 Art & Literature
Famous Authors, Paintings, Literature, Classical Works, Artists
*Sample*: "Who wrote the novel '1984'?"

## 🛠️ Technical Details

### Technologies Used
- **HTML5**: Semantic markup with accessibility features
- **CSS3**: Modern styling with Flexbox/Grid, animations, and responsive design
- **Vanilla JavaScript**: ES6+ features, modular architecture, and efficient DOM manipulation

### Browser Compatibility
- ✅ Chrome 70+
- ✅ Firefox 65+
- ✅ Safari 12+
- ✅ Edge 79+
- ✅ Mobile browsers (iOS Safari, Chrome Mobile)

### Performance
- **Initial Load**: < 2 seconds
- **Question Transitions**: < 200ms
- **Memory Usage**: < 10MB
- **Offline Support**: Full functionality after initial load

### Code Quality
- **ES6+ JavaScript**: Modern syntax with proper error handling
- **Modular Architecture**: Organized, reusable code structure  
- **Responsive CSS**: Mobile-first approach with fluid layouts
- **Accessibility**: WCAG 2.1 compliant with screen reader support

## 📁 File Structure

```
trivia-master-quiz/
│
├── index.html              # Main application file
├── README.md               # This file
├── LICENSE                 # MIT license
│
├── assets/                 # (Optional: for external assets)
│   ├── icons/              # Category and UI icons
│   ├── sounds/             # Sound effects
│   └── images/             # Background images and graphics
│
└── docs/                   # (Optional: documentation)
    ├── CONTRIBUTING.md     # Contribution guidelines
    ├── CHANGELOG.md        # Version history
    └── API.md              # Code documentation
```

## 🎨 Customization

### Adding New Questions
Questions are stored in the JavaScript object within `index.html`. Add new questions following this structure:

```javascript
{
  id: 121,
  category: "Science",
  difficulty: "medium",
  question: "What is the hardest natural substance on Earth?",
  options: ["Diamond", "Graphite", "Quartz", "Steel"],
  correct: 0,
  explanation: "Diamond is the hardest natural substance, ranking 10 on the Mohs scale.",
  points: 20
}
```

### Modifying Categories
To add or modify categories:
1. Update the `categories` array
2. Add corresponding questions to the `questionBank`
3. Update category icons and colors in the CSS

### Styling Customization
The app uses CSS custom properties for easy theming:

```css
:root {
  --primary-color: #4CAF50;
  --secondary-color: #2196F3;
  --accent-color: #FF9800;
  --background-color: #f5f5f5;
  --text-color: #333;
}
```

### Feature Toggles
Enable/disable features by modifying the configuration object:

```javascript
const gameConfig = {
  enableTimer: true,
  timerDuration: 30,
  enableSound: true,
  enableLifelines: true,
  maxLifelines: 3
};
```

## 🤝 Contributing

We welcome contributions! Here's how you can help:

### Ways to Contribute
- 🐛 **Bug Reports**: Found a bug? Create an issue with detailed steps to reproduce
- 💡 **Feature Requests**: Have an idea? Share it in the issues section
- 📝 **Question Bank**: Add new questions to expand our database
- 🎨 **UI/UX Improvements**: Enhance the design and user experience
- 🔧 **Code Improvements**: Optimize performance or add new features

### Development Setup
1. Fork the repository
2. Create a feature branch: `git checkout -b feature-name`
3. Make your changes and test thoroughly
4. Commit with clear messages: `git commit -m "Add new feature"`
5. Push to your fork: `git push origin feature-name`
6. Submit a pull request

### Coding Standards
- Use modern JavaScript (ES6+)
- Follow consistent indentation (2 spaces)
- Add comments for complex logic
- Test across multiple browsers
- Maintain responsive design principles

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

```
MIT License

Copyright (c) 2025 Trivia Master Quiz App

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.
```

## 🙏 Acknowledgments

- **Inspiration**: Trivia Crack and other popular quiz applications
- **Icons**: Lucide Icons for beautiful UI elements
- **Fonts**: Google Fonts for typography
- **Colors**: Material Design color palette
- **Community**: Thanks to all contributors and users

---

<div align="center">

**Made with ❤️ for quiz enthusiasts everywhere**

[⭐ Star this repo](../../stargazers) • [🐛 Report Bug](../../issues) • [💡 Request Feature](../../issues)

[![GitHub stars](https://img.shields.io/github/stars/yourusername/trivia-master-quiz?style=social)](../../stargazers)
[![GitHub forks](https://img.shields.io/github/forks/yourusername/trivia-master-quiz?style=social)](../../network)

</div>

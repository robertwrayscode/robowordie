# RoboWordie 🤖

A Wordle-style word guessing game with helpful clues to guide you along the way!

## 🎮 Play Now

**Live Demo:** [https://cluedle-game.netlify.app](https://cluedle-game.netlify.app)

## ✨ Features

- **Classic Wordle Gameplay**: Guess the 5-letter word in 6 tries
- **Helpful Clues**: Get hints after each guess to help you solve the puzzle
- **Clean Design**: Minimalist interface inspired by the original Wordle
- **Mobile-Friendly**: On-screen keyboard works perfectly on iPhone and mobile devices
- **Customizable Settings**:
  - 🌙 **Dark Theme** - Easy on the eyes
  - 🎨 **High Contrast Mode** - Better for colorblind users (orange/blue instead of green/yellow)
  - 💪 **Hard Mode** - Revealed hints must be used in subsequent guesses
- **Word Lists**: Multiple difficulty levels with curated word sets

## 🎯 How to Play

1. Guess a 5-letter word
2. Get color-coded feedback:
   - 🟩 **Green** - Letter is correct and in the right position
   - 🟨 **Yellow** - Letter is in the word but wrong position
   - ⬛ **Gray** - Letter is not in the word
3. Get a helpful clue after each guess
4. Solve the word in 6 guesses or less!

## 🚀 Deployment

This game is deployed on Netlify:
- Automatic deployments from the `main` branch
- Custom domain support
- Instant rollbacks

To deploy your own:
```bash
npm install -g netlify-cli
netlify deploy --prod
```

## 🛠️ Tech Stack

- **Pure HTML/CSS/JavaScript** - No frameworks needed
- **Netlify** - Hosting and deployment
- **localStorage** - Persists user settings

## 📝 License

MIT License - Feel free to use and modify!

## 👨‍💻 Author

Created by Robert Wray

---

Enjoy playing RoboWordie! 🎯

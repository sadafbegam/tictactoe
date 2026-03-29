# ❌⭕ Tic-Tac-Toe Game

<div align="center">

![React](https://img.shields.io/badge/React-18.x-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![JavaScript](https://img.shields.io/badge/JavaScript-ES6-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![CSS3](https://img.shields.io/badge/CSS3-Styled-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)

### A classic Tic-Tac-Toe game built with React

[View Demo](https://sadafbegam.github.io/tictactoe) · [Report Bug](https://github.com/sadafbegam/tictactoe/issues) · [Request Feature](https://github.com/sadafbegam/tictactoe/issues)

</div>

---

## 📸 Screenshots

<div align="center">

### Game Board
![Game Screenshot 1](Screenshot%202026-03-29%20113549.png)

### Gameplay
![Game Screenshot 2](Screenshot%202026-03-29%20114225.png)

</div>

---

## 🎮 About The Project

A fully functional Tic-Tac-Toe game built with React, featuring a clean UI and smooth gameplay. Challenge your friend in this classic two-player game!

### ✨ Features

- ✅ **Two-player gameplay** - Play against a friend
- 🎨 **Clean and intuitive UI** - Easy to understand and play
- 🔄 **Turn indicator** - Shows whose turn it is (X or O)
- 🏆 **Winner detection** - Automatically detects the winner
- 🔁 **Reset functionality** - Start a new game anytime
- 📱 **Responsive design** - Works on all screen sizes
- ⚡ **Fast and lightweight** - Built with vanilla React
- 🎯 **Interactive squares** - Smooth click interactions

---

## 🛠️ Built With

- **React** - JavaScript library for building user interfaces
- **JavaScript (ES6+)** - Modern JavaScript features
- **CSS3** - Styling and animations
- **HTML5** - Semantic markup

---

## 🚀 Getting Started

Follow these steps to run the project locally:

### Prerequisites

Make sure you have Node.js and npm installed:

```bash
node --version
npm --version
```

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/sadafbegam/tictactoe.git
   ```

2. **Navigate to project directory**
   ```bash
   cd tictactoe/tic-tac-toe
   ```

3. **Install dependencies**
   ```bash
   npm install
   ```

4. **Start the development server**
   ```bash
   npm start
   ```

5. **Open your browser**
   ```
   Visit http://localhost:3000
   ```

---

## 📂 Project Structure

```
tictactoe/
├── tic-tac-toe/
│   ├── public/
│   │   └── index.html
│   ├── src/
│   │   ├── Components/
│   │   │   └── TicTacToe.js
│   │   ├── App.js
│   │   ├── App.css
│   │   ├── index.js
│   │   └── index.css
│   ├── package.json
│   └── README.md
├── Screenshot 2026-03-29 113549.png
├── Screenshot 2026-03-29 114225.png
└── README.md
```

---

## 🎯 How to Play

1. **Start the game** - The game begins with Player X
2. **Take turns** - Players alternate clicking on empty squares
3. **Get three in a row** - First player to get 3 marks in a row (horizontal, vertical, or diagonal) wins!
4. **Reset** - Click the reset button to start a new game

### Game Rules:
- ❌ Player 1 uses **X**
- ⭕ Player 2 uses **O**
- Players take turns marking empty squares
- First to get 3 in a row wins
- If all 9 squares are filled without a winner, it's a draw

---

## 💻 Code Highlights

### React State Management
```javascript
const [board, setBoard] = useState(Array(9).fill(null))
const [isXTurn, setIsXTurn] = useState(true)
```

### Winner Detection Algorithm
The game includes smart logic to detect all possible winning combinations:
- Horizontal wins (rows)
- Vertical wins (columns)
- Diagonal wins (both directions)

### Dynamic UI Updates
Real-time board updates with React's state management for smooth gameplay.

---

## 📚 What I Learned

Building this project helped me improve my skills in:

- ✅ **React Hooks** - Using `useState` for state management
- ✅ **Component Architecture** - Building reusable components
- ✅ **Game Logic** - Implementing win conditions and turn management
- ✅ **Event Handling** - Managing user interactions
- ✅ **CSS Styling** - Creating a polished user interface
- ✅ **Array Manipulation** - Working with game board state
- ✅ **Conditional Rendering** - Displaying game status dynamically

---

## 🔮 Future Enhancements

Planned features for future versions:

- [ ] **AI opponent** - Play against the computer
- [ ] **Score tracking** - Keep track of wins/losses
- [ ] **Animations** - Add smooth transitions and effects
- [ ] **Sound effects** - Add audio feedback
- [ ] **Themes** - Dark mode and color customization
- [ ] **Difficulty levels** - Easy, Medium, Hard AI
- [ ] **Online multiplayer** - Play with friends remotely
- [ ] **Game history** - View past moves

---

## 🤝 Contributing

Contributions are welcome! Here's how you can help:

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

---

## 📝 Available Scripts

In the project directory, you can run:

### `npm start`
Runs the app in development mode at [http://localhost:3000](http://localhost:3000)

### `npm test`
Launches the test runner in interactive watch mode

### `npm run build`
Builds the app for production to the `build` folder

### `npm run eject`
**Note: this is a one-way operation!**

---

## 📄 License

This project is open source and available for educational purposes.

---

## 👤 Author

**Sadaf Begam**

- GitHub: [@sadafbegam](https://github.com/sadafbegam)
- LinkedIn: [sadafbegam-t-sk](https://linkedin.com/in/sadafbegam-t-sk)
- Email: tshaiksadafbegum@gmail.com

---

## 🙏 Acknowledgments

- Inspired by the classic Tic-Tac-Toe game
- Built as a learning project to practice React concepts
- Thanks to the React community for excellent documentation

---

<div align="center">

### ⭐ If you like this project, please give it a star!

**Made with ❤️ by [Sadaf Begam](https://github.com/sadafbegam)**

*Happy Gaming!* 🎮

</div>







# Getting Started with Create React App

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`

**Note: this is a one-way operation. Once you `eject`, you can't go back!**

If you aren't satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you're on your own.

You don't have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn't feel obligated to use this feature. However we understand that this tool wouldn't be useful if you couldn't customize it when you are ready for it.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).

### Code Splitting

This section has moved here: [https://facebook.github.io/create-react-app/docs/code-splitting](https://facebook.github.io/create-react-app/docs/code-splitting)

### Analyzing the Bundle Size

This section has moved here: [https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size](https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size)

### Making a Progressive Web App

This section has moved here: [https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app](https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app)

### Advanced Configuration

This section has moved here: [https://facebook.github.io/create-react-app/docs/advanced-configuration](https://facebook.github.io/create-react-app/docs/advanced-configuration)

### Deployment

This section has moved here: [https://facebook.github.io/create-react-app/docs/deployment](https://facebook.github.io/create-react-app/docs/deployment)

### `npm run build` fails to minify

This section has moved here: [https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify](https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify)

# Tic Tac Toe Game

A modern implementation of the classic Tic Tac Toe game built with React, TypeScript, and Tailwind CSS.

## Features

- 🎮 Classic Tic Tac Toe gameplay
- 📊 Score tracking for both players
- 🔄 Game history tracking
- 🎯 Win detection with winning line highlight
- 🔄 New game and reset functionality
- 🎨 Modern, responsive UI with Tailwind CSS
- 💻 Built with TypeScript for type safety

## Tech Stack

- React
- TypeScript
- Tailwind CSS
- Vite (Build tool)
- ESLint
- PostCSS

## Getting Started

### Prerequisites

- Node.js (v14 or higher)
- npm or yarn

### Installation

1. Clone the repository
```bash
git clone https://github.com/himavanthreddy94/tictactoe-devsecops-pipeline.git
```

2. Install dependencies
```bash
npm install
# or
yarn install
```

3. Start the development server
```bash
npm run dev
# or
yarn dev
```

4. Open your browser and visit `http://localhost:5173`

## Game Rules

- Players take turns placing their marks (X or O) in empty squares
- The first player to get 3 of their marks in a row (up, down, across, or diagonally) wins
- When all 9 squares are filled and there's no winner, the game is a draw

## Project Structure

```
Project1_tictactoe/
├── src/
│   ├── components/     # React components
│   ├── utils/          # Utility functions
│   ├── __tests__/     # Test files
│   ├── App.tsx        # Main application component
│   └── main.tsx       # Application entry point
├── public/            # Static assets
└── package.json       # Project dependencies and scripts
```

## License

MIT License
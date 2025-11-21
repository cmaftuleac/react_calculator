# React Calculator App

A beautiful, modern calculator web application built with React and Vite.

## Features

- ✨ Modern, gradient-based UI design
- 🧮 Basic arithmetic operations (addition, subtraction, multiplication, division)
- 🔢 Decimal number support
- ➕ Additional functions (percentage, sign toggle)
- 📱 Fully responsive design
- 🎨 Smooth animations and hover effects

## Tech Stack

- **React 18** - UI library
- **Vite** - Build tool and dev server
- **CSS3** - Styling with gradients and modern effects

## Getting Started

### Prerequisites

- Node.js (version 14 or higher)
- npm or yarn

### Installation

1. Install dependencies:

```bash
npm install
```

### Running the App

Start the development server:

```bash
npm run dev
```

The app will open at `http://localhost:5173`

### Building for Production

Create an optimized production build:

```bash
npm run build
```

Preview the production build:

```bash
npm run preview
```

## Usage

- Click number buttons to input digits
- Click operation buttons (+, −, ×, ÷) to perform calculations
- Click `=` to see the result
- Click `AC` to clear all
- Click `+/-` to toggle between positive and negative
- Click `%` to convert to percentage
- Click `.` to input decimal numbers

## Project Structure

```
/workspace/
├── index.html              # HTML entry point
├── package.json            # Project dependencies
├── vite.config.js          # Vite configuration
├── src/
│   ├── main.jsx            # React entry point
│   ├── App.jsx             # Main App component
│   ├── App.css             # App styles
│   ├── index.css           # Global styles
│   └── components/
│       ├── Calculator.jsx  # Calculator component
│       └── Calculator.css  # Calculator styles
└── README.md               # This file
```

## License

MIT

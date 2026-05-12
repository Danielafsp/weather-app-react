# ⛅ Weather App — React

A weather application built with React that displays real-time weather conditions and a multi-day forecast for any city in the world. This project was the final project of the [SheCodes React](https://www.shecodes.io/) program, and marks the evolution from the [vanilla JS version](https://github.com/Danielafsp/Weather-app) to a fully component-based React architecture.

🔗 **Live demo:** [skycheck-weather.netlify.app](https://skycheck-weather.netlify.app/)

---

## 📋 About the Project

After building a weather app with vanilla JavaScript, this React version was developed to apply the same core functionality using a modern component-based approach. The focus was on understanding how React manages UI through state and props, and how to structure an app into reusable components.

---

## ✨ Features

- 🔍 Search weather by city name
- 🌡️ Current temperature in Celsius
- 💧 Humidity and wind speed display
- 🕐 Local time and weather description
- 🎞️ Animated weather icons (via `react-animated-weather`)
- 📱 Responsive layout with Bootstrap 5

---

## 🛠️ Built With

| Technology | Purpose |
|---|---|
| React 18 | Component-based UI |
| JavaScript (ES6+) | App logic |
| CSS3 | Custom styling |
| [Axios](https://axios-http.com/) | HTTP requests |
| [Bootstrap 5](https://getbootstrap.com/) + React-Bootstrap | Responsive layout and UI components |
| [react-animated-weather](https://www.npmjs.com/package/react-animated-weather) | Animated weather icons |
| [SheCodes Weather API](https://www.shecodes.io/learn) | Real-time weather data |
| [Netlify](https://www.netlify.com/) | Deployment |

---

## 🚀 Getting Started

```bash
# Clone the repository
git clone https://github.com/Danielafsp/weather-app-react.git

# Navigate to the project folder
cd final-project

# Install dependencies
npm install

# Start the development server
npm start
```

The app will open at `http://localhost:3000`.

---

## 📁 Project Structure

```
final-project/
├── public/
│   └── index.html
├── src/
│   ├── components/       # React components (Weather, Forecast, etc.)
│   ├── App.js            # Root component
│   ├── App.css           # Global styles
│   └── index.js          # Entry point
├── package.json
└── README.md
```

---

## 🔄 Vanilla JS vs React — What Changed

This project was built after the [vanilla JS weather app](https://github.com/Danielafsp/Weather-app), with the same features but a completely different architecture:

| | Vanilla JS | React |
|---|---|---|
| UI updates | Manual DOM manipulation | State-driven re-renders |
| Code structure | Single script file | Reusable components |
| Data flow | Global variables | Props and state |
| Side effects | Inline callbacks | `useEffect` hook |

---

## 💡 What I Learned

- Structuring an app into independent, reusable React components
- Managing state with `useState` and side effects with `useEffect`
- Passing data between components via props
- Integrating third-party React libraries (`react-animated-weather`, `react-bootstrap`)
- Building and deploying a React app to Netlify

---

## 👩‍💻 Author

**Daniela Pereira**
[GitHub](https://github.com/Danielafsp) · [LinkedIn](https://www.linkedin.com/in/daniela-pereira-b42305117/)

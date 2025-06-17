# 🌍 Weather Forecast Web App (Single HTML File)

This is a creative weather forecast web app built entirely in **one HTML file** using **HTML, CSS, JavaScript, and JSON** — powered by the [7Timer API](http://7timer.info/). What makes this project unique is the **use of prompt engineering (via AI)** to design and implement animations, weather effects, and a rotating Earth background.

---

## 🚀 Features

- 📦 **Single HTML File**: All logic, styles, and structure in one file for portability and simplicity.
- 🤖 **Prompt-Driven Design**: Used AI tools (like ChatGPT) to convert visual UI ideas into code (animations, layout, physics effects).
- 🌐 **7Timer API** Integration: Real-time 7-day forecast using city coordinates.
- 🌍 **3D Earth Background**: Rotates 360° in the background using Three.js or CSS animation.
- 🧊 **Interactive Forecast Cards**:
  - Flip on hover to reveal more info.
  - Show general weather on front and details on back.
- ❄️ **Custom Animations**:
  - 🌧️ Rain – falling droplets on the card
  - ❄️ Snow – snowflakes that pile or slide realistically
  - 💨 Wind – wind lines or particles blowing across text/icons
- 🎨 **Creative Visuals**: Fonts, shadows, and effects designed for clarity and emotion.

---

## 🗺️ How It Works

1. The user selects a city from a CSV-powered list (in dropdown or predefined options).
2. Coordinates are passed to fetch 7-day data from 7Timer API.
3. Cards are created dynamically for each day.
4. Based on weather type (e.g., `snow`, `rain`, `cloudy`, `clear`), animation and visuals are adjusted using condition checks.
5. All animations and logic live inside one HTML file — no need to manage multiple files.

---

## 💡 Inspiration & AI Usage

This project was made not just by writing code but by:
- Using **prompt engineering** with tools like ChatGPT to generate UI/UX ideas.
- Describing visual behaviors (e.g., "snow piling on text") and converting them into working CSS/JS code.
- Fast prototyping ideas like Earth rotation and weather animations in one go.

---

## 📦 Tech Stack

- HTML5
- CSS3 (Custom animations, Flex/Grid layout)
- JavaScript (DOM manipulation, API fetch)
- [7Timer Weather API](http://7timer.info/doc.php)
- (Optional) Three.js or Canvas for Earth visual

---

## 📸 Screenshots (Optional)

| Earth View | Weather Cards | Snow/Rain Animations |
|------------|----------------|----------------------|
| ![earth](link) | ![cards](link) | ![effects](link) |

---

## 🔧 How to Run

1. Clone this repo or download the `.html` file
2. Open the file in any modern browser
3. Select a city and explore the animated 7-day forecast

```bash
git clone https://github.com/yourusername/weather-ai-app.git
cd weather-ai-app
open index.html

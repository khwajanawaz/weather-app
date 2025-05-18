
# 🌦️ Weather App Project

This is a simple and beautiful weather application built using **HTML**, **CSS**, and **JavaScript**. It allows users to enter a city name and fetch real-time weather information using the OpenWeatherMap API. The UI updates dynamically with custom weather icons and styles.

---

## 🚀 Features

- Get live weather data by city name  
- Custom weather icons for different conditions (rain, snow, wind, etc.)  
- Responsive and clean UI design  
- Error handling for invalid city names  

---

## 🛠️ Project Structure

```
📦 main
 ┣ 📂 images/
 ┃ ┣ 📄 clear.png
 ┃ ┣ 📄 clouds.png
 ┃ ┣ 📄 drizzle.png
 ┃ ┣ 📄 humidity.png
 ┃ ┣ 📄 rain.png
 ┃ ┣ 📄 search.png
 ┃ ┣ 📄 snow.png
 ┃ ┣ 📄 wind.png
 ┣ 📄 index.html
 ┣ 📄 style.css
 ┣ 📄 README.md
```

---

## 📌 Steps You Followed

### 1. Created `index.html` file:
- Added the main structure of the weather app.
- Included search input and button for city name.
- Displayed weather info using placeholders for icons, temperature, humidity, etc.

### 2. Designed UI with `style.css`:
- Set background gradient and styling for the `.card`.
- Applied responsive design using `max-width` and `flex`.
- Styled icons and weather details neatly with custom fonts.

### 3. Added Icons:
- Used custom `.png` icons for weather conditions (`rain.png`, `clouds.png`, etc.).
- Organized them under the same directory to keep things clean.

### 4. Handled Invalid Input:
- Displayed an error message when the user entered an invalid city name.

### 5. Connected Weather API (OpenWeatherMap):
- (Assuming JavaScript was added later) Connected to the OpenWeatherMap API using JS.
- Parsed and displayed live data dynamically.

---

## 💻 How to Run Locally

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/weather-app.git
   ```

2. Open `index.html` in any browser:
   ```bash
   open index.html
   ```

---

## ✅ Conclusion

This weather app demonstrates how to combine **HTML**, **CSS**, and simple logic (with JavaScript or a placeholder API call) to build a visually appealing and functional application. It's a great beginner-friendly project to understand DOM manipulation, API integration, and styling.

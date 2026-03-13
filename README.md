# 🌤️ Async Weather Tracker

A modern **JavaScript Weather App** that demonstrates how the **JavaScript Event Loop, Async/Await, Promises, and API fetching** work in real time.
The application fetches live weather data from the **OpenWeatherMap API** and visually displays the **execution order of synchronous code, microtasks, and macrotasks** in a console panel.

---

# 🚀 Features

### 🌍 Weather Search

* Search weather information by entering any **city name**
* Displays:

  * Temperature
  * Weather condition
  * Humidity
  * Wind speed
  * Country

### ⚡ Async JavaScript Demonstration

Shows how the **JavaScript Event Loop works** using:

* Synchronous code
* `Promise.then()` (Microtask)
* `setTimeout()` (Macrotask)
* `async/await` API calls

The console section visually logs the execution order.

### 🧠 Search History

* Stores previously searched cities
* Uses **Local Storage**
* Keeps the **last 6 searches**
* Click any history item to fetch weather again instantly

### 🛡 Error Handling

Handles common errors such as:

* Invalid city names
* Network/API issues
* Empty search input

---

# 🖼️ Application UI

The app includes three main sections:

1. **Search City Panel**

   * Enter a city
   * Search button
   * Search history

2. **Weather Info Panel**

   * Displays live weather data

3. **Console – Event Loop**

   * Displays execution logs to illustrate async JavaScript behavior

---

# 🛠️ Technologies Used

* **HTML5**
* **CSS3**
* **JavaScript (ES6+)**
* **Async / Await**
* **Promises**
* **Fetch API**
* **OpenWeatherMap API**
* **Local Storage**

---

# 📦 Project Structure

```
async-weather-tracker/
│
├── index.html        # Main application file
├── README.md         # Project documentation
```

---

# 🔑 API Setup

This project uses the **OpenWeatherMap API**.

### Steps to get your API key

1. Go to
   https://openweathermap.org/api

2. Create a free account

3. Generate an API key

4. Replace the API key inside the script:

```javascript
const API_KEY = "YOUR_API_KEY_HERE";
```

---

# ▶️ How to Run the Project

### Option 1 — Simple Method

1. Download or clone the repository

```
git clone https://github.com/chiragchanchal/Async-Weather-Tracker
```

2. Open the folder

3. Double click

```
index.html
```

The app will run in your browser.

---

### Option 2 — Using Live Server (Recommended)

If using **VS Code**:

1. Install the **Live Server extension**
2. Right click `index.html`
3. Click **Open with Live Server**

---

# 🧩 How the Event Loop Demonstration Works

When you search a city, the following code executes:

```
Sync Start
Promise.then (Microtask)
setTimeout (Macrotask)
[ASYNC] START fetching
Sync End
```

This helps visualize how JavaScript prioritizes tasks in the **Event Loop**.

Execution Order:

1️⃣ Synchronous Code
2️⃣ Microtasks (Promises)
3️⃣ Macrotasks (`setTimeout`)
4️⃣ Async API response

---

# 📚 Learning Purpose

This project is great for understanding:

* JavaScript **Event Loop**
* **Async / Await**
* **Promises**
* **API requests**
* **Error handling**
* **Local Storage**

It is suitable for **JavaScript beginners and intermediate developers**.

---

# 🔮 Possible Improvements

Future enhancements could include:

* 5-day weather forecast
* Weather icons
* Dark/light theme
* Loading animations
* Geolocation support
* Mobile UI improvements

---

# 🤝 Contributing

Contributions are welcome!

1. Fork the repository
2. Create a new branch
3. Make your changes
4. Submit a Pull Request

---

# 📄 License

This project is open-source and available under the **MIT License**.

---

# 👨‍💻 Author

Developed as a project to demonstrate **asynchronous JavaScript behavior and API integration**.

If you like this project, consider giving it a ⭐ on GitHub.

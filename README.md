# 💱 Currency Converter

A clean, responsive, and real-time Currency Converter web application built with vanilla **HTML**, **CSS**, and **JavaScript**. It fetches live foreign exchange rates and dynamically displays the corresponding country flags as you select different currencies.

---

## 🚀 Live Demo

<!-- Replace with your GitHub Pages or Vercel link once deployed -->
> **[View Live Demo](https://your-username.github.io/currency-converter/)** *(Add your deployed link here)*

---

## ✨ Features

- **Real-Time Exchange Rates**: Fetches live and accurate currency conversion rates using the Frankfurter API.
- **Dynamic Country Flags**: Automatically updates national flags using the Flags API whenever a currency is selected.
- **Extensive Currency Support**: Supports over 150+ currencies mapped with their respective country codes.
- **Instant Initial Conversion**: Automatically calculates the default rate (USD to INR) on page load.
- **Input Validation**: Ensures valid conversion amount (defaults to 1 if empty or less than 1).
- **Clean & Intuitive UI**: Centered card design styled with custom CSS and modern FontAwesome icons.

---

## 🛠️ Tech Stack & Resources

- **HTML5**: Semantic markup for forms and layouts.
- **CSS3**: Custom modern styling, responsive flexbox layout, and clean form inputs.
- **JavaScript (ES6+)**: Asynchronous fetching (`async`/`await`), dynamic DOM manipulation, and event handling.
- **APIs & CDN Services**:
  - [Frankfurter API](https://api.frankfurter.dev/): Free, open-source exchange rates API.
  - [Flags API](https://flagsapi.com/): Dynamic high-resolution country flag images.
  - [Font Awesome](https://fontawesome.com/): Iconography for UI elements.

---

## 📁 Project Structure

```plaintext
currency-converter/
│
├── index.html        # Main HTML structure and UI layout
├── style.css         # Styling for cards, inputs, dropdowns, and button
├── app.js            # Core logic: API fetch, currency conversion, and event listeners
├── codes.js          # Currency-to-country code mapping dictionary for flag icons
└── README.md         # Project documentation
```

---

## 💻 Getting Started Locally

No complex build tools or installations are required! Follow these steps to run the project locally on your machine:

### 1. Clone the Repository
```bash
git clone https://github.com/your-username/currency-converter.git
```

### 2. Navigate to Project Directory
```bash
cd currency-converter
```

### 3. Run the Project
- **Option 1**: Simply double-click `index.html` to open it in your default web browser.
- **Option 2 (Recommended)**: Use the **Live Server** extension in VS Code:
  1. Open the project folder in VS Code.
  2. Right-click `index.html` and select **"Open with Live Server"**.

---

## 🔮 Future Improvements

- [ ] Swap button functionality to reverse "From" and "To" currencies with a single click.
- [ ] Historical rate charts and currency trends.
- [ ] Dark / Light theme toggle.
- [ ] Offline caching of previous rates with LocalStorage.

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

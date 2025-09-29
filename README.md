
💱 Currency Converter Webpage

A simple, responsive web application for converting currencies in real time using the Fawaz Ahmed Currency API.

🚀 Features

Convert between multiple currencies instantly using live exchange rates.

Clean and user-friendly interface.

Responsive design for both desktop and mobile devices.

Lightweight frontend (HTML, CSS, JavaScript).


📂 Project Structure

Currency Converter/
├── index.html       # Main HTML file  
├── style.css        # Styling (CSS)  
├── script.js        # Core conversion logic (fetching API / handling input)  
└── codes.js         # Currency codes and country list data

🛠 Technologies Used

HTML5 for structure

CSS3 for styling

JavaScript (ES6) for functionality

Fawaz Ahmed Currency API for live exchange rates


📝 How to Run Locally

1. Clone this repository:

git clone https://github.com/<your-username>/currency-converter.git


2. Navigate into the project folder:

cd currency-converter/Currency\ Converter


3. Open index.html in your browser.



No build tools or server required — it’s a pure frontend app.

🌐 How It Works

On page load, the app fetches the latest exchange rates from:

https://cdn.jsdelivr.net/npm/@fawazahmed0/currency-api@latest/v1/currencies/

It populates dropdowns with currency codes and updates flags dynamically from codes.js.

Clicking the Convert button calculates the converted amount using the live rates.


🌐 Deployment

You can host this on GitHub Pages, Netlify, or any static hosting platform:

For GitHub Pages, push the repo and enable Pages in settings.


🤝 Contributing

Feel free to fork the repository, create a branch, make changes, and submit a pull request.

📜 License

This project is open source under the MIT License.


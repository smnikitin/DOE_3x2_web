# DOE Visualizer – 3 Factor Full Factorial Tool

A lightweight, browser-based visualization tool for **Design of Experiments (DOE)** with **3 factors** at **2 levels** each (full factorial 2³ design). It allows users to:

- Input response values (Y) for each experimental run
- Calculate and visualize main effects and interactions using a Pareto chart
- View the estimated regression equation
- Predict Y for any combination of X1, X2, X3
- Predict X1, X2, X3 that achieve a target Y value

## 🚀 Live Demo

> Just open the `https://smnikitin.github.io/DOE_3x2_web/` file in your browser. No setup needed.

## 📊 Features

- 🧪 **3-Factor Full Factorial Design**: Automatically generates all 8 combinations of factor levels.
- 📈 **Pareto Chart**: Displays relative influence of main and interaction effects.
- ✍️ **Equation Estimation**: Calculates linear regression model using matrix algebra (with [math.js](https://mathjs.org/)).
- 🔮 **Predictive Tools**:
  - **Predict Y** from any combination of X1, X2, X3
  - **Reverse predict factors** that produce a given Y

## 🛠️ Technologies Used

- **HTML, CSS, JavaScript**
- [Chart.js](https://www.chartjs.org/) – For Pareto visualization
- [math.js](https://mathjs.org/) – For matrix operations
- [Plotly.js (included, not used)](https://plotly.com/javascript/) – May be removed if unnecessary

## 📷 Screenshot

![Screenshot of the app interface showing table, chart, and prediction tools](screenshot.png)

## ✏️ How to Use

1. Open `index.html` in your browser.
2. Edit Y values in the table (default is 1–8).
3. Click **"Calculate"** to update:
   - Regression equation
   - Pareto chart
4. Use the **prediction tools** on the right:
   - Predict the Y output for chosen X1, X2, X3
   - Enter a target Y to find the closest matching X1, X2, X3

## 📁 File Structure

├── index.html # Main self-contained HTML file
├── README.md # You're here
└── screenshot.png # (optional) UI preview image


## ✅ To Do / Improvements

- [ ] Add support for center points or fractional factorials
- [ ] Export to CSV or PNG
- [ ] Add response surface plots
- [ ] Option to rename or describe factors

## 📄 License

MIT License. Free to use, modify, and distribute.



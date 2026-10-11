# 📉 DeskGap Risk Analytics

> **Forex Desk Weekend Options Hedging & Gap Stress Model**  
> *Indicative scenario analysis model for institutional desks, proprietary trading firms, and market makers.*

[![Live Tool](https://img.shields.io/badge/Access-Live%20Tool-004A99?style=flat-square&logo=google-chrome)](https://hafzan.pages.dev/)  
[![Single-File Architecture](https://img.shields.io/badge/Architecture-Single%20File%20HTML%2FJS-green?style=flat-square)](https://developer.mozilla.org/en-US/docs/Web/Guide/HTML/HTML5)  
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=flat-square)](LICENSE)

---

![gap-risk-light](https://raw.githubusercontent.com/amaanullah21/gap-risk/refs/heads/main/gap-risk-light.png)

---

![gap-risk-dark](https://raw.githubusercontent.com/amaanullah21/gap-risk/refs/heads/main/gap-risk-dark.png)


## 🚀 Overview

**DeskGap Risk Analytics** is an advanced, high-performance web application designed to model and visualize the weekend gap risk faced by Forex and commodity trading desks holding unhedged spot positions over the weekend. 

Because market liquidity dries up and geopolitical headlines or macroeconomic releases can cause severe weekend gaps upon Monday's open, trading desks often utilize vanilla options (Puts/Calls) to protect their portfolios. This tool combines a **Black–Scholes pricing engine**, **Greeks calculator**, **dynamic payoff charting**, and a **multi-scenario stress matrix** into a zero-dependency, single-interface web utility.

🔗 **[Launch DeskGap Risk Analytics Live](https://amaanullah21.github.io/gap-risk/)**

---

## ✨ Key Features

- **Black–Scholes Valuation Engine**: Client-side mathematical pricing model calculating theoretical option values, Delta ($\Delta$), Gamma ($\Gamma$), Vega ($\nu$), and Theta ($\Theta$).
- **Live Asset Presets**: Quick-load configurations for major assets including **Gold (XAU/USD)**, **EUR/USD**, **GBP/USD**, **USD/JPY**, and **Bitcoin (BTC/USD)**.
- **Hedge Sizing & Execution Ticket**: Determines required option contract quantities, delta hedge coverage percentages, total premium outlays, and residual net portfolio deltas.
- **Weekend Gap Stress Testing**: Interactive target price sliders and percentage shift controls to model overnight/weekend gap-ups and gap-downs.
- **Volatility Crush / Expansion Modeling**: Adjust IV shifts instantly to visualize how volatility spikes or crunches impact option hedge performance.
- **Multi-Scenario Sensitivity Matrix**: Automated stress table mapping P&L outcomes across various gap shifts (-5% to +5%) alongside IV expansion scenarios (+20% IV).
- **Responsive & Themeable UI**: Includes a fully responsive layout with built-in **Light / Dark Mode** toggles.

---

## 🛠️ Technology Stack

- **HTML5 / CSS3**: Modern layout using CSS Grid, CSS Variables (`:root`), and native system font stacks.
- **Vanilla JavaScript (ES6+)**: Pure, lightweight implementation with custom Black–Scholes implementation (utilizing cumulative normal distribution approximations).
- **Chart.js**: Integrated via CDN for real-time interactive payoff curves and portfolio P&L visualization.

---

## ⚠️ Disclaimer

*This application is provided for **indicative scenario analysis, educational, and risk-modeling purposes only**. It is not connected to live broker execution APIs, real-time option-chain quotes, or financial clearinghouses. Options trading involves substantial risk; always verify live market quotes, counterparty credit risk, and exact contract specifications before executing any hedging strategy.*

---

## 👤 Author

**Amaanullah Bhatti**  
- Portfolio / Live Tool: [hafzan.pages.dev](https://hafzan.pages.dev/)  

---

## 📄 License

This project is open-source and available under the [MIT License](LICENSE).

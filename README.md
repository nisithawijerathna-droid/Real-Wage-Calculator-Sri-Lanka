# Real Wage Calculator — Sri Lanka

A clean, interactive web-based tool designed to help users in Sri Lanka visualize the impact of inflation on their purchasing power. This calculator compares salaries against the Colombo Consumer Price Index (CCPI) to determine "real" income value from 2018 through early 2026.

## 🚀 Features

*   **Purchasing Power Analysis**: Calculate the real value of your current salary in terms of a previous base year.
*   **Inflation Gap Visualization**: Instantly see if your income is "Ahead" or "Behind" inflation with dynamic color-coded cards and bar charts.
*   **Historical Back-Splicing**: Includes logic to bridge the CCPI (2013=100) and (2021=100) series for accurate comparisons across the 2022 economic shift.
*   **Modern UI**: High-contrast dark mode interface built with a focus on typography and mobile responsiveness.
*   **Up-to-Date Data**: Pre-loaded with official CCPI data through February 2026.

## 📊 Methodology

The tool uses official data published by the **Department of Census & Statistics, Sri Lanka**.

1.  **Current Data**: Uses the CCPI (Base 2021 = 100) series.
2.  **Historical Data**: For dates prior to January 2022, the tool uses the CCPI (Base 2013 = 100) series, back-extended and spliced at the January 2022 overlap to maintain a consistent ratio.
3.  **Real Wage Formula**: 
    *   `Real Value = (Current Salary / Current Index) * Base Index`
    *   `Required Salary = (Base Salary / Base Index) * Current Index`

## 🛠️ Technical Stack

*   **Language**: Vanilla JavaScript (ES6+)
*   **Styling**: CSS3 (Modern Grid, Flexbox, and CSS Variables)
*   **Structure**: Semantic HTML5
*   **Fonts**: DM Sans & DM Serif Display (via Google Fonts)

## 💻 Installation & Usage

Since this is a client-side tool, no installation is required. 

1.  Clone the repository:
    ```bash
    git clone [https://github.com/your-username/real-wage-calculator-sl.git](https://github.com/your-username/real-wage-calculator-sl.git)
    ```
2.  Open `index.html` in any modern web browser.
3.  Enter your starting salary/date and your current salary/date to see the results.

---

**Created by [Nisitha Wijerathna](mailto:nisithawijerathna@gmail.com)**

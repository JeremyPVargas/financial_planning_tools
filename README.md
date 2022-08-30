# Financial Planning Tools
This tool runs on a Jupyter notebook and it has 2 sections designed for financial analysis and planning.
Section # 1: Emergency Fund Planning
Section # 2: Retirement Planning

<!-- TABLE OF CONTENTS -->
<details open="open">
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#purpose">Purpose</a>
      <ul>
        <li><a href="#inputs">Inputs</a></li>
        <li><a href="#outputs">Outputs</a></li>
      </ul>
    </li>
    <li>
      <a href="#technologies">Technologies</a>
      <ul>
        <li><a href="#json">Json</a></li>
        <li><a href="#alpaca">Alpaca</a></li>
        <li><a href="#requests">Requests</a></li>
        <li><a href="#os">os</a></li>
        <li><a href="#mcforecasttools">MCForecastTools</a></li>
        <li><a href="#pandas">Pandas</a></li>
        <li><a href="#matplotlib">Matplotlib</a></li>
      </ul>
    </li>
    <li><a href="#version-release">Version Release</a></li>
    <li><a href="#how_to_run">How to run</a></li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#contributors">Contributors</a></li>
    <li><a href="#license">License</a></li>
        <ul>
        <li><a href="#permissions">Permissions</a></li>
        <li><a href="#disclaimer">Disclaimer</a></li>
        </ul>
    </li>
    <li><a href="#aknowledgements">Aknowledgements</a></li>
</details>

<!--Purpose -->
## Purpose
This tool runs on a Jupyter notebook and it has 2 sections designed to assist in the financial analysis and planning of a credit union client.

Section # 1: Emergency Fund Planning

    The client will be able to visualize their current savings. The tool will determine if the user will have enough reserves for an emergency fund.

Section # 2: Retirement Planning

    The tool forecasts the performance of client's retirement portfolio in 30 years. The tool makes an Alpaca API call via the Alpaca SDK to get historical price data. Then data is used to run Monte Carlo simulations that will help determine the fund's value based on these simulations.


### Inputs and APIs
The application reads financial performance data from one file. Data is used to conduct futher analysis of the funds in comparision to the S&P 500, which is also included in the original Data Frame.

    MC ForecastTools.py

    Alpaca API

  
### Outputs
    Visualizations:
    - Portfolio assets
    - Portfolio performance over x trading days based on Monte Carlo Simulations.
    - Distribution of portfolio's Final Cumulative Returns accross simulations.
    Statistical analysis methods: 
    - 95% Confidence interval including upper and lower confidience intervals.
    
---
<!--Technologies -->
## Technologies
### Python:

    Phyton Version: **3.7.13**

## Libraries and Dependencies
### Json
[Json](https://matplotlib.org/stable/api/_as_gen/matplotlib.pyplot.plot.html)

### Alpaca
[Alpaca](https://alpaca.markets/docs/api-references/market-data-api/)

### Requests
[Requests](https://realpython.com/python-requests/)

### os
[os](https://docs.python.org/3/library/os.html)

### MCForecastTools
[MCForecastTools](https://pbpython.com/monte-carlo.html)

### Pandas
[Pandas](https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.DataFrame.html) 

### Matplotlib
[Matplotlib](https://matplotlib.org/stable/api/_as_gen/matplotlib.pyplot.plot.html)

---
<!--How to run -->
## How to run

1. Clone the repository on a folder that will easy to open
2. File was developed with Jypiter Notebook and Lab
3. Open the file with Jupiter using the Anaconda Navigator
4. Navigate open the folder where the files were cloned to
5. Open the file on JupyterLab


![jupyterlab](./images/anaconda_nav.png)



---
<!--Version Release -->
## Version Release

### Version 1.0


---
<!--Usage -->
## Usage

### Portfolio performance data - sample:

![portfolio](./images/portfolio.png)



### Visualization of Monte Carlo histogram -sample:

![montecarlo1](./images/5-4-monte-carlo-histogram.png)



### Visualization of Monte Carlo simulation over x trading days- sample:

![montecarlo2](./images/5-4-monte-carlo-line-plot.png)


---
<!--Contributors -->
## Contributors

Jeremy Vargas

    Managing Director
    Resonant Solutions LLC
    email:    jeremyvargas@resonantsolutions.org
    linkedin: https://www.linkedin.com/in/jeremyvargas/

UW FinTech Bootcamp
- Startup code provided by institution

---
<!--License -->
## License
Portfolio Risk Analysis tool is available under an MIT License.

Copyright (c) 2022 - Resonant Solutions, LLC

### Permissions
Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the “Software”), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.
### Disclaimer
The Software is provided “as is”, without warranty of any kind, express or implied, including but not limited to the warranties of merchantability, fitness for a particular purpose and noninfringement. In no event shall the authors or copyright holders be liable for any claim, damages or other liability, whether in an action of contract, tort or otherwise, arising from, out of or in connection with the software or the use or other dealings in the Software.

---
<!--Aknowledgements -->
## Aknowledgements
* [Markdown Guide](https://www.markdownguide.org/basic-syntax/#reference-style-links)


<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->

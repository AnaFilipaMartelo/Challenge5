# Credit Union Financial Health Analysis Tools

This project provides a set of financial analysis tools designed to help credit union members evaluate their financial health and plan for the future. The tools include a financial planner for emergencies, allowing members to assess their monthly budgets and determine if they have enough reserves for an emergency fund. Additionally, there is a financial planner for retirement that forecasts the performance of members' retirement portfolios using historical price data and Monte Carlo simulations. The prototype application showcases these tools and empowers members to make informed financial decisions

---

## Technologies

The technologies used in this project include:

   * Python 3.7
   * JupyterLab 3.5.3
   * Pandas 1.5.3
   * Requests
   * JSON
   * Alpaca Trade API
   * MCForecastTools
   

---

## Installation Guide

Open your terminal and install JupyterLab as shown below:

```python
  python -m ipykernel install --user --name
```

Install Requests and JSON

```python
  conda install -c anaconda requests
  conda install -c jmcmurray json
```

Install the python-dotenv library as follows:

```python
  pip install python-dotenv
```

Install the Alpaca SDK:

```python
  pip install alpaca-trade-api
```

---

## Usage

Clone the repository and Launch Jupyter Notebook by executing the following command in your terminal:

 ![Launch Jupyter](Images/Screenshot1.png) 

In the Jupyter Notebook interface, navigate to the project directory and open the finnancial_planning_tools.ipynb file. Add your Alpaca API key and Alpaca secret key to the SAMPLE.env file. 

Insert the name of the .env file in the line 9 of the second block of code 

```python
load_dotenv(".env")
```

This is a prototype application, to use it with your personal information first provide the required financial information, such as your income, expenses, and current savings. 

Run each cell in the notebook sequentially to calculate the current value, in US dolars, of each cryptocurrency and entire cryptocurrency wallet. And also, to calculate the value, in US dollars, of the current amount of shares in each of the stock and bond portions of the members' portfolio.

The second part of the application prototype will create a Monte Carlo simulation for the next 30 years and calculate the lower and upper bounds for the expected value of the portfolio (with weights 40% bonds and 60% stocks) with a 95% confidence interval.

Lastly, it will will create a Monte Carlo simulation for the next 10 years and calculate the lower and upper bounds for the expected value of the portfolio (with weights adjusted to 20% bonds and 80% stocks) with a 95% confidence interval.

Read the comments and text documentation within the notebook to understand the analysis and findings.

---


## Contributors

* Ana Martelo (anafilipamartelo@gmail.com)

---

## License

MIT
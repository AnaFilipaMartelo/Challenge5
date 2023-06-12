# CFinancial Planner for Emergencies

The Financial Planner for Emergencies is a powerful tool designed to help you effectively manage your finances and plan for unforeseen circumstances. This application serves as your personal financial assistant, allowing you to visualize and evaluate your current savings to determine if you have sufficient reserves for an emergency fund. 

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

In the Jupyter Notebook interface, navigate to the project directory and open the finnancial_planning_tools.ipynb file.

This is a prototype application, to use it with your personal information first provide the required financial information, such as your income, expenses, and current savings. 

Run each cell in the notebook sequentially to calculate the current value, in US dolars, of each cryptocurrency and entire cryptocurrency wallet. And also, to calculate the value, in US dollars, of the current amount of shares in each of the stock and bond portions of the portfolio.

Read the comments and text documentation within the notebook to understand the analysis and findings.

---


## Contributors

* Ana Martelo (anafilipamartelo@gmail.com)

---

## License

MIT
# Sales Dashboard with Python and Streamlit

This is one of the projects I developed during my Data Science studies at Alura. The goal was to put what I had been learning about Python, data analysis, and visualization into practice by building a dashboard that can be accessed directly through a web browser.

## Access the Project

- **Dashboard:** [View the live application](https://nixondeam-dashboard-vendas-alura.streamlit.app/Dados_brutos)
- **Source Code:** [GitHub Repository](https://github.com/nixondeam0205/dashboard_vendas)

## About the Project

The dashboard uses sales data to present information visually and allows users to explore results through interactive filters.

During development, I worked on retrieving data from an API, manipulating data with Pandas, and creating interactive charts. I also built a separate page to explore the raw data and choose which columns to display.

## What You Can Explore

- Total revenue and number of sales.
- Revenue by state and product category.
- Geographical distribution of sales.
- Monthly revenue and sales trends.
- Sales performance comparisons by salesperson and state.
- Raw sales data with filters for product, category, price, shipping cost, purchase date, salesperson, location, customer rating, payment method, and number of installments.

## Technologies Used

- **Python:** Application development.
- **Pandas:** Data manipulation, grouping, and analysis.
- **Requests:** Retrieving data from the API.
- **Plotly Express:** Creating interactive charts.
- **Streamlit:** Building and deploying the dashboard.

## How to Run the Project Locally

You will need Python and Git installed, as well as an internet connection to access the API.

### 1. Clone the repository

```bash
git clone https://github.com/nixondeam0205/dashboard_vendas.git
cd dashboard_vendas
```

### 2. Create a virtual environment

```bash
python -m venv venv
```

### 3. Activate the virtual environment

On Windows, using PowerShell:

```powershell
.\venv\Scripts\Activate.ps1
```

### 4. Install the dependencies

```bash
pip install -r requirements.txt
```

### 5. Run the dashboard

```bash
streamlit run Dashboard.py
```

The application will open in your browser. If it does not open automatically, follow the local URL displayed in the terminal.

## Data Source

The data is retrieved from the API available at [labdados.com/produtos](https://labdados.com/produtos).

Since the application relies on an external service, its functionality depends on the API being available.

## What I Learned

This project helped me better understand how different tools can work together in a data analysis application.

I gained practical experience with API requests, data manipulation using Pandas, interactive charts and filters, and deploying a web application. I also had to troubleshoot issues during development, which became an important part of the learning process.

I plan to keep improving my skills in Python and data analysis as I continue learning and working on new projects.

## About Me

I have a bachelor's degree in Law and am transitioning into the technology field, with a focus on Data Science and Data Analytics. I have been studying Python, Pandas, and data visualization while developing practical projects to strengthen my skills.

- **GitHub:** [nixondeam0205](https://github.com/nixondeam0205)
- **LinkedIn:** [Nixon Deam Cavalcanti](https://www.linkedin.com/in/nixon-deam-cavalcanti/)

---

*Educational project developed as part of my Data Science studies at Alura.*

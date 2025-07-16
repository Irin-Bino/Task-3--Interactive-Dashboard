# Task-3--Interactive-Dashboard
# Interactive Dashboard using Dash in Google Colab (No File Upload Needed)

This project demonstrates how to create a fully interactive data visualization dashboard using [Plotly Dash](https://dash.plotly.com/) — all within **Google Colab**.

The dashboard uses a CSV dataset that is loaded automatically from a public URL, so **no file uploads or local installations are needed**.

---

## Features

- Interactive dashboard built with Dash
- Runs entirely in Google Colab (browser-based)
- Uses publicly hosted dataset (no file upload required)
- Data visualized with Plotly (responsive and zoomable)
- Easy to customize with your own dataset or chart type

---

## Files in This Repository

| File | Description |
|------|-------------|
| `dashboard.ipynb` | Google Colab notebook that builds and runs the dashboard |
| `README.md`       | Project description and instructions |

---

## Dataset

The dashboard uses the [Gapminder dataset](https://github.com/plotly/datasets/blob/master/gapminderDataFiveYear.csv), which includes country-level development indicators (GDP, life expectancy, population, etc.) from 1952–2007.

Dataset is fetched directly from this URL:
https://raw.githubusercontent.com/plotly/datasets/master/gapminderDataFiveYear.csv

yaml
Copy
Edit

---
##  How to Run

1. Open the notebook in Google Colab:  
   [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](dashboard.ipynb)

2. Click **“Run All”** to install dependencies and launch the dashboard.

3. The interactive Plotly dashboard will appear **inline** in the notebook.

---

## Example Visualization

The dashboard displays a bubble chart of GDP per capita vs life expectancy in 2007:

- X-axis: GDP per capita (log scale)
- Y-axis: Life expectancy
- Bubble size: Population
- Bubble color: Continent
- Tooltip: Country

---

##  Tech Stack

- [Python 3](https://www.python.org/)
- [Google Colab](https://colab.research.google.com/)
- [Dash](https://dash.plotly.com/)
- [Plotly Express](https://plotly.com/python/plotly-express/)
- [Pandas](https://pandas.pydata.org/)

---

## License

This project is licensed under the [MIT License](LICENSE).

---


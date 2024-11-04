# IDS 706 Mini Project 9 - Cloud-Hosted Notebook Data Manipulation

### 🏗️ Requirements
- Set up a cloud-hosted Jupyter Notebook (e.g., Google Colab)
- Perform data manipulation tasks on a sample dataset

### 📂 Project Structure

```
.
├── Makefile
├── README.md
├── main.ipynb
├── main.py
├── mylib
│   ├── make_functions.py
│   └── test_lib.py
├── requirements.txt
├── sustainable_fashion_trends_2024.csv
└── test_main.py
```

### 📊 Dataset Description
The dataset used for this project is Sustainable Fashion: Eco-Friendly Trends from Kaggle. It provides information on sustainable fashion trends with various metrics related to the industry. For more details and to download the dataset, visit this [link](https://www.kaggle.com/datasets/waqi786/sustainable-fashion-eco-friendly-trends).

The dataset has the following features:
- Brand_ID
- Brand Name
- Country - country of origin
- Year - year the brand was created
- Sustainability_Rating - the rating of the brand - from A to D
- Material_type - the type of materials used
- Eco_Friendly_Materials - whether the materials were eco-friendly or not
- Carbon_Footprint_MT - the carbon footprint generated in metric tonnes
- Water_Usage_Liters - the amount of water used in liters
- Waste_Production_KG - the amount of waste produced in kilograms
- Recycling_Programs - whether the brand had any recycling programs or not
- Product_lines - number of product lines the brand had
- Average_Price_USD - the average price of a product by the brand, in US Dollars
- Market_Trend - checking the place of these brands as per the market
- Certifications - any certifications the brand had

### 📋 Summary Statistics 

Describe:
|    | Statistic          |   Value |
|---:|:-------------------|--------:|
|  0 | Mean               | 250.318 |
|  1 | Median             | 250.65  |
|  2 | Standard Deviation | 142.802 |


### 🔍 Visualizations
The script generates two visualizations:

1. Bar Chart - Displays the number of sustainable fashion brands by the countries.
![sustainablebrand_viz1](bar_plot.png)

2. Pie Chart - Shows the propotion of brands based on the materials they use.
![sustainablebrand_viz2](pie_chart.png)

The statistics and the visualizations for the Sustainability brands data can be viewed through the following link:
[Click here to view details](sustainable_fashion.md)
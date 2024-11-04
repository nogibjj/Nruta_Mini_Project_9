[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https:colab.research.google.com/github/nogibjj/Nruta_Mini_Project_9/blob/main/main.ipynb)
[![Format](https://github.com/nogibjj/Nruta_Mini_Project_9/actions/workflows/cicd.yml/badge.svg)](https://github.com/nogibjj/Nruta_Mini_Project_9/actions/workflows/cicd.yml)

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

### 🛠️ Setup Instructions
#### Step 1: Open Google Colab
1. Go to Google Colab.
2. Sign in with your Google account if you haven’t already.

#### Step 2: Clone the Repository
To access this project’s files in Colab, clone the repository from GitHub.
1. Start a new notebook in Google Colab.
2. Run the following cell to clone the repository:
```
git clone https://github.com/nogibjj/Nruta_Mini_Project_9
```

#### Step 3: Install Dependencies
If your project has a requirements.txt file, you can install the dependencies by running:
```
!pip install -r requirements.txt
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

### 
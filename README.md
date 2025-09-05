# 🏡 Airbnb Data Analysis – Python Project  

## 🔎 Overview  
This project analyzes **Airbnb listings data** using **Python (Pandas, Matplotlib, Seaborn, etc.)** to uncover insights into pricing, availability, and customer behavior.  
The goal is to understand **market dynamics** and identify trends that can help hosts, guests, and stakeholders make data-driven decisions.  

---

## 🗂 Dataset  
The dataset contains detailed Airbnb listing information, including:  
- Listing ID & Name  
- Host details 👤  
- Neighborhood / Location 📍  
- Room type 🏠  
- Price 💰  
- Minimum nights 💤  
- Number of reviews ⭐  
- Availability (per year) 📅  

---

## 🔧 Data Cleaning  
Steps performed before analysis:  
- ✅ Removed duplicate entries  
- ✅ Handled missing values  
- ✅ Converted data types (e.g., dates, numbers)  
- ✅ Filtered outliers (unrealistic prices & nights)  
- ✅ Standardized categorical fields for grouping  

---

## 📈 Analysis & Visualizations  

### 1️⃣ Exploratory Data Analysis (EDA)  
- Distribution of prices & availability  
- Correlation between neighborhood and price  

### 2️⃣ Geographical Insights  
- Neighborhood-wise listing distribution  
- Hotspot areas with highest demand  

### 3️⃣ Host & Customer Behavior  
- Top hosts by number of listings  
- Review activity trends  

### 4️⃣ Room Type Analysis  
- Popular room types (Entire home, Private, Shared)  
- Price comparison by room type  

### 5️⃣ Trends Over Time  
- Seasonal availability  
- Review growth across years  

---

## 🔍 Key Insights  
✨ Entire homes/apartments generate the highest average revenue  
✨ Some neighborhoods dominate in both demand and pricing  
✨ Unrealistic minimum-night values needed filtering  
✨ Reviews highlight trust & host reliability as key factors  
✨ Seasonal patterns strongly impact availability & pricing  

---

## 🚀 How to Run  

1. Clone this repository:  
   ```bash
   git clone https://github.com/yourusername/airbnb-python-project.git
   cd airbnb-python-project
2.Install reqiurements
  pip install -r requirements.txt
  
3.Open Jupyter Notebook
  jupyter notebook airbnb-python-project.ipynb

4. Open `airbnb-paris-analysis.ipynb` and run the cells step by step.

---

## 📊 Results

Here are some key visualizations from the analysis:

* **Growth of Airbnb Listings in Paris**
  ![Listings Growth](images/listings_growth.png)

* **Average Price by Locality**
  ![Price by Locality](images/price_locality.png)

* **Impact of 2017 Regulation on Host Entries**
  ![Regulation Impact](images/regulation_impact.png)

---

## 📜 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## 🙌 Acknowledgments

* [Inside Airbnb](http://insideairbnb.com/) for providing the dataset.
* Paris regulatory context from local housing policies.

---

## 🚀 Future Work

* Extend the analysis to other European cities for comparison.
* Add predictive modeling to forecast Airbnb prices.
* Build an interactive dashboard with Plotly or Power BI.

---

✅ **Final Note:**
This project highlights the intersection of **data, policy, and business strategy** in the short-term rental market.
Paris remains a dynamic case study of how regulations reshape supply, demand, and pricing in urban tourism.

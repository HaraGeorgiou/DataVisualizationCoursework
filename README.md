# **Quality of Life Data Visualization **

## **Overview**
This project presents an interactive data visualization of **Quality of Life Metrics** based on the **OECD Better Life Index** dataset. The visualizations aim to provide insights into factors affecting life quality, such as **income, education, health, and environment**.

## **Features**
- Interactive web-based visualizations (**combined_visualization.html**)  
- Data processing and cleaning using Python  
- Jupyter Notebook with detailed visualization steps  
- Uses **OECD Better Life Index** dataset for analysis  

## **Tech Stack**
- **Programming Language:** Python  
- **Visualization Libraries:** Matplotlib, Seaborn, Plotly  
- **Data Handling:** Pandas, NumPy  
- **Frontend:** HTML (for rendering visualizations)  

## **Installation Guide**
### **1. Clone the Repository**
```bash
git clone https://github.com/yourusername/c1013770_DataVisualization.git
cd c1013770_DataVisualization
```

### **2. Set Up a Virtual Environment**
```bash
python -m venv env
source env/bin/activate   # Mac/Linux
env\Scripts\activate      # Windows
```

### **3. Install Dependencies**
```bash
pip install -r requirements.txt
```

### **4. Open the Jupyter Notebook**
```bash
jupyter notebook DataVisualizationCode.ipynb
```

## **Project Structure**
```
 c1013770_DataVisualization
│──  data
│   │── OECD_betterLifeIndex.xlsx  # Dataset used for visualization
│── DataVisualizationCode.ipynb   # Jupyter Notebook with visualization code
│── combined_visualization.html   # Output visualization in web format
│── CSC3833_Coursework_QualityOfLife_Part1_TechnicalReportTemplate-1.pdf  # Report
│── README.md                     # Project documentation (this file)
```

## **Usage**
1. Open `DataVisualizationCode.ipynb` in **Jupyter Notebook**.
2. Run the cells to **load, process, and visualize** the data.
3. The **interactive visualizations** are saved as `combined_visualization.html`, which can be opened in a web browser.

## **Future Enhancements**
-  Add more interactive filtering options for users  
-  Expand dataset to include more global metrics  
-  Deploy visualizations on a web-based platform  

## **License**
This project is licensed under the **MIT License**.

## **Author**
**Hara Georgiou**  

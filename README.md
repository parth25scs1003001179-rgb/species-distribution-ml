#  Species Distribution Probability Mapping using Machine Learning

##  Project Overview
This project predicts **species distribution probability maps** using machine learning techniques. It analyzes environmental factors such as temperature, rainfall, altitude, and vegetation to determine the likelihood of species presence across different regions.

The system helps in **biodiversity conservation, ecological planning, and environmental analysis**.

---

##  Objectives
- Build a machine learning model for species prediction  
- Analyze environmental variables affecting species habitats  
- Generate probability maps for species distribution  
- Support data-driven conservation decisions  
- Create a scalable and automated system  

---

##  Technologies Used
- Python  
- Pandas  
- NumPy  
- Scikit-learn  
- Matplotlib  
- Joblib  

---

##  Dataset
The dataset used contains the following features:

- Temperature  
- Rainfall  
- Altitude  
- Vegetation Index  
- Species Presence (0 or 1)  

 File used: `species_data.csv`

---

##  Project Workflow

1. **Data Loading**
   - Load dataset from CSV file  

2. **Data Preprocessing**
   - Select relevant features  
   - Split data into input (X) and output (y)  

3. **Model Training**
   - Algorithm: Random Forest Classifier  
   - Train-test split: 80/20  

4. **Model Evaluation**
   - Accuracy Score  
   - AUC Score  

5. **Visualization**
   - Generate probability map using scatter plot  

---

##  How to Run

### 1. Clone the Repository
```bash
git clone https://github.com/your-username/species-distribution-ml.git
cd species-distribution-ml

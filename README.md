
# **Medical Cost Analysis Project**

## **Overview**
This project explores factors influencing medical insurance costs using the **Kaggle Medical Cost Personal Datasets**. It applies **exploratory data analysis (EDA)** and statistical methods to identify key variables affecting medical expenses. The project is structured into multiple sections, including function-based and class-based implementations for better scalability and reusability.

## **Project Goals**
- **Analyze** how demographic and health factors (age, BMI, smoking status, etc.) impact insurance costs.
- **Visualize** relationships between variables using scatter plots, box plots, and correlation matrices.
- **Build reusable functions** for various analyses.
- **Encapsulate** analysis into a class-based implementation for better organization and extensibility.

## **Dataset**
- **Source:** Kaggle - Medical Cost Personal Datasets
- **Features:**
  - `age`: Age of the insured person
  - `sex`: Gender of the insured person
  - `bmi`: Body Mass Index
  - `children`: Number of dependents
  - `smoker`: Smoking status
  - `region`: Residential region
  - `charges`: Medical insurance cost

## **Project Structure**
### **1️⃣ Scoping the Data & EDA**
- Load and explore the dataset.
- Identify missing values and check data distributions.
- Visualize key relationships.

### **2️⃣ Function-Based Analysis**
- Implement functions for:
  - Analyzing **age vs. charges**
  - Analyzing **BMI vs. charges**
  - Comparing **smokers vs. non-smokers**
  - Correlation matrix visualization

### **3️⃣ Class-Based Implementation**
- Develop a `MedicalCostAnalysis` class with methods for:
  - Dataset exploration
  - Data visualization
  - Statistical analysis
  - Future extensions (e.g., machine learning models)

3. **Run the analysis in Google Colab or locally:**
   ```python
   from medical_cost_analysis import MedicalCostAnalysis
   analyzer = MedicalCostAnalysis("insurance.csv")
   analyzer.explore()
   analyzer.visualize_distributions()
   analyzer.analyze_age()
   ```

## **Future Enhancements**
- Implement **predictive modeling** using machine learning.
- Add **automated reporting** for medical cost trends.
- Expand the analysis to additional healthcare datasets.

## **Author**
- **Your Name**
- **LinkedIn**: [Your LinkedIn](https://www.linkedin.com/in/candace215/)
- **GitHub**: [Your GitHub](https://github.com/aicoaching2025/)

## **License**
This project is licensed under the **MIT License**.

---

Let me know if you'd like me to refine or customize anything further! 🚀

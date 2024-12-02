# 🌊 Predicting Dissolved Oxygen (DO) Levels in Polluted River Water 💧

![16382538_304](https://github.com/user-attachments/assets/8727d451-d98b-4e43-b515-95b64c989b98)


## 1. Project Overview

### **Why This Project Matters**

Rivers are vital for both ecosystems and human communities. However, pollution has significantly degraded water quality in many rivers, making it crucial to monitor and predict key water quality parameters. One of the most critical indicators of water quality is **Dissolved Oxygen (DO)** levels. In this project, I was hired as a **Data Science Consultant** to analyze contaminated river water parameters, with the main goal of predicting the **DO level** based on various physico-chemical features.

### **What I Did**

🔹 **Data Loading**      
I sourced and loaded a comprehensive dataset containing key water sample parameters from a heavily polluted river.

🔹 **Preprocessing**       
The raw data was cleaned and prepared to ensure it was ready for machine learning models. This step involved handling missing values, normalizing features, and more.

🔹 **Model Training**        
I developed and trained several machine learning models to predict DO levels using the available physico-chemical features.

🔹 **Model Evaluation**        
I assessed the performance of each model, ensuring the predictions of DO levels were accurate and reliable.

By automating DO level predictions, this project aims to enhance **environmental monitoring** and improve the management of polluted water bodies for better **water quality**.

---

## 2. Dataset

The dataset contains water sample data collected from a heavily polluted river. It includes various physico-chemical parameters measured at the time of sampling.

### **Dataset Columns**    

| **Column**     | **Description**                                                                 |
|----------------|---------------------------------------------------------------------------------|
| `sample_id`    | Unique identifier for each water sample.                                        |
| `temperature`  | Temperature of the water sample (°C).                                           |
| `pH`           | pH level of the water sample.                                                    |
| `turbidity`    | Turbidity level of the water (NTU).                                             |
| `conductivity` | Electrical conductivity of the water (µS/cm).                                   |
| `nutrients`    | Nutrient levels in the water (mg/L).                                             |
| `DO`           | **Dissolved Oxygen level** in the water (mg/L) - this is our **target variable**. |

---

## 3. Key Packages Used     

This project relies on several key Python packages for data manipulation, modeling, and visualization:    

- **Pandas 2.2.2** & **NumPy 1.26** for data manipulation     
- **Matplotlib 3.8.4** & **Seaborn 0.12.2** for data visualization     
- **Scikit-learn 1.2.2** for building machine learning models     
- **IPython 8.20.0** & **IPython Sql 0.3.9** for interactive work      
- **ML Flow 2.14.1** for model tracking and management       

---

## 4. Setting Up the Environment

To run this project, you will need to set up the necessary environment. The easiest way is using **Anaconda**, a powerful tool for managing Python environments.

### **Steps to Create Your Environment**

1. Open **Anaconda** and go to the **Environments** pane.
2. Click the **+** button at the bottom of the pane to create a new environment.
3. In the **Packages** section, search for and select the following packages:

   - `numpy` version **1.26**
   - `pandas` version **2.2.2**
   - `seaborn` version **0.12.2**
   - `matplotlib` version **3.8.4**
   - `nltk` version **3.8.1**
   - `ipython` version **8.20.0**
   - `ipython-sql` version **0.3.9**
   - `python` version **3.11.8**
   - `pymysql` version **1.0.2**
   - `mlflow` version **2.14.1**

4. After selecting all the necessary packages, click **Apply**.
5. Once the environment is set up, right-click the **Play button** and choose **Open in Jupyter Notebook** to begin using the project.

---

## 5. Running the Project

To run the notebook and start analyzing the data:

1. Ensure all dependencies are installed in your environment.
2. Launch Jupyter Notebook from the Anaconda Navigator or the terminal.
3. Open the notebook files from the project directory.
4. Run each cell sequentially to load, preprocess, and analyze the data.

---

## 6. Contributing

I welcome contributions to this project! If you'd like to contribute:

1. **Fork** the repository.    
2. Create a **new branch** for your changes.     
3. Make your changes and **commit** them.      
4. Submit a **pull request** to have your contributions reviewed.    

---

## 7. License

This project is licensed under the [MIT License](LICENSE).

---

**Thank you for exploring this project!**        
By leveraging data science, we're making strides toward better water quality management and environmental protection. Let's work together to make our rivers cleaner and healthier! 🌍    



# Data Analysis with PySpark and MLlib
Repo for the week 4 assignment with PySpark and MLlib.  
## Notes
- Python version 3.10.0  
- Used PySpark and MLlib for classification model.  
- Used WSL2 Debian distribution on Windows 11.  
- Code was run in a Jupyter Notebook inside VSCode.  
- Dataset comes from Kaggle:  
  - https://www.kaggle.com/datasets/shrutimechlearn/churn-modelling/data  
### Steps
1. **Create Virtual Environment**
   ```
    Python –m venv venv
    Source venv/bin/activate
    Pip install –-upgrade pip
    ```
2. **Installed Jupyter and Pyspark**
   ```
    Pip install jupyter
    Pip install pyspark
    ```
3. **Install findspark**
   ```
    pip install findspark
   ```
4. **Notebook Code**
   ```
   import findspark
   findspark.init()
   import pyspark
   spark = SparkSession.builder \
   .appName("Churn Prediction with PySpark MLlib") \
   .getOrCreate()
    print("Spark Session created successfully.")
   ```

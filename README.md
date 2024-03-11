# Logistic Regression with Mathematical Insights using PySpark ML

This project demonstrates the application of Logistic Regression for classification using PySpark's Machine Learning library (MLlib). It aims to provide insights into the mathematical underpinnings of Logistic Regression and the Gradient Descent optimization algorithm within a distributed computing environment.

## Instructor Information

**Dr Amin Karami (PhD, FHEA, EE)**  
University of East London, Docklands Campus  
E-mail: [amin.karami@ymail.com](mailto:amin.karami@ymail.com)  
YouTube: [AminKarami](https://www.youtube.com/@AminKarami)  
Website: [https://www.aminkarami.com](https://www.aminkarami.com)

---

## Learning Outcomes

- **Master Logistic Regression and Optimization**: Develop an in-depth understanding of Logistic Regression and optimize using Gradient Descent with PySpark ML.
- **Data Handling Expertise**: Learn to preprocess, select features, and manage large datasets within Jupyter Notebook.
- **Accuracy Assessment**: Acquire the ability to evaluate model performance using various metrics to ensure dependable classification.

## Project Structure

The project is structured as a Jupyter Notebook and comprises the following steps:

### Step 1: Initialization
Setting up the PySpark environment and importing the required libraries.

### Step 2: Data Preprocessing
Loading and preprocessing the KDDCup 1999 Data to prepare for the application of Logistic Regression.

### Step 3: Model Training
Applying the Logistic Regression model using PySpark ML and tuning the parameters for optimal performance.

### Step 4: Model Evaluation
Assessing the performance of the model using metrics like confusion matrix, accuracy, precision, recall, and F1 score.

## Dataset

The KDDCup 1999 dataset, containing network intrusion detection data, is utilized to test the Logistic Regression model. The dataset can be found here:

- [Full dataset (18M; 743M Uncompressed)](https://kdd.ics.uci.edu/databases/kddcup99/kddcup.data.gz)
- [10% dataset (2.1M; 75M Uncompressed)](https://kdd.ics.uci.edu/databases/kddcup99/kddcup.data_10_percent.gz)

Further information on the dataset can be found on the [UCI KDD Archive](https://kdd.ics.uci.edu/databases/kddcup99/kddcup99.html).

## Requirements

This project requires a working installation of PySpark and access to a Spark cluster. The recommended setup is as follows:

- Spark 3.x
- Python 3.8 or later
- Jupyter Notebook

The memory and core configurations are set for local execution but can be adjusted for a distributed environment.

## Usage

To run the project, open the Jupyter Notebook in a PySpark-enabled environment and execute the cells sequentially. Ensure the dataset is accessible to the SparkSession.

## Contact

For inquiries or support, please reach out to Dr Amin Karami at the provided contact details.

## License

This project is licensed under the MIT License - see the LICENSE file for details.

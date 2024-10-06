**Data Illustration Project:**
- This project analyzes COVID-19 cases in Los Angeles County using Python. The dataset is processed, cleaned, and visualized to provide insights into COVID-19 trends over time.

**Features:**
- Data Cleaning:
    - Unnecessary columns are removed, and the dataset is limited to relevant data points.
- Data Transformation:
    - Date columns are converted to datetime format, and the data is sorted by date.
- CSV Export:
    - The cleaned and sorted dataset is exported as a new CSV file for further use.
- Visualization:
    - The project supports generating visualizations using matplotlib.

**Files:**
- Data_Illustration.py:
    - Python script that handles data processing, cleaning, and exporting the cleaned dataset.
- LA_County_COVID_Cases.csv:
    - Original dataset used for analysis.

**Dependencies:**
- This project requires the following Python libraries:
  - numpy
  - pandas
  - matplotlib

You can install the necessary dependencies by running the following command in your terminal:

- pip install numpy pandas matplotlib

**Usage:**
- Clone the repository by running the following command in your terminal:
  - git clone https://github.com/your-username/recipe-website.git

- Make sure you have the dataset (LA_County_COVID_Cases.csv) in the same directory as the script.
- Run the Python script:
  - python Data_Illustration.py

- The processed data will be saved as sorted_file.csv, and the cleaned DataFrame will be displayed in the console.

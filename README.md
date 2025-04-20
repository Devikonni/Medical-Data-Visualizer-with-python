# 🏥 Medical-Data-Visualizer-with-python
This project analyzes medical examination data using Python, Pandas, Seaborn, and Matplotlib. It includes cleaning, normalization, categorical plotting, and heatmap generation. Done as part of the freeCodeCamp Data Analysis with Python certification.
 

This Python project visualizes and analyzes medical examination data to explore the relationship between body measurements, blood tests, lifestyle choices, and cardiovascular disease. The project uses **Pandas**, **Matplotlib**, and **Seaborn** to clean, process, and visualize the dataset.

The goal of this project is to process medical examination data and visualize relationships between various health metrics and the presence of cardiovascular disease. You will use different types of visualizations to provide insights into these relationships.

---

## ✅ What I Did

- **Data Preprocessing**:
  - Loaded the dataset from `medical_examination.csv`.
  - Added an "overweight" column based on the BMI calculation (weight/height^2).
  - Normalized categorical columns (`cholesterol`, `gluc`, etc.) to make `0` as "normal" and `1` as "not normal".

- **Data Visualization**:
  - Created categorical plots to compare health metrics between people with and without cardiovascular disease.
  - Generated a heatmap to show correlations between various health-related features, filtering out invalid data.

- **Testing**:
  - Ensured the functionality of each component (data preprocessing, plot generation, etc.) by running unit tests.

---

## 📦 Tech Stack

- **Python 3**
- **Pandas** for data manipulation
- **Matplotlib** for static data visualization
- **Seaborn** for advanced statistical visualizations
- **Numpy** for mathematical operations
- **Git** & **GitHub** for version control

---

## 🧪 How to Run

1. **Clone the repository**:

   
   git clone https://github.com/<your-username>/medical-data-visualizer.git
   cd medical-data-visualizer
Install dependencies:

Ensure you have all the necessary dependencies by installing them with pip:

 
pip install -r requirements.txt
Run the script:

The main Python script medical_data_visualizer.py processes the data and generates the required visualizations.
 
python medical_data_visualizer.py
Run unit tests:

To ensure your code is correct, run the provided unit tests:
 
python -m unittest test_module.py
## 🗂️ Project Structure
 
medical-data-visualizer/
├── medical_data_visualizer.py    # Main script with the core logic
├── medical_examination.csv       # Dataset with medical examination data
├── test_module.py                # Unit tests to validate the functionality
├── main.py                       # Script for testing during development
├── requirements.txt              # Python dependencies
├── README.md                     # You're here!
└── .gitignore                    # Gitignore file to exclude unnecessary files
## 🔗 Links
GitHub Repository: https://github.com/<your-username>/medical-data-visualizer

Gitpod Workspace: [Add your Gitpod link here]

## 📬 About Me
Hi, I'm Konni Devi! I'm passionate about transforming data into actionable insights and applying my analytical skills to real-world problems.

Feel free to reach out if you'd like to collaborate or review the project:

📧 Email: devikonni022@gmail.com
📱 Phone: +91-9392605650



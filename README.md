# **Netflix Data Analysis Project**

This project is part of the **Data Analyst Track** and focuses on analyzing Netflix movie data from the 1990s. Below is a description of the analysis conducted in this project.

---

## **Project Description**

### **1. Filtering Movies**  
Filters movies released between **1990 and 1999** from the Netflix dataset to extract relevant data for analysis.  

---

### **2. Most Frequent Movie Duration**  
Identifies the **most frequent movie duration** in the 1990s using the mode of the `duration` column.  

---

### **3. Short Action Movies Count**  
Counts **short action movies** with durations less than 90 minutes released during the 1990s.  

---

### **4. Visualization**  
(Optional) Creates a **histogram** to visualize the distribution of movie durations from the filtered data using `matplotlib`.  

---

## **System Requirements**

To successfully run this project, follow the steps below:  

1. **Install Python**  
   - Ensure Python 3.7+ is installed on your machine.  

2. **Install Necessary Python Libraries**  
   - Install **pandas** for data manipulation:  
     ```bash
     pip install pandas
     ```  
   - Install **matplotlib** for visualizations (optional):  
     ```bash
     pip install matplotlib
     ```  

3. **Prepare the Dataset**  
   - Download the Netflix dataset (`netflix_data.csv`) and place it in the project directory.  
   - Ensure the dataset includes columns such as `release_year`, `type`, `genre`, and `duration`.  

---

## **Installation Steps (Optional: Virtual Environment)**

1. **Clone the Repository**  
   Clone this repository to your local machine:  
   ```bash
   git clone https://github.com/yourusername/netflix-data-analysis.git
   cd netflix-data-analysis
   ```  

2. **Set Up a Virtual Environment**  
   Using a virtual environment is recommended to manage dependencies and isolate the project's environment:  
   ```bash
   python -m venv env
   source env/bin/activate  # On Windows: env\Scripts\activate
   ```  

3. **Install Required Libraries**  
   Use `pip` to install the required libraries:  
   ```bash
   pip install -r requirements.txt
   ```  

---

## **Code Usage**

### Key Steps in the Analysis  

1. **Filter Movies from the 1990s**  
   Extract movies released between **1990 and 1999** from the dataset.  

2. **Find the Most Frequent Movie Duration**  
   Identify the mode of the movie durations from the filtered dataset.  

3. **Count Short Action Movies**  
   Filter and count action movies with a duration less than 90 minutes.  

4. **Visualize Results**  
   Use a histogram to show the distribution of movie durations (optional).  

---

### **Why Use a Virtual Environment?**  
A virtual environment ensures that your project's dependencies do not interfere with other projects or system-wide packages, improving portability and ease of collaboration.

---

### **Note**  
For any issues or questions, feel free to open an issue on the repository or contact the maintainer.

---

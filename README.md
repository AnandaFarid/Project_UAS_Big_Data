# **Final Project UAS Big Data**

![Project Logo](blog-7-strategi-meningkatkan-review-positif-dari-tamu-hotel-67-l.jpg)

---

## **Exploratory Analysis of Hotel Data**

---

### **Table of Contents**

1. [🔱 Project Title](#project-title)
2. [🌟 Overview](#overview)
3. [🎯 Objectives](#objectives)
4. [📊 Dataset](#dataset)
5. [🔍 Methodology](#methodology)
6. [💡 Key Insights](#key-insights)
7. [⚙️ Dependencies](#dependencies)
8. [🚀 Getting Started](#getting-started)
9. [👥 Team Members](#team-members)
10. [📂 Repository Structure](#repository-structure)
11. [📚 References](#references)

---

### **🔱 Project Title**

**Exploratory Analysis of Hotel Data: Trends, Patterns, and Optimizations**

---

### **🌟 Overview**

This project delves into hotel data to uncover patterns and trends in customer behavior, booking cancellations, and operational efficiency. Using Exploratory Data Analysis (EDA), we aim to generate actionable insights to enhance hotel operations and customer satisfaction. The analysis incorporates advanced visualization and recommendation techniques to explore key variables such as booking cancellations, lead time, and customer segments.

---

### **🎯 Objectives**

- Identify key trends and patterns in customer behavior.
- Analyze factors influencing booking cancellations.
- Provide data-driven recommendations to improve hotel operations.

---

### **📊 Dataset**

The dataset used in this project is sourced from [TidyTuesday](https://github.com/rfordatascience/tidytuesday) and consists of hotel booking data released on **January 21, 2020**. The dataset can be accessed here: [hotels.csv](https://github.com/rfordatascience/tidytuesday/blob/main/data/2020/2020-02-11/hotels.csv).

#### Key Variables:

- **hotel**: Type of hotel (City Hotel or Resort Hotel).
- **is_canceled**: Booking status (0 = Not Canceled, 1 = Canceled).
- **lead_time**: Number of days between booking and arrival.
- **customer_type**: Customer category (e.g., transient, group).
- **market_segment**: Source of bookings (e.g., direct, online).
- **reservation_status**: Final status (e.g., canceled, no-show, checked-out).

---

### **🔍 Methodology**

1. **Data Import and Cleaning:** Importing the dataset and handling missing values.
2. **Exploratory Data Analysis (EDA):** Identifying patterns, trends, and anomalies in the data.
3. **Visualization:** Creating visual representations for easier interpretation of insights.
4. **Recommendation System:** Utilizing patterns for customer behavior predictions.

---

### **💡 Key Insights**

- **Cancellation Rates:** Resort Hotels have higher cancellation rates compared to City Hotels.
- **Lead Time:** Bookings with longer lead times are more likely to be canceled.
- **Customer Types:** Transient customers form the majority of bookings but also have higher cancellation rates.
- **Seasonal Trends:** Higher demand and lower cancellations observed during peak holiday seasons.

---

### **⚙️ Dependencies**

The following Python libraries are required to run the project:

- `pandas` (1.4.3)
- `numpy` (1.23.0)
- `matplotlib` (3.5.2)
- `seaborn` (0.11.2)
- `jupyterlab` (3.4.4)
- `tqdm` (4.64.0)

Dependencies can be installed using the provided `requirements.txt` file.

---

### **🚀 Getting Started**

#### Clone the Repository

```bash
$ git clone https://github.com/AnandaFarid/Project_UAS_Big_Data
$ cd Project_UAS_Big_Data
```

#### Install Dependencies

```bash
$ pip install -r requirements.txt
```

#### Run the Jupyter Notebook

```bash
$ jupyter notebook UAS_BIG_DATA.ipynb
```

Ensure the `hotels.csv` file is in the same directory as the notebook.

#### Explore the Analysis

Follow the steps outlined in the notebook to:
- Clean the dataset.
- Perform EDA.
- Visualize key patterns and trends.

---

### **👥 Team Members**

- **[Ananda Farid Syahputra](https://github.com/AnandaFarid)**  
- **[Sujimmy](https://github.com/Sujimmy)**  
- **[Sultan Yusuf Brian P](https://github.com/SultanYusuf)**

---

### **📂 Repository Structure**

```plaintext
|-- Project_UAS_Big_Data/
    |-- hotels.csv                # Dataset
    |-- UAS_BIG_DATA.ipynb        # Jupyter Notebook for analysis
    |-- requirements.txt          # Required dependencies
    |-- README.md                 # Project documentation
```

---

### **📚 References**

- [TidyTuesday GitHub Repository](https://github.com/rfordatascience/tidytuesday)
- [Matplotlib Documentation](https://matplotlib.org/)
- [Pandas Documentation](https://pandas.pydata.org/)

---

**Thank you for exploring our project!**


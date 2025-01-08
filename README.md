# Customer-Segmentation-with-RFM
This project demonstrates customer segmentation using the **RFM** (Recency, Frequency, and Monetary) model.
RFM is a widely used technique to analyze and segment customers based on their purchasing behavior.

---

## Table of Contents
- [Project Overview](#project-overview)
- [Data Description](#data-description)
- [RFM Model](#rfm-model)
- [Usage](#usage)
- [Installation](#installation)
- [Dependencies](#dependencies)
- [License](#license)

---

## Project Overview
The goal of this project is to perform customer segmentation using the **RFM** model, which helps businesses categorize customers based on three key factors:
1. **Recency (R)**: How recently the customer has made a purchase.
2. **Frequency (F)**: How often the customer makes a purchase.
3. **Monetary (M)**: How much the customer spends.
![image](https://github.com/user-attachments/assets/72a88410-7e9a-49b1-a379-4575036e6c44)
By analyzing these three metrics, we can classify customers into different segments such as:
- High-value customers
- At-risk customers
- Low-engagement customers

---

## Data Description
The dataset used in this project includes customer transaction history with the following key columns:
- `CustomerID`: Unique identifier for each customer.
- `InvoiceDate`: Date of purchase.
- `InvoiceNo`: Invoice number for each transaction.
- `Amount`: The monetary value of each transaction.
![image](https://github.com/user-attachments/assets/1cf57027-4f17-43aa-b9d3-bd053a3058e9)

---

## RFM Model
The RFM model involves calculating three scores for each customer:
1. **Recency**: The number of days since the customer’s last purchase.
2. **Frequency**: The total number of purchases made by the customer in a given time period.
3. **Monetary**: The total monetary value spent by the customer.
These scores are then used to segment customers into different categories for targeted marketing strategies.
![image](https://github.com/user-attachments/assets/2a8aeb16-54e4-4d26-855b-66016eda5a71)

---

## Usage
1. Clone this repository:
    ```bash
    git clone https://github.com/yourusername/customer-segmentation-rfm.git
    cd customer-segmentation-rfm
    ```
2. Load your dataset into the project.
3. Run the RFM analysis script:
    ```bash
    python rfm_analysis.py
    ```
4. View the segmentation results in `rfm_segmentation_output.csv`.

---

## Installation
1. Clone this repository:
    ```bash
    git clone https://github.com/yourusername/customer-segmentation-rfm.git
    ```

2. Navigate to the project directory:
    ```bash
    cd customer-segmentation-rfm
    ```

3. Install required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

---

## Dependencies
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
![image](https://github.com/user-attachments/assets/dfe4a8e6-a563-4a16-ad36-13da8ec00f17)

You can install the required dependencies by running:
```bash
pip install -r requirements.txt

---

## Conclusion
In this project, we applied the **RFM (Recency, Frequency, Monetary)** model to segment customers based on their purchasing behaviors. By analyzing the **Recency**, **Frequency**, and **Monetary** metrics, we were able to classify customers into distinct groups, such as:

- **High-value customers** who frequently engage and spend significantly.
- **At-risk customers** who haven't made recent purchases but have historically spent a lot.
- **Low-engagement customers** who make fewer purchases and spend less.

These customer segments can help businesses tailor their marketing strategies, improve customer retention, and identify opportunities for growth. Targeted campaigns can be designed for each segment, ensuring personalized communication and better resource allocation.

---

### Future Work
- **Incorporate additional features** such as customer demographics, product preferences, or feedback to refine segmentation.
- **Predict customer churn** using the RFM segments and implement targeted retention strategies.
- **Use machine learning** for more advanced segmentation, such as clustering customers based on their RFM scores.

By utilizing customer segmentation models like RFM, companies can gain valuable insights into customer behavior and develop more effective strategies to drive business growth.



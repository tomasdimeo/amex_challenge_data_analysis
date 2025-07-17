# 📊 The American Express Campus Challenge Dataset 

<p align="center">
  <img src="https://imgs.search.brave.com/aA9rhwtcBesbPYeuizmH18-NQbostThv8JDUTXcd_3E/rs:fit:860:0:0:0/g:ce/aHR0cHM6Ly9hc3Nl/dHMuc3RpY2twbmcu/Y29tL2ltYWdlcy82/MjA2NzBiOWQ3Yjkx/YjAwMDQxMjI2MTcu/cG5n" alt="Diagrama" width="600"/>
</p>

Welcome! This repository hosts my resolution of ["The American Express Campus Challenge Dataset 2025 – Product Track"](https://www.kaggle.com/datasets/pratsharma7/the-american-express-campus-challenge-dataset). 


### 🗂️ Dataset Overview

1. Clickstream data of the digital footprint left behind by customers as they browse and interact with Amex’s marketing offers online will be provided.

2. The end objective of this problem statement is to analyse this behavioural data.

3. Participants are not only required to develop a deep understanding of the data but also understand how it can be made fit to use and derive key actionable insights to achieve the desired solution.

#### 🗂️ Repository Structure

| File                    | Description                                     |
| ----------------------- | ----------------------------------------------- |
| `README.md`         | This file.     |
| `amex_data_res.ipynb`   | Jupyter Notebook with the full data cleaning, analysis, and solutions.            |


### 🚀 Getting Started

Follow these steps to set up the project locally.

#### Prerequisites

Make sure you have Python 3.x installed on your system.

#### Installation & Setup

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/tomasdimeo/amex_challenge_data_analysis.git
    cd amex_challenge_data_analysis
    ```

2.  **Create a virtual environment (recommended):**
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
    ```

3. **Run this code in the Jupyter Notebook "amex_data_res.ipynb" to download all the files:**
    ```bash
    !pip install kagglehub # If you don't have the library.
    import kagglehub

    # Download latest version
    path = kagglehub.dataset_download("pratsharma7/the-american-express-campus-challenge-dataset")

    print("Path to dataset files:", path)
    ```

4. **All the necessary libraries are in the Jupyter Notebook with instructions on how to install them.**

## 🎯 Key Insights & Conclusions

This analysis of Amex's clickstream data revealed several key insights into customer behavior and offer performance. Below is a summary of the main findings:

*   **Customer Behavior:** Active users demonstrate significantly higher savings from discounts compared to inactive users. However, contrary to the initial hypothesis, they do not show a stronger preference for Airline offers; instead, their engagement is higher with other categories when measured by conversion rate.
*   **Offer Strategy:** High-value discounts do not universally guarantee higher conversion rates. For categories like Shopping and Travel, offers with lower discount values per dollar surprisingly achieved a better click-through rate, suggesting that other factors (e.g., offer relevance, brand) play a crucial role.
*   **Customer Segmentation:** By segmenting customers into Low, Medium, and High spenders, we found that the **Low-spending segment** showed the highest engagement rate (offers participated in vs. offers rolled out), making them a valuable target for specific campaigns.
*   **Top Performers:** A profile of the top 10 performing offers was built, with **Shopping** and **Entertainment** categories dominating the list. Additionally, an analysis of the top 15 most engaged customers highlighted their preferred offer categories and their responsiveness to email campaigns.

## 📜 License

This project is for educational and demonstrative purposes. Please refer to the original Kaggle dataset page for specific licensing and usage restrictions.

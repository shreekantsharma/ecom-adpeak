# Dropship Analytics Dashboard

A robust, interactive analytics dashboard for e-commerce dropshipping businesses, built with [Streamlit](https://streamlit.io/).

![Status](https://img.shields.io/badge/Status-Maintained-green)
![Python](https://img.shields.io/badge/Python-3.9+-blue.svg)

## 🚀 Features
-   **Smart Data Loading**: Auto-detects CSV vs Excel and finds header rows intelligently.
-   **Column Normalization**: Automatically maps meaningful columns (e.g., "User State" -> "state", "Shopify Store Name" -> "channel").
-   **Cascading Filters**: Filters for Status, Payment, Channel, SKU, and Product adjust dynamically based on your selection.
-   **KPI Cards**: Track Synced Orders, GMV, Margin %, Delivery %, and RTO % at a glance.
-   **Interactive Charts**: 
    -   Daily Orders vs GMV trend
    -   Payment Method split
    -   Confirmation & Status distribution
-   **Detailed Analysis Tables**:
    -   Delivery Performance by Date
    -   Delivery by State (Geography)
    -   Product-level performance metrics

## 🛠️ Installation (Local)

1.  **Clone the repository**:
    ```bash
    git clone https://github.com/shreekantsharma/ecom-adpeak.git
    cd ecom-adpeak
    ```

2.  **Install requirements**:
    ```bash
    pip install -r requirements.txt
    ```

3.  **Run the app**:
    ```bash
    streamlit run app.py
    ```

## 🌐 How to Make it Live (Deploy)

You can deploy this app for free using **Streamlit Community Cloud**, which connects directly to this GitHub repository.

1.  Go to [share.streamlit.io](https://share.streamlit.io/) and Sign Up / Log In (use your GitHub account).
2.  Click **"New app"**.
3.  Select "Use existing repo".
4.  Choose your repository: `shreekantsharma/ecom-adpeak`.
5.  **Branch**: `main`.
6.  **Main file path**: `app.py`.
7.  Click **"Deploy!"**.

Your app will be live in minutes! 🚀

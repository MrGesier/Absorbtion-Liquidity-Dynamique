# Absorbtion-Liquidity-Dynamique
Software allowing to manage your unlocks &amp; Static + Dynamic Liquidity


Here’s a `README.md` (in English) you can use for your GitHub repository based on your Streamlit app:

---

# 🧮 Token Unlock & Overflow Simulation Dashboard

This Streamlit app provides a comprehensive simulation and visualization of **daily token unlocks**, **sell pressure**, **overflow versus liquidity**, and **reward distribution mechanics**. It's tailored for **token engineers**, **treasury managers**, and **economics designers** looking to forecast market dynamics under various tokenomics and liquidity stress conditions.

---

## 🚀 Features

* **Customizable Vesting Schedules**
  Define multiple categories with TGE%, lock-up and vesting periods, and dynamic sell pressure behavior (default vs triggered by ROI).

* **Price Modeling Options**

  * Constant Price
  * Stochastic (Black-Scholes)
  * Adaptive (Black-Scholes + Overflow Response)

* **Liquidity Stress Testing**
  Simulate sell pressure vs. daily liquidity limits with overflow reaction mechanisms and market absorption capacities.

* **Rewards Emission Modeling**
  Customizable logistic distribution for client-based rewards over time.

* **Unsold Token Management**
  Toggle to either keep or exclude unsold tokens from future simulations.

* **ROI Analysis**
  Includes ROI per category and global weighted average ROI based on unlock distribution.

* **Bear Market Shock Simulation**
  Introduce bear periods that multiply sell pressure coefficients.

---

## 📊 Outputs

* **Stacked Token Sales & Unsold Visualization**
  Daily sales in USD by category, unsold stack, liquidity thresholds, and overflow shading.

* **Token Price Chart**
  Single or stochastic paths with confidence envelopes.

* **ROI Curves**
  Category-wise ROI curves plus weighted ROI vs. overflow timeline.

* **Raw Data Display**
  Option to explore all raw simulation results (liquidity, overflow, ROI, prices).

---

## 🛠️ Requirements

Install the necessary Python dependencies:

```bash
pip install streamlit matplotlib numpy pandas statsmodels
```

---

## 🧪 How to Run

```bash
streamlit run app.py
```

Then open `http://localhost:8501` in your browser.

---

## 📁 File Structure

* `app.py` — main Streamlit application.
* `README.md` — this file.
* *(Optional)* Consider splitting modeling logic and plotting functions in future modular versions.

---

## 📌 Notes

* This simulation is **not a financial forecast**. It aims to **stress test and visualize tokenomics assumptions** under various liquidity and volatility conditions.
* Designed with flexibility in mind for iterative Web3 treasury planning and unlock scenario modeling.

---

## 📬 Contact

Built by Yann MASTIN- Nomiks team — feel free to reach out for consulting or integration into your token design processes.



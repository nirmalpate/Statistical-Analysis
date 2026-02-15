 
---

# 🚗 Europe Car Marketing: Performance & Profitability Analysis

This repository contains a Python-based framework for analyzing **YoY Revenue Growth**, **ROAS (Return on Ad Spend)** efficiency, and **A/B Test** performance specifically for the car subscription and rental market (CarCloud).

## 📊 Project Overview

The goal of this analysis is to track how Europe can scale revenue by **300% YoY** while maintaining a strict **25% Net Profit Margin**.

## 🛠 Features

* **A/B Test Simulator:** Compares conversion rates between different landing page CTAs.
* **Revenue Growth Calculator:** Logic for calculating YoY hikes (e.g., transforming €2,000 to €8,000).
* **Target ROAS Modeler:** Determines the exact ROAS required to hit specific profit targets based on unit costs.

## 📈 The Calculations (Step-by-Step)

### 1. Revenue Growth

For a **300% increase** on an initial €2,000:

* **Base:** €2,000
* **Hike:** +€6,000 ()
* **New Total:** **€8,000**

### 2. Profitability Goal (25% Margin)

Based on a **€200** selling price and **€100** maintenance/fleet cost:

* **Target Profit:** €50 (25% of €200)
* **Product Cost:** €100
* **Max Marketing Spend:** €50 ()
* **Required ROAS:** **400%** ()

## 🚀 Usage

Run the analysis script to see the current performance metrics:

```python
# Example command
python europe_analysis.py

```

### Sample Output:

```text
--- A/B Test Results ---
Control CR: 3.00% | Test CR: 4.20%
Uplift: +40.00%

--- Target Strategy ---
Target Profit: €50.00
Max Ad Spend: €50.00
Required ROAS: 400%

```

## 📋 Requirements

* Python 3.x
* Pandas

---


# Cart Abandonment Pattern Analysis & AI-Based Prediction

## Project Overview

This project analyzes e-commerce cart abandonment patterns and builds an
exploratory Random Forest classification model to identify behavioral
signals associated with cart abandonment.

## Business Question

**Where in the checkout flow are customers dropping off, and what should
the product team examine first?**

## Tools & Technologies

- SQL: data extraction and funnel analysis
- Python / Pandas: data cleaning, analysis and feature engineering
- Scikit-learn: Random Forest classification
- Power BI: interactive dashboard
- Matplotlib / Seaborn: visualization

## Dataset

The project uses an e-commerce session dataset containing **25,000 rows
and 29 columns**.

## Key Findings

- Overall cart abandonment rate: **42.00%**
- Added to cart: **16,117 sessions (64.47%)**
- Purchases: **5,616 sessions (22.46%)**
- Very Short sessions had the highest observed abandonment rate:
  **44.13%**
- Monthly abandonment ranged from **40.46% to 44.42%**
- Device type, payment method, marketing channel, product category,
  price segments and discount percentage showed relatively small
  differences.

## AI Model

A Random Forest classifier was trained after removing leakage-prone
outcome variables such as `purchased` and `added_to_cart`.

**Accuracy: 58.32%**

Most influential features: 1. Unit Price 2. Time on Site 3. Rating 4.
Pages Viewed 5. Discount Amount

Feature importance indicates model influence and should not be
interpreted as proof of causation. The model is an exploratory
decision-support component rather than a production-grade predictor.

## Power BI Dashboard

1.  Executive Overview
2.  Checkout Funnel
3.  AI Insights

## Business Recommendations

- Examine the cart-to-purchase gap and checkout journey for friction.
- Improve early-session engagement and product information.
- Monitor checkout and payment experience.
- Use behavioral signals for segmentation and exploratory analysis.
- Track abandonment trends continuously through Power BI.

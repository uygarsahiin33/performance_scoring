# Performance Scoring System

This project focuses on building a **statistical model-based performance scoring system** to dynamically and parametrically evaluate **store and employee performances**. It utilizes **chi-square significance testing** and **clustering algorithms** to generate actionable and data-driven performance insights.

---

## 🚀 Project Objective

To provide companies with a **data-driven**, **objective**, and **flexible scoring framework** for tracking and improving store and employee performance.

---

## 🔍 Methods Used
- 📊 **Chi-Square Tests**: Testing the statistical significance of various performance metrics.
- 📈 **Clustering**: Segmenting stores and employees into performance groups based on behavioral patterns.
- ⚙️ **Dynamic Scoring System**: Generating parametrically weighted performance scores adaptable to business objectives.

---

---

## 📝 Methodology

The scoring process follows a structured, multi-step approach combining statistical validation, distribution-based scoring, and weighted aggregation.

- 🟣 **Step 1: Distribution Identification via Chi-Square Test**
    - Five key performance metrics are analyzed using **Chi-Square significance tests** to understand their distributional behavior.
    - Metrics are classified into:
        - **Beta Distribution (3 metrics)**: Metrics with skewed or bounded distributions (e.g., satisfaction scores).
        - **Normal Distribution (2 metrics)**: Metrics displaying symmetric bell-shaped distributions (e.g., operational timings).

- 🟣 **Step 2: Scoring via Percentile and Sigma Buckets**
    - Each metric is **ranked from worst to best**.
    - For **Beta-distributed metrics**:
        - Scoring follows percentile brackets (0–5%, 5–15%, ..., 95–100%) with scores from **0 to 5**.
    - For **Normally-distributed metrics**:
        - Scoring follows **standard deviation intervals** (e.g., μ ± σ ranges), assigning points based on distance from the mean.

- 🟣 **Step 3: Weighted Aggregation of Scores**
    - Each metric is assigned a **business-priority weight**.
    - The final **weighted average performance score** is computed by multiplying each metric score with its respective weight.

This methodology ensures **fair**, **distribution-sensitive**, and **customizable performance scoring**, offering reliable insights for store and employee performance tracking.


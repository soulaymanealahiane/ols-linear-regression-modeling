# Case Study: Comparing Shariah vs. Conventional Investment Behavior Among University Students

## 📌 Project Overview

**Domain:** Financial Behavioral Science / Islamic Finance

This project employs a **dual-model regression framework** to analyze the elasticity of capital allocation among **UAE university students**. By isolating Shariah-compliant assets from conventional financial instruments, the research quantifies the marginal impact of ethical orientation, financial literacy, and demographic variables on investment propensity.

The findings offer statistical evidence for segmented product structuring in the youth wealth management sector, addressing the lack of granular data on how "ethical screening" interacts with standard economic predictors among Generation Z investors.

## 🛠️ Tools Used

* **SPSS** (Statistical Package for the Social Sciences)
* **OLS Linear Regression Modeling**

## 📂 Repository Contents

* **`[Double_Linear_Regression_Report].pdf`**: The full research report detailing the literature review, statistical methodology, and conclusion.
* **`[Model_Shariah_Data].csv`**: Dataset containing variables used for the Shariah-compliant regression model.
* **`[Model_Conventional_Data].csv`**: Dataset containing variables used for the conventional investment regression model.

## ⚙️ Methodology & Model Specification

Two separate linear models were estimated to solve for the coefficients $\beta$ for Shariah ($Y_a$) and Conventional ($Y_b$) investments.

**The Regression Equation:**

$$
Y_i = \beta_0 + \beta_1(Age)_i + \beta_2(Income)_i + \beta_3(School)_i + \beta_4(FinanceCourses)_i + \beta_5(Ethics)_i + \epsilon_i
$$

### Data Dictionary

| Variable Type | Variable Name | Description |
| :--- | :--- | :--- |
| **Dependent ($Y_a$)** | `Total_Shariah_Investments` | Sum of intended allocation to Sukuk, Islamic Equities, and Halal-screened funds (AED). |
| **Dependent ($Y_b$)** | `Total_Conventional_Investments` | Sum of intended allocation to Bonds, Conventional Mutual Funds, and Insurance products (AED). |
| **Independent ($X_1$)** | `Ethics_Score` | Psychometric continuous scale (1–10) measuring moral/ethical adherence. |
| **Independent ($X_2$)** | `Finance_Courses_Taken` | Integer count of completed finance modules (Domain Knowledge). |
| **Independent ($X_3$)** | `Age` | Continuous variable. |
| **Independent ($X_4$)** | `Parents_Income_Bracket` | Ordinal variable acting as a proxy for socio-economic status. |
| **Independent ($X_5$)** | `School_Dummy_Levels` | Categorical dummies representing academic major/institution. |

## 📊 Key Findings

* **Core Drivers:** Ethics orientation, age, finance education, and parental income were identified as the primary drivers of student investment behavior.
* **Base Determinant:** School/Major acts as a base determinant of initial investment intent, regardless of whether the investment is Shariah-compliant or conventional.
* **Shariah-Specific Predictors:** **Finance education** and **ethical consideration** significantly increase the predicted investment amount specifically for Shariah-compliant products.
* **General Positive Predictors:** Parental income and student age show positive predictive behavior for investment amounts across both categories (Shariah and Conventional).

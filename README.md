# Drug-Inventory-Checker

## Introduction

The Drug Inventory Checker is a Python application built for HealthyLife Pharmacy to streamline daily inventory reporting, monitor expiry status, and evaluate sales performance.

## The Problem Statement

In fast-paced clinical operations, pharmacists face challenges in manually tracking drug inventory, identifying expired medications, and evaluating incorrect stock calculations caused by daily sales. 

Manual reporting is prone to errors, delays, and inconsistent evaluations, making it difficult to flag stockouts and expired drugs that require immediate operational intervention.

## The Solution

To address this, a Python-based operational tool was built to automate daily inventory summaries. The script takes raw drug stock parameters, calculates actual performance metrics, checks compliance against minimum stock targets, and automatically determines whether a medication requires operational review for restocking or expiry.

## Project Importance

Optimizing stock efficiency and tracking expired drugs directly impact a healthcare facility's bottom line and patient safety. Unmonitored stockouts and poor inventory management lead to higher execution costs and reduced margins. Automated operational reporting gives pharmacists immediate visibility to optimize costs and improve drug availability.

## Technologies Used

* Python 3
* Jupyter Notebook

## Python Concepts Used

Built strictly using fundamental Python building blocks:

* **Variables & Data Types:** Storing strings, integers, floats, and booleans for drug attributes.
* **Arithmetic Operators:** Calculating remaining stock and daily revenue.
* **Assignment Operators:** Dynamically updating actual stock levels after daily sales (`-=`).
* **Comparison Operators:** Checking minimum stock thresholds (`<=`) and sales targets (`>=`).
* **Logical Operators:** Evaluating complex dispensing rules (`and`, `or`, `not`).

## Project Flow

* **Inventory Variables:** Initialized drug data, names, stock levels, daily sales, minimum stock, and expiry status.
* **Metric Calculations and Updating Stock:** Calculated stock difference, computing sales revenue and updating total inventory after daily sales using assignment operators.
* **Logical Evaluation and Performance Conditions:** Evaluated boolean flags for minimum stock compliance, discount eligibility, safe-to-sell status, and overall operational review.
* **Drug Inventory Performance Report:** Printed the formatted terminal summary report for Drug 1 (Paracetamol).
* **Bonus Challenge:** Evaluation of identical variable assignment, calculations, and evaluation logic for Drug 2 (Amoxicillin).
* **Comparative Drug Analysis:** Comparing Drug 1 vs. Drug 2 metrics directly using comparison operators.
* **Final Managerial Assessment:** Documenting operational takeaways based on calculated results.

## Results

**Drug 1:**

* Paracetamol
* Starting Stock: 250 units
* Updated Stock Remaining: 185 units
* Units Sold Today: 65
* Revenue Generated: ₦55,250
* Needs Restocking: False
* Safe to Sell: True
* Eligible for Discount: True

**Drug 2:**

* Amoxicillin
* Starting Stock: 90 units
* Updated Stock Remaining: 55 units
* Units Sold Today: 35
* Revenue Generated: ₦52,500
* Needs Restocking: True
* Safe to Sell: False
* Eligible for Discount: False

**Comparative Analysis:**

* Higher Revenue Generation: Paracetamol (₦55,250 vs ₦52,500).
* Requires Restocking: Amoxicillin met its minimum stock trigger; Paracetamol did not.
* Safe for Dispensing: Paracetamol is safe to sell; Amoxicillin is expired and unsafe.
* Requires Operational Review: Amoxicillin / Drug 2.

## Project Screenshots
### Inventory management Output
<img width="1643" height="759" alt="image" src="https://github.com/user-attachments/assets/5cadbae3-4dc4-474a-b934-c1b5d8d47e42" />
<img width="1628" height="674" alt="image" src="https://github.com/user-attachments/assets/b390b75e-4eb8-468b-94bb-0a0a96c4b4d5" />
<img width="1641" height="654" alt="image" src="https://github.com/user-attachments/assets/3f972e89-66c4-4851-8fa0-7dd597851c3d" />
<img width="1634" height="684" alt="image" src="https://github.com/user-attachments/assets/1f0e49e4-8d2a-4e32-b9c8-f6c569c3d338" />
<img width="1190" height="771" alt="image" src="https://github.com/user-attachments/assets/1c3eaec2-087f-40d8-b015-3c5f20216713" />
<img width="1162" height="228" alt="image" src="https://github.com/user-attachments/assets/f9b95af8-ca89-4195-bfdf-08e8041cc079" />


## Key Findings

* **Stock Efficiency Compliance:** Paracetamol successfully stayed above maximum allowable stock thresholds despite daily sales.
* **Safety Target Deviation:** Amoxicillin failed to achieve its safety target (expired), triggering an operational review flag.
* **Cost Optimization Need:** Paracetamol achieved higher revenue and did not require a restock review, whereas Amoxicillin's stock shortfall and expiry will increase operational execution costs if unaddressed.

## Key Learnings

* **Logic over Complexity:** Complex conditional structures (`if`/`else`) aren't always necessary; comparison and logical operators can evaluate complex business logic directly.
* **Data to Insight:** Raw numbers become actionable business decisions when structured into clear operational reports.
* **Domain Context:** Software development in pharmacy requires thinking beyond code to consider operational constraints, safety targets, and cost impacts.

## Future Improvements

* Implement conditional statements (`if`/`elif`/`else`) for customized reporting messages.
* Introduce loops (`for`/`while`) to automate processing across larger pharmacy inventories.

## Author

## MICHAEL DURU
Pharmacy Student (University of Lagos). Data Analyst and Scientist. Python Developer.

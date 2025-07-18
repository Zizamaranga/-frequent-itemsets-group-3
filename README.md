﻿# -frequent-itemsets-group-3
# Frequent Itemsets Group Project – Group 3

**Course:** Data Mining / Warehousing  
**Title:** Exploring Frequent Itemsets: Closed vs Maximal in Supermarket Data  

## Group Members
- Ilham Mohamed- 670152 - iamohamed@usiu.ac.ke
- Yar Deng Kuot-669215 - ydkuot@usiu.ac.ke
- Ruth Musanhu 670474 - rmusanhu@usiu.ac.ke
- Ziza Maranga - 669613 - mziza@usiu.ac.ke
- Samuel Kasusya -668694 - smkasusya@usiu.ac.ke

## Roles & Contributions

- **Ilham Yusuf** – Simulated supermarket transaction data using Python. She generated 3000 transactions, each containing 2–7 randomly selected items from a pool of 30 unique products. Her work produced the `supermarket_transactions.csv` file.
- **Yar Deng Kuot** -Created a custom version of the Apriori algorithm from scratch. She manually handled generating itemsets, calculating support, and picking out the most frequent ones. Her work is in `apriori_custom.ipynb`, and she also exported the results to `frequent_itemsets.csv`,Displayed and exported the top 10 itemsets.
- **Ruth Musanhu** - (*pending*)
- **Ziza Maranga** - (*pending*)
- **Samuel Kasusya** - Responsible for structuring and writing the `README.md` file. Documented each group member’s contribution, ensured clarity in instructions for running the project, and maintained alignment with assignment requirements.


## How to Run

1. Clone the repo: https://github.com/Zizamaranga/-frequent-itemsets-group-3

2. Make sure the required libraries are installed:
- pip install pandas mlxtend

3. Run the notebook cells in this order:
- i. Frequent Itemsets.ipynb
- ii. apriori_custom.ipynb

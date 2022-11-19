# Case_Ambev
 
![GitHub top language](https://img.shields.io/github/languages/top/hbatistuzzo/Case_Ambev)
![GitHub commit activity](https://img.shields.io/github/commit-activity/m/hbatistuzzo/Case_Ambev)
![GitHub code size in bytes](https://img.shields.io/github/languages/code-size/hbatistuzzo/Case_Ambev)
![GitHub last commit](https://img.shields.io/github/last-commit/hbatistuzzo/Case_Ambev)

Project status: In Progress

# Project Summary
<p align="right"><img src="images/Ambev_logo_2015.svg.png" width="40%" alt="Logo"></p>

This is a Data Science challenge from the Brazilian company Ambev.

---

# Technologies

- Python 3.8.13
	- Pandas 1.4.4
	- Numpy 1.21.5
	- Pycaret 2.3.10
	- Seaborn 0.11.2
	- Matplotlib 3.5.2
	- Scikit-learn 1.1
- Tableau 2022.3

---

# The Case

Given the `dataset.json` file which contains the orders made by customers in one of Ambev's applications, the Case establish objective questions to be answered.
Besides an initial inspection, this project will follow the structured path provided by the questions themselves.

---

## Case questions

- **List as many use cases for the dataset as possible**.

	- Locate the best and worst selling products to optimize production.
	- Locate the best and worst selling channels to optimize revenue.
	- Locate the top customers to offer them "bonuses" or "gifts" as a sort of fidelity program.
	- Although not explicitly detailed, one of the attributes of `dataset.json` is the group which a certain customer belongs to, implying a degree os similarity between same-group customers. This allows the construction of
a recommendation system tailored for each group.
	- The "is_churn" attribute seems particularly useful to identify problems in user experience. A strong correlation with a certain seller_code might shed light into the problem.

- Pick one of the use cases you listed in question 1 and describe how building a statistical model based on the dataset could best be used to improve the business this data comes from.

- Implement the model you described in question 2, preferably in Python. The code has to retrieve the data, train and test a statistical model, and report relevant performance criteria.
Ideally, we should be able to replicate your analysis from your submitted source-code, so please explicit the versions of the tools and packages you are using.

- Explain each and every of your design choices, you can use jupyter notebooks. (e.g., preprocessing, model selection, hyper parameters, evaluation criteria). Compare and contrast your choices with alternative methodologies.

- Describe how you would improve the model in Question 3 if you had more time.




---

# Steps

---

# Conclusion
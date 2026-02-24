# Instructions

Experimental observations and their interpretations are crucial since they attach meaning to numbers, tables and graphs that you present. All the explanations should be outside the codeblock, do not write explanations/observations as comments inside the codeblock.

### Guidelines
* Give proper labels, titles, legend to graphs/plots.
* Submit the python notebook (ipynb) or report (pdf).
* Clearly explain/demonstrate using tables, graphs, explanations, observations, conclusions.

### Dataset: LR_MSE.csv
* **Number of data samples:** 300
* **Number of features:** 15 ($x_0$ to $x_{14}$)
* **Target variable:** 1 ($y$)
* **Aim:** Build a linear regressor to predict the target variable $y$, with least Mean Square Error (MSE).

### Experiments
1. **Summarize/Analyze:** Data with statistics and plots.
2. **Impute:** Missing values with different techniques and analyse.
3. **Detect Outliers:** Use different techniques and analyse.
4. **Select Features:** Based on different criterion and analyse.
5. **Pipeline Design:** Provide a pipeline which works best for the given data:
   * **Data** $\rightarrow$ **Impute** $\rightarrow$ **Outlier detect/Removal** $\rightarrow$ **Feature Selection** $\rightarrow$ **Model**

---
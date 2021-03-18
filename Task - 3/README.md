# Task - 3
## Exploratory Data Analysis (EDA) - Retail
**Objective(s)**:
* To perform ‘Exploratory Data Analysis’ on dataset ‘SampleSuperstore’
* As a business manager, try to find out the weak areas where more profit can be made
* Derive business problems through exploration of data

### Details -
<ul>
  <li> <b>Programming Language:</b> Python
  <li> <b>Platform Used:</b> Jupyter Notebooks
  <li> <b>Dataset:</b> SuperStore.CSV
  <li> <b>Libraries:</b> Numpy, Pandas, Matplotlib, Seaborn, Scikit-learn
</ul>

### Collection of observations and suggestions
* There exists a strong correlation between Profit and Sales
* There is no correlation between Discount and Profit
* The South region is generating maximum sales and comparatively low profits.
* There is a disproportionately high discount in central region resulting in low profits.
* For making profits, it's best to keep discount at a maximum of 20%
* Same-day Shipments are not generating losses (generating good profits)
* Negative profit for Discount > 0.5 && Ship Mode ≠ Same Day
* Texas, Pennsylvania and Florida have among the highest sales, but negative profits.
* Texas gives maximum discount, and has the highest loss. Solution - reduce the discounts given out in this state.
* All the states that have seen losses are giving out more than the average discount which needs to be cut down on.
* The states Arizona, Colorado, Oregon and Tennessee have decidedly low sales, which needs a boost

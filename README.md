# MechaCar_Statistical_Analysis

## BACKGROUND

> A few weeks after starting his new role, Jeremy is approached by upper management about a special project. AutosRUs’ newest prototype, the MechaCar, is suffering from production troubles that are blocking the manufacturing team’s progress. AutosRUs’ upper management has called on Jeremy and the data analytics team to review the production data for insights that may help the manufacturing team.
>
> In this challenge, you’ll help Jeremy and the data analytics team do the following:
>
> - Perform multiple linear regression analysis to identify which variables in the dataset predict the mpg of MechaCar prototypes
> - Collect summary statistics on the pounds per square inch (PSI) of the suspension coils from the manufacturing lots
> - Run t-tests to determine if the manufacturing lots are statistically different from the mean population
> - Design a statistical study to compare vehicle performance of the MechaCar vehicles against vehicles from other manufacturers. For each > > > statistical analysis, you’ll write a summary interpretation of the findings.

### OBJECTIVE

- Deliverable 1: Linear Regression to Predict MPG
- Deliverable 2: Summary Statistics on Suspension Coils
- Deliverable 3: T-Test on Suspension Coils
- Deliverable 4: Design a Study Comparing the MechaCar to the Competition

---

## Deliverable 1: Linear Regression to Predict MPG

<table>
  <tr>
    <td>Complete</td>
    <td>Task</td>
    <td>Example</td>
  </tr>
  <tr>
    <td <td> :white_check_mark: </td>
    <td <td style="height:10px;"> 1.) Perform linear regression using the lm() function. In the lm() function, pass in all six variables (i.e., columns), and add the dataframe you created in Step 4 as the data parameter.</td>
    <td <td style="height:10px;"><img src="https://github.com/jcaraway-na/MechaCar_Statistical_Analysis/blob/main/images/importcsv_linear_regression_six_variables.png" width=100% height=100%></td>
  </tr>
  <tr>
    <td> :white_check_mark: </td>
    <td style="height:10px;"> 2.) Using the summary() function, determine the p-value and the r-squared value for the linear regression model.</td>
    <td <td style="height:10px;"><img src="https://github.com/jcaraway-na/MechaCar_Statistical_Analysis/blob/main/images/summary.png" width=100% height=100%></td>
  </tr>
</table>

---

## Deliverable 2: Summary Statistics on Suspension Coils

<table>
  <tr>
    <td>Complete</td>
    <td>Task</td>
    <td>Example</td>
  </tr>
  <tr>
    <td <td> :white_check_mark: </td>
    <td <td style="height:10px;"> 1.) Write an RScript that creates a total_summary dataframe using the summarize() function to get the mean, median, variance, and standard deviation of the suspension coil’s PSI column.</td>
    <td <td style="height:10px;"><img src="https://github.com/jcaraway-na/MechaCar_Statistical_Analysis/blob/main/images/total_summary.png" width=100% height=100%></td>
  </tr>
  <tr>
    <td> :white_check_mark: </td>
    <td style="height:10px;"> 2.) Write an RScript that creates a lot_summary dataframe using the group_by() and the summarize() functions to group each manufacturing lot by the mean, median, variance, and standard deviation of the suspension coil’s PSI column.</td>
    <td <td style="height:10px;"><img src="https://github.com/jcaraway-na/MechaCar_Statistical_Analysis/blob/main/images/lot_summary.png" width=100% height=100%></td>
  </tr>
</table>

---

## Deliverable 3: T-Test on Suspension Coils

<table>
  <tr>
    <td>Complete</td>
    <td>Task</td>
    <td>Example</td>
  </tr>
  <tr>
    <td <td> :white_check_mark: </td>
    <td <td style="height:10px;"> 1.) In your MechaCarChallenge.RScript, write an RScript using the t.test() function to determine if the PSI across all manufacturing lots is statistically different from the population mean of 1,500 pounds per square inch.</td>
    <td <td style="height:10px;"><img src="https://github.com/jcaraway-na/MechaCar_Statistical_Analysis/blob/main/images/t_test.png" width=100% height=100%></td>
  </tr>
  <tr>
    <td> :white_check_mark: </td>
    <td style="height:10px;"> 2.) Next, write three more RScripts in your MechaCarChallenge.RScript using the t.test() function and its subset() argument to determine if the PSI for each manufacturing lot is statistically different from the population mean of 1,500 pounds per square inch.</td>
    <td <td style="width:10px;">
    <img src="https://github.com/jcaraway-na/MechaCar_Statistical_Analysis/blob/main/images/tree_more_psittest.png" width=100% height=100%>
    <img src="https://github.com/jcaraway-na/MechaCar_Statistical_Analysis/blob/main/images/tree_t_test.png" width=100% height=100%>
    </td>
  </tr>
</table>

## Study Design: MechaCar vs Competition

> When diving deeper into the data, we split the data into 3 buckets. Lot 1 and Lot 2 have similar PSI mean and median, with a variance ranging from 0.98 to 7.5 (rounded up), well below the lot allowed. Lot 3 has a lower psi mean and median, with a much higher variance of 170.286 exceeding the lot allowed 100 PSI variance. Just by reviewing this simple variance analysis, we can determine that lot 3 is the contributor to the full lot t-test variance.  

<div>
<img src="https://github.com/jcaraway-na/MechaCar_Statistical_Analysis/blob/main/images/box_plot.png" width=100% height=100%>
</div>

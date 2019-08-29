# Project Capstone

## Episode III

![Explorers](../images/part-03/explorers.jpg)

<br>

### Fitbit EDA

I performed preliminary analysis and created several charts for the datasets. Some charts include:

- BMI Scatterplot (Weight vs Height)
- Activity Level (e.g. High, Sedentary) Distribution by participators
- Steps Count by Day (for 1 participator in a Week)

I concluded that the datasets were not suitable for to build a model predictor. Some reasons were:

Missing Data:
- Some participators only had 1 week of data for the 1st month.
- Only 11 out of 35 participators had Weight data.
- Only 50% of participators had Heart-Rate data.

Use-Case:
- It will be difficult to classify Participator Id due to missing data.
- Needed a better use-case with more practical application.
- The datasets were more appropriate for individual fitness review than building a classification model.

Links: [2_eda_fitbit](../code/fitbit/2_eda_fitbit.ipynb)

<br>

### FitRec EDA

Firstly, I created charts of selected individual workouts e.g. workout route with altitude, speed over time. I realised the timestamps had varying intervals and performed additional data cleansing (i.e. created a time difference column for each json). In addition, I created a lineplot to compare heart-rates for 2 different workouts e.g. cycling and running. I realised I could create a prediction model to classication workout types using features like heart-rate zones.



blank

blank

Links: [2_eda_fitrec](../code/fitrec/2_eda_fitrec.ipynb) | [2_eda_fitrec_2](../code/fitrec/2_eda_fitrec_2.ipynb) | [Tableau](https://public.tableau.com/profile/cheekeet#!/vizhome/2_eda_fitrec/Gender)

<br>

## Episode IV

Report will be out in 2054..

[<<< Rewind to Episode II](part-02.md)

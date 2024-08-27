# Diabetes Prediction in Mothers 

## Introduction
Diabetes is a chronic metabolic disease which is characterized by elevated levels of blood sugar, which over time to serious damage to the heart, blood vessels, eyes, kidneys and nerves.
There are two types of of diabetes type 1 and type 2 diabetes.
Type 2 diabetes is when the body becomes resistant to insulin or doesn't make enough insulin.
Type 1 diabetes is when the pancreas produces little or no insulin by itself.

## Business Understanding

### Background

In introduction we were briefly intoduced to what diabetes is and the most common types of diabetes which is type 1 and type 2 diabetes.
In this section, we will further undertand what type of diabetes mostly affect pregnant mothers or women who have children already and the effect on their children.
First we look at diabetes that affect mothers and pregnant women and its effect on the children:

1. Gestational diabetes

This a form of diabetes that occurs when the blood sugar levels become elevated during pregnancy between the 24th and 28th weeks of pregnancy.
It is caused by hormonal changes during pregnancy that interfere with the body's ability to produce or use insulin.

Risk factors:

a. Overweight

b. Family history of diabetes

c. Age over 25

d. Certain ethnicities

Risks for the mother:

 a. Increased risk of preeclampsia (a serious condition   affecting blood pressure)

 b. Higher chance of cesarean section

 c. Increased risk of type 2 diabetes later in life  

  Risks for the baby:
  
a. Macrosomia(baby is born significantly larger than average)

b. Hypoglycemia after birth(the blood sugar level drops too low)

c. Increased risk of respiratory distress syndrome

d. Higher risk of developing type 2 diabetes

2.  Type 1 diabetes

This is an autoimmune condition where the body's immune system attacks the pancreas.

Risks for the mother:

a. Increased risk of preeclampsia.

b. Higher risk of miscarriage.

c. Increased risk of birth defects.

d. Higher risk of preterm labor.

Risks for the baby:

a. Macrosomia(baby is born significantly larger than average)

b. Hypoglycemia after birth(the blood sugar level drops too low)

c. Increased risk of respiratory distress syndrome

d. Higher risk of developing type 1 diabetes

3. Type 2 diabetes 

A condition characterized by insulin resistance and insufficient insulin production.

Risks for the mother:

a. Increased risk of preeclampsia.

b. Higher risk of miscarriage.

c. Increased risk of birth defects.

d. Higher risk of preterm labor.

Risks for the baby:

a. Macrosomia(baby is born significantly larger than average)

b. Hypoglycemia after birth(the blood sugar level drops too low)

c. Increased risk of respiratory distress syndrome

d. Higher risk of developing type 2 diabetes

### Problem  Statement

As described in the background mothers are at high risk of developing the different forms of diabetes mentioned above and the we have also seen the risks and complications on both mother and child, from factors mentioned such as weight, genetics age and ethnicity.
The challenge is to effectively identify mothers who are high risk of developing diabetes and provide actionable ways for them to manage it and prevent complications during pregnancies.

To address this challenge a logistic regression model can be developed to predict the likelihood of a woman developing diabetes based on relevant features highlighted from the research. This model would enable healthcare providers to identify high-risk individuals early on and offer targeted interventions to improve maternal and child health outcomes.

### Objectives
1.	Create a model that can be used to predict mothers at risk of diabetes based on the features provided in the dataset.

2.	By creating the model will be able to see if it can be used on unseen data to predict women or mothers at risk of diabetes.

3.	By creating the model, it helps us improve early detection of diabetes in mothers and allows us to provide measures to be used to manage the diabetes and prevent complications during pregnancies
.
4.	The model will allow us to prioritize resource allocations in hospitals for mothers who have diabetes and prevent resource wastage on women who do not have diabetes.

5. The model will allow us to better understand the factors influencing the development of diabetes in mothers during and after pregnancy

### Stakeholders and Implications 

1. Healthcare providers

This involves the hospital in general and the general practioners such as gynecologists and obstetricians.
Implication - They can use the model to identify women who are at high-risk of developing diabetes and follow a suitable approach to manage it and prevent complications in function if fall pregnant.

2. Patients

This mainly includes mothers who are at high risk of diabetes or those who have already have diabetes.
Implication - Enables them to be aware of their situation and enable them to manage it outside the hospital with the help of family members. This helps them to prevent complications if they conceive in the future.

3. Health Insurance Companies

Use the model to assess the risk of diabetes-related complications and adjust insurance premiums accordingly.
Implication - The model can help identify populations at high risk for diabetes-related expenses, enabling targeted prevention programs and risk management strategies.

4. Health policy makers

The model enables them to identify the number of women in the area who are at high risk of developing diabetes during or after pregnancy. 
Implication - This can enable them to preserve resources to be allocated in this situation and spread awareness about diabetes in prevention and management programs.

### Conclusion

From the background we have learnt about the different types of diabetes which include gestational diabetes, type 1, type 2 diabetes and the risk and complications implicted on the mothers and the children if not managed or treated properly.
We also discovered a technical of identifying mothers with diabetes by creating a model that can be able to identify women who have diabetes or at high risk of getting it from the ones who do not through certain factors that can cause it.
We also identified different stakeholders of this project and the implications of this project to them

## Data Understanding

### Data Source
The dataset is a healthcare diabetes dataset that was extracted from kaggle https://www.kaggle.com/datasets/nanditapore/healthcare-diabetes.

The importance of this dataset is contains columns such as blood pressure, insulin, glucose, body mass index, number of times of pregnant for a mother as these are factors that can be used to investigate presence of diabetes in an individual depending on the level of each of the factors in the human body.
If the level of glucose is above average this can lead to gestational diabetes in pregnant women and type 2 diabetes.
If the level of insulin is lower than average this can lead to type 1 diabetes.
The dataset enables us to identify the appropriate levels required in terms of the features in dataset to conclude either an individual has diabetes or not

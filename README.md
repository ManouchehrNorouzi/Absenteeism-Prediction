# Absenteeism-Prediction
Modeling Absenteeism

The Anseteeinsm_data.csv contains data for 700 individuals containing features that can cause absence in people.

'Reason for absence' is split into multiple dummy variables, and then group them in the following way:
Group 1: Columns 1 to 14
Group 2: Columns 15, 16, and 17
Group 3: Columns 18, 19, 20, and 21
Group 4: Columns 22 to 28

Then the 'Day' and 'Month' values are extracted and saved into new features.

The other features are also investigated.

Different checkpoints are created to prevent confusion.

According to the aim of the project, the targets are transformed and made ready.

A Customscaler is defined to scale the data and prepare for modeling.

Then the data is split into train and test and a Logistic regression is fitted.

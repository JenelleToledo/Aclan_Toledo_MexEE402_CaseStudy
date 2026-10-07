# Aclan_Toledo_MexEE402_CaseStudy

# MexEE 402: Data Preprocessing Case Study

MexEE Elective 2: Data Science and Machine Learning
Batangas State University, Alangilan Campus
1st Semester, AY 2026-2027

## Members

| Name | Student Number | Section |
|---|---|---|
| Aclan, Yancy |1|MExE-4102|
| Surname, First Name |2|MExE-4102|

## Notebook links

| Chapter | Member 1 | Member 2 |
|---|---|---|
| Ch1_2_3 | [link](https://colab.research.google.com/drive/1wu4UyfOccsoE06wdYid6O66bpzKD4BW8?usp=drive_link) | [link]() |
| Ch4 | [link](https://colab.research.google.com/drive/1OvzMl9VQQkWykBjFH5YzIeS7X8xO04iO?usp=drive_link) | [link]() |
| Ch5 | [link](https://colab.research.google.com/drive/1dRe52PCnbjieKqx31DxIdQqEtVPG2IHF?usp=drive_link) | [link]() |
| Ch6 | [link](https://colab.research.google.com/drive/1ebjp0TOpW6RHm4iwcKYqy-_ch2ZxMHzk?usp=drive_link) | [link]() |
| Ch7 | [link](https://colab.research.google.com/drive/1f2xxXWhP9NieCmtc0ilEzDdbfgoJSah7?usp=drive_link) | [link]() |
| Ch8 | [link](https://colab.research.google.com/drive/14ZBq0X8YIJwTGY8dbeWb4Qz3KJoWROfl?usp=drive_link) | [link]() |
| Ch9 | [link](https://colab.research.google.com/drive/1vsnb6UbnlpgTUEQaoSRAWQg0d5VrkrPV?usp=drive_link) | [link]() |

## What we learned

Chapter 5: Data Scaling

This chapter taught us that data scaling is important when different features have very different numerical ranges. We learned that StandardScaler centers the data around 0 with a standard deviation of 1, while MinMaxScaler puts values between 0 and 1. What surprised us was that scaling does not change the actual relationship between the data, but it changes how the values are represented so that one feature does not dominate another just because it has bigger numbers like what happened in Grades and study hours, the machine value mores the "Grades" values than "Study_hours."

Chapter 6: Dealing with Outliers

Chapter 6 helped us understand how unusual values can affect the way we interpret a dataset. We practiced finding these values using both Z-scores and the IQR method. One thing that stood out was that 100 was clearly much higher than the other values, but the Z-score method did not mark it as an outlier, while the IQR method did. This showed us that different detection methods can give different results.

Chapter 7: Feature Selection

Chapter 7 taught us that having more information does not always mean having a better model. We learned how to identify which variables are actually useful for predicting an outcome and compared three different approaches: filter, wrapper, and embedded methods. What surprised us was that each method selected a different group of features, showing that feature importance can depend on the method being used.

Chapter 8: Constructing a Preprocessing Pipeline

In Chapter 8, we learned how preprocessing helps us prepare data before using it for machine learning. We practiced using a pipeline to handle missing values and scale numerical data, and we learned how ColumnTransformer can apply different steps to specific columns. What surprised us was that the order of preprocessing steps matters, because each step affects the data before it moves to the next step.

Chapter 9: Real-World Application: Data Preprocessing

In Chapter 9, we learned how to apply the preprocessing techniques we have learned in Chapter 8 to the Titanic dataset. We worked with missing values, numerical and categorical data, scaling, one-hot encoding, data reduction, and age discretization. We also learned to use plots to check and understand the processed data. What surprised us was how many different preprocessing steps were needed to turn a real dataset into data that was ready for analysis and modeling.

## Errors we found

List any mistake you found in the original notebooks, and the correct version.
There are real ones in there. Finding them earns points.

## Note on AI tools

Yes, we used AI tools such as Claude AI and Gemini. We used Gemini recommendations while coding because it is easier in putting random sampling data. We used Claude AI in understanding difficult codes and concepts, check the results or possible errors while reviewing the notebooks. We still based our answers on the chapters and the results we obtained from our notebooks.

## References

McKinney, W. (2021). Python for Data Analysis, 3rd ed. O'Reilly.
VanderPlas, J. Python Data Science Handbook.
Any other page or article you used.

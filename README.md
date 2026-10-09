# MexEE 402: Data Preprocessing Case Study

MexEE Elective 2: Data Science and Machine Learning
Batangas State University, Alangilan Campus
1st Semester, AY 2026-2027

## Members

| Name | Student Number | Section |
|---|---|---|
| Garcia, Russel L. |22-01130|MEXE-4101 |
| Sanchez, Ingrid Keight V. |23-03344 |MEXE-4101 |

## Notebook links

| Chapter | Member 1 | Member 2 |
|---|---|---|
| Ch1_2_3 | [Garcia](https://colab.research.google.com/drive/1NSINUKkoJd8A16CoHBV0tNzXMGl9nknb?usp=drive_link)| [Sanchez](https://colab.research.google.com/drive/1niMnBGDzpqNBI00lec_9h_s5Vu2UVQXs?usp=sharing) |
| Ch4 |[Garcia](https://colab.research.google.com/drive/1LDMJrX4tNkF6ssPHuHxilbQdf-5gcc_W?usp=drive_link)| [Sanchez](https://colab.research.google.com/drive/1sF-YTdS1Ap9pTAGINEjxYrmmvhcouYJi?usp=sharing) |
| Ch5 | [Garcia](https://colab.research.google.com/drive/1MLgg2A_AeoCmam5c7uwM007LK10g9qA-?usp=drive_link) | [Sanchez](https://colab.research.google.com/drive/1x2ZtsSkDlwbfeh4qCyg51_qcEqNhelhE?usp=sharing) |
| Ch6 | [Garcia](https://colab.research.google.com/drive/1veMDU31IN3UteAo0jM0w0Dvt4gMN7SiG?usp=drive_link) | [Sanchez](https://colab.research.google.com/drive/1kmZ6GK9V_Z6R3a_EOIJ6NYT5gMfU3bUh?usp=sharing) |
| Ch7 | [Garcia](https://colab.research.google.com/drive/1kuS08D09VqlRZsncZfMh6NRQgLW5YghJ?usp=drive_link) | [Sanchez](https://colab.research.google.com/drive/11NNmG3cvkGssyc8omyaY2zHTu19Cg4eW?usp=sharing) |
| Ch8 | [Garcia](https://colab.research.google.com/drive/1YBtE-SjNbBg6HgEboCKx0U5RCQCLhFBe?usp=drive_link) | [Sanchez](https://colab.research.google.com/drive/1I1_JamS8_ZYhu04Qq30xbfXYtZePKDsO?usp=sharing) |
| Ch9 | [Garcia](https://colab.research.google.com/drive/1Xzqsjon068yBz_mA9sPu2f6_r8LhkIBT?usp=drive_link) | [Sanchez](https://colab.research.google.com/drive/1ZZlKa_ROq1ZLdKytwNOfGOYwmIOgWe6I?usp=sharing) |

## 📖 What we learned
### Chapter 1, 2, and 3
- Basing on our personal experience, considering this as one of the first few try on Google Colab, we were able to discover basic functions such as insertion of texts/codes and uploading of files. This is also the chapter where we encountered numerous errors which also means this area taught us to troubleshoot and adjust the codes as needed. Importing of necessary libraries in order to run the whole program were also learned from this chapter.

### Chapter 4
  - One of the main takeaways from this chapter is how efficient it is to learn how to code especially when you need to categorize continuous values into discrete categories. We believe utilizing Feature engineering and binning will be quite useful on our future pursuit for our research/thesis/capstone. Just like the given examples where instead of just direct and specific temperatures, they were categorized to cool, warm, and hot it allows others, even non-engineering students to somehow grasp what we are working with. 

### Chapter 5
  - As the name suggests from this chapter, we have learned a principle that it is important to level out the playing field. Considering that there were observable variance in the given ranges, it is important that although they relate to each other, we cannot imply their proportionality without first making sure that they are on the same level. The data shown already seemed to be accurate upon first glance but adjusting them to  be on the same footing allowed us to actually understand their relation

### Chapter 6
  - We have learned from processing outliers is that aside from being just the "odd one out" among a data set, although both are useful, there are two contrasting approaches we can do to utilize them, depending on how or when we need them. To put into view, outliers can provide essential information such as indicating the limit or maximum/minimum of data set but at the same time it can be discarded if deemed as an error.

### Chapter 7
  - Just like from the other previous chapters, we have appreciated how much more convenient it is to learn how to code for visual representations such as tables and that it comes in handy when dealing with plenty numerical values. Even more so, since we were faced with a lot of numbers, it is easy to miss basic errors such as the use of capitalization of variables which we encountered in this chapter. Not only did this chapter taught correlation but also vigilance in the works that we do. 

### Chapter 8
  - We put in mind that in order to check if our codes are correct, we must restart the session, run it all again and the program should not crash. However, we have observed that once we have exited the program, we have to upload `train.csv` to the files once again. To fix that, we have changed and updated the provided codes so that whenever we restart the program, the files are already uploaded and we can proceed with running the program right away. As suggested by our instructor as well, this stimulated us to think outside the box and explore more what we know about coding and apply it to this case study. 

### Chapter 9
  - We learned eight data preprocessing techniques using the Titanic dataset, which helped us understand how to prepare data for machine learning. We learned how to handle missing values, reduce data skewness, remove unnecessary columns, group numerical values into categories, convert categorical data into numerical values, and standardize numerical features. We also explored how to fill missing values using SimpleImputer and organize preprocessing steps using pipelines and ColumnTransformer. In addition, we used pandas, os, and files.upload() to make loading the dataset easier. The code checks whether train.csv already exists in the /content/ directory and loads it automatically if available; otherwise, it allows us to upload the file. This makes our work in Google Colab more convenient by reducing the need to upload the same dataset repeatedly.

## ⚠️ Errors we found
In **Chapter 6**, in order to achieve an outlier of 100, the z-score threshold should be 2 instead of 3 and code should be as follows: `outliers = data[np.abs(z_scores) > 2]`. If the code stays with threshold being 3, the code program will not produce an outlier.

In **Chapter 7**, `the variable x must be changed to X`. Please be consistent in using either capital X or lowercase x; we use capital X throughout the code. Another issue is when running RFECV , Python throws multiple runtime warnings. to fix it,either reduce the cross-validation folds (e.g., cv=2) or provide a larger dataset.

For **Chapters 1, 8, and 9**, `running the code without the CSV file` will cause an error. In the original notebooks, the program repeatedly asks the user to upload the CSV file whenever the code is run. Therefore, we added an if-else condition so that the program only asks for the file when it is not already available. This prevents errors when the user reopens the Google Colab notebook and runs all the cells again.

## ⚙️ Note on AI tools

Artificial Intelligence were utilized accordingly in the making of this case study. During the trials and testing of the codes, there were errors encountered for which the application Google Colab suggested for explanations. The use of **Gemini** as an AI tool helped resolve unfamiliar issues and explain parts of the programmed codes that were not fully understood by the students.

**Chapter 1**

In Chapter 1, uploading a CSV file from our file manager to the sample_data folder in Google Colab caused the execution of Run all or the runtime to crash because of insufficient code to handle the file.

We asked the AI tool for suggestions, and we added an if-else statement. If a CSV file is needed for the dataset, the code looks for that filename in the sample_data folder in Google Colab. Otherwise, it asks the user to upload the CSV file.

The concept queries we asked the AI tool were about how to ask the user to upload a file, rename it, and put it in the sample_data folder.

**Chapter 2**

- Error explanation
- Code programming suggestions
- Concepts queries

## 📌 References

McKinney, W. (2021). Python for Data Analysis, 3rd ed. O'Reilly.
VanderPlas, J. Python Data Science Handbook.
Any other page or article you used.


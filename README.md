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
| Ch1_2_3 | [[link](https://colab.research.google.com/drive/1NSINUKkoJd8A16CoHBV0tNzXMGl9nknb?usp=drive_link)]| [link](https://colab.research.google.com/drive/1niMnBGDzpqNBI00lec_9h_s5Vu2UVQXs?usp=sharing) |
| Ch4 |[[link](https://colab.research.google.com/drive/1LDMJrX4tNkF6ssPHuHxilbQdf-5gcc_W?usp=drive_link)]| [link](https://colab.research.google.com/drive/1sF-YTdS1Ap9pTAGINEjxYrmmvhcouYJi?usp=sharing) |
| Ch5 | [[link](https://colab.research.google.com/drive/1MLgg2A_AeoCmam5c7uwM007LK10g9qA-?usp=drive_link)] | [link](https://colab.research.google.com/drive/1x2ZtsSkDlwbfeh4qCyg51_qcEqNhelhE?usp=sharing) |
| Ch6 | [[link](https://colab.research.google.com/drive/1veMDU31IN3UteAo0jM0w0Dvt4gMN7SiG?usp=drive_link)] | [link](https://colab.research.google.com/drive/1kmZ6GK9V_Z6R3a_EOIJ6NYT5gMfU3bUh?usp=sharing) |
| Ch7 | [[link](https://colab.research.google.com/drive/1kuS08D09VqlRZsncZfMh6NRQgLW5YghJ?usp=drive_link)] | [link](https://colab.research.google.com/drive/11NNmG3cvkGssyc8omyaY2zHTu19Cg4eW?usp=sharing) |
| Ch8 | [[link](https://colab.research.google.com/drive/1YBtE-SjNbBg6HgEboCKx0U5RCQCLhFBe?usp=drive_link)] | [link](https://colab.research.google.com/drive/1I1_JamS8_ZYhu04Qq30xbfXYtZePKDsO?usp=sharing) |
| Ch9 | [[link](https://colab.research.google.com/drive/1Xzqsjon068yBz_mA9sPu2f6_r8LhkIBT?usp=drive_link)] | [link](https://colab.research.google.com/drive/1ZZlKa_ROq1ZLdKytwNOfGOYwmIOgWe6I?usp=sharing) |

## 📖 What we learned
### Chapter 1, 2, and 3
  - Basing on our personal experience, considering this as one of the first few try on Google Colab, we were able to discover basic functions such as insertion of texts/codes and uploading of files. This is also the chapter where we encountered numerous errors which also means this area taught us to troubleshoot and adjust the codes as needed. Importing of necessary libraries in order to run the whole program were also learned from this chapter.

### Chapter 4
  - One short paragraph per chapter, Ch1_2_3 to Ch9. Say what the chapter taught you and what surprised you. Not what the library does, but what you understood. One short paragraph per         chapter, Ch1_2_3 to Ch9. Say what the chapter taught you and what surprised you. Not what the library does, but what you understood. One short paragraph per chapter, Ch1_2_3 to Ch9.        Say what the chapter taught you and what surprised you. Not what the library does, but what you understood.

### Chapter 5
  - One short paragraph per chapter, Ch1_2_3 to Ch9. Say what the chapter taught you and what surprised you. Not what the library does, but what you understood. One short paragraph per         chapter, Ch1_2_3 to Ch9. Say what the chapter taught you and what surprised you. Not what the library does, but what you understood. One short paragraph per chapter, Ch1_2_3 to Ch9.        Say what the chapter taught you and what surprised you. Not what the library does, but what you understood.

### Chapter 6
  - One short paragraph per chapter, Ch1_2_3 to Ch9. Say what the chapter taught you and what surprised you. Not what the library does, but what you understood. One short paragraph per         chapter, Ch1_2_3 to Ch9. Say what the chapter taught you and what surprised you. Not what the library does, but what you understood. One short paragraph per chapter, Ch1_2_3 to Ch9.        Say what the chapter taught you and what surprised you. Not what the library does, but what you understood. 

### Chapter 7
  - One short paragraph per chapter, Ch1_2_3 to Ch9. Say what the chapter taught you and what surprised you. Not what the library does, but what you understood. One short paragraph per         chapter, Ch1_2_3 to Ch9. Say what the chapter taught you and what surprised you. Not what the library does, but what you understood. One short paragraph per chapter, Ch1_2_3 to Ch9.        Say what the chapter taught you and what surprised you. Not what the library does, but what you understood.

### Chapter 8
  - One short paragraph per chapter, Ch1_2_3 to Ch9. Say what the chapter taught you and what surprised you. Not what the library does, but what you understood. One short paragraph per         chapter, Ch1_2_3 to Ch9. Say what the chapter taught you and what surprised you. Not what the library does, but what you understood. One short paragraph per chapter, Ch1_2_3 to Ch9.        Say what the chapter taught you and what surprised you. Not what the library does, but what you understood. 

### Chapter 9
  - One short paragraph per chapter, Ch1_2_3 to Ch9. Say what the chapter taught you and what surprised you. Not what the library does, but what you understood. One short paragraph per         chapter, Ch1_2_3 to Ch9. Say what the chapter taught you and what surprised you. Not what the library does, but what you understood. One short paragraph per chapter, Ch1_2_3 to Ch9.        Say what the chapter taught you and what surprised you. Not what the library does, but what you understood. 

## ⚠️ Errors we found
In **Chapter 6**, in order to achieve an outlier of 100, the z-score threshold should be 2 instead of 3 `outliers = data[np.abs(z_scores) > 2]`. If the code stays with threshold being 3, the code program will not produce an outlier and will stay blank

In **Chapter 7**, `the variable x must be changed to X`. Please be consistent in using either capital X or lowercase x; we use capital X throughout the code.

For **Chapters 1, 8, and 9**, `running the code without the CSV file` will cause an error. In the original notebooks, the program repeatedly asks the user to upload the CSV file whenever the code is run. Therefore, we added an if-else condition so that the program only asks for the file when it is not already available. This prevents errors when the user reopens the Google Colab notebook and runs all the cells again.

## ⚙️ Note on AI tools

Artificial Intelligence were utilized accordingly in the making of this case study. During the trials and testing of the codes, there were errors encountered for which the application Google Colab suggested for explanations. The use of **Gemini** as an AI tool helped resolve unfamiliar issues and explain parts of the programmed codes that were not fully understood by the students.
- Error explanation
- Code programming suggestions
- Concepts queries

## 📌 References

McKinney, W. (2021). Python for Data Analysis, 3rd ed. O'Reilly.
VanderPlas, J. Python Data Science Handbook.
Any other page or article you used.


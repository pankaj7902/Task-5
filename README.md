# Task 5 – Python Data Cleaning (Titanic Dataset)

##  Objective
The objective of this task is to perform basic data cleaning using Python and Pandas on the Titanic dataset.

---

##  Tools & Technologies
- Python
- Pandas
- NumPy
- Google Colab

---

##  Dataset
**Titanic Dataset**
- Contains passenger information such as age, gender, class, fare, and survival status.

---

##  Data Cleaning Steps Performed
1. Loaded dataset using `pd.read_csv()`
2. Checked dataset structure using `.head()` and `.info()`
3. Identified missing values using `.isnull().sum()`
4. Filled missing values:
   - Age → Mean
   - Embarked → Mode
5. Dropped Cabin column due to excessive missing values
6. Removed duplicate rows
7. Converted Survived column to categorical datatype
8. Created a new column `Age_Group`
9. Saved cleaned dataset as `cleaned_data.csv`

---

##  Files in Repository
[cleaned_data.csv](https://github.com/user-attachments/files/24794569/cleaned_data.csv)
[Task5_Cleaning.ipynb](https://github.com/user-attachments/files/24794566/Task5_Cleaning.ipynb)


---

##  Final Outcome
This task demonstrates hands-on experience in data cleaning using Python, highlighting how Pandas can efficiently replace manual Excel-based cleaning for large datasets.

Author 
Pankaj Parmar

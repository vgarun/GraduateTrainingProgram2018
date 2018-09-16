
##Fictitious Names Problem

Step 1. Import the necessary libraries

Step 2. Create the 3 DataFrames based on the followin raw data

```
raw_data_1 = {
        'subject_id': ['1', '2', '3', '4', '5'],
        'first_name': ['Alex', 'Amy', 'Allen', 'Alice', 'Ayoung'], 
        'last_name': ['Anderson', 'Ackerman', 'Ali', 'Aoni', 'Atiches']}

raw_data_2 = {
        'subject_id': ['4', '5', '6', '7', '8'],
        'first_name': ['Billy', 'Brian', 'Bran', 'Bryce', 'Betty'], 
        'last_name': ['Bonder', 'Black', 'Balwner', 'Brice', 'Btisan']}

raw_data_3 = {
        'subject_id': ['1', '2', '3', '4', '5', '7', '8', '9', '10', '11'],
        'test_id': [51, 15, 15, 61, 16, 14, 15, 1, 61, 16]}
```

Step 3. Assign each to a variable called data1, data2, data3

Step 4. Join the two dataframes along rows and assign it to all_data

Step 5. Join the two dataframes along columns and assing it to all_data_col

Step 6. Print data3

Step 7. Merge all_data and data3 along the subject_id value

Step 8. Merge only the data that has the same 'subject_id' on both data1 and data2

Step 9. Merge all values in data1 and data2, with matching records from both sides where available.

# Video Game Sales Analysis using Python

This is an analysis to determine if the average global sales was higher before or after 2005 by using Python and MySql. Data verification was completed in MySql in order to ensure that all the records are correctly stored and structured to obtain accurate results in the end. Data cleaning, cleansing, and preprocessing was completed in Python to ensure the dataset is consistent and accurate by removing duplicates, handling missing values, and refining the data. Data analysis to determine the average global sales before and after 2005 was completed in Python as well.

# Getting Started

The instructions below will guide you to obtain a copy of the project and get it up and running on your local machine for development and testing purposes. 

# Prerequisites 

Here are the programs that you will need to install in order to get the Project 3.ipynb file up and running in your local machine.

```
Anaconda (Open source data science and AI distribution platform)

Jupyter Notebook (Interactive development environment)

MySql (Open source relational database management system)
```


# Installing 

Here is a series of step by step instructions how to get the SQL and development environment running.

```
Installing MySQL Workbench:

1. Go to dev.mysql.com/downloads/workbench/.com
2. Click "Free Download".
3. Follow through with the steps of installing MySQL to finish installation.
```
![Screenshot 2025-04-01 at 5 31 24 PM](https://github.com/user-attachments/assets/bec053db-cdbf-4620-876b-584c828b4910)


```
Installing anaconda:

1. Go to www.anaconda.com
2. Click "Free Download"
```

![Screenshot 2025-04-01 at 4 48 14 PM](https://github.com/user-attachments/assets/dc7bd081-c1a1-4acd-9613-a9742b989d7a)

```
3. Follow through with the steps of installing Anaconda to finish installation
```

```
Installing Jupyter Notebook in Anaconda environment:

1. Go to Anaconda environment
2. Search Jupyter Notebook and install it
3. Click "Launch" to open Jupyter Notebook
```
![Screenshot 2025-04-01 at 4 58 45 PM](https://github.com/user-attachments/assets/2563ec23-5219-45db-bf5f-14b857f2762e)

```
4. In the Jupyter Notebook environment find the Project 3.ipynb in your folders where you saved it.
```
<img width="1231" alt="Screenshot 2025-04-01 at 5 05 37 PM" src="https://github.com/user-attachments/assets/60f9ed62-eb0c-4df9-8287-99ae160521b7" />

```
5. Once you have found the file and open it. This is what will what you will see.
```
<img width="1308" alt="Screenshot 2025-04-01 at 5 14 22 PM" src="https://github.com/user-attachments/assets/b62da418-dc81-42fb-8c26-ec62e77654cd" />

# Running the tests

Below will be shown the explanation of running the automated tests for the Python file (Project 3). The testing will begin in MySQL workbench using SQL commands.

## Breakdown of Tests
```
1. An initial excel file containing the data for Video Game Sales is given.
2. Convert the file into a CSV file
3. Import the CSV file into MySQL by right clicking on the database being used and click on Table Data Import Wizard.
4. Follow through with the steps of loading the data of the CSV file into a table within the database in MySQL.
```
<img width="379" alt="Screenshot 2025-04-01 at 5 34 34 PM" src="https://github.com/user-attachments/assets/2282fff7-0927-499e-aaf4-3793f3c790c0" />


<pre>
</pre>

After the data is loaded into a table in the database. The testing of the data can begin by extracting the requried data using SQL commands.

```
Teesting for the first part for of Project 3:

1. Type in SQL commands to obtain the average global sales before and after 2005.
2. The required answer is displayed in the console in the bottom of the screenshot shown below.
```
<img width="1421" alt="Screenshot 2025-04-01 at 5 42 16 PM" src="https://github.com/user-attachments/assets/a500de6d-7fea-446f-93fa-bb7327175846" />


```
Testing for the second part of Project 3:

1. Type in SQL commands to add in a column to display pre and post 2005 for the required records.
2. The required answer is displayed in the console in the bottom of the screenshot shown below.
```
<img width="1429" alt="Screenshot 2025-04-01 at 5 56 55 PM" src="https://github.com/user-attachments/assets/7ff282d9-0027-4224-9734-1f4f00dbb6a7" />


# Deployment 


In order to deploy data in the table after it has been tested in MySQL using the SQL commands shown in the Breakdown of Testing section the follow steps need to be performed:

```
1. In Jupyter Notebook go to the Project 3 Python file and input the MySQL connection code block shown in the screenshot below.
2. Include the host, user, password, and database that you are using for the table you would like to use in the Python script.
3. Input and download the MySQL driver in the Python environment in your localhost. This is shown in the screenshot below.

```
![Screenshot 2025-04-01 at 6 09 37 PM](https://github.com/user-attachments/assets/1629c186-0847-4537-835e-3fefb13af283)
<img width="1326" alt="Screenshot 2025-04-01 at 6 10 55 PM" src="https://github.com/user-attachments/assets/061afc77-481f-44d3-a790-34ce88ee7ab8" />

```
4. Run each of the code blocks you would like to run in Project 3 by clicking the play button at the top of the window as shown in the screenshot below.

```
<img width="1242" alt="Screenshot 2025-04-01 at 6 14 37 PM" src="https://github.com/user-attachments/assets/a57bbca2-7583-4cef-9622-dd3eef1fe1fa" />



# Authors 

- David He - Project 3 (Python)


# License 

This project is licensed and is under the property of David He - see the [LICENSE.md](LICENSE.md) file for details.

# Acknowledgements 

Many thanks to Prof. Omar Altrad for his  guidance in DATA 1202.







# Crowdfunding_ETL

Project Collaborators "The Cool Cat Coders": Taniya Talukdar, Matty Donovan, Saroja Shrestha, Veronica Mueller


Data Sources: crowdfunding.xlsx & contacts.xlsx

<ins>Crowdfunding Analysis</ins> 


At the start of the project, we extracted the crowdfunding.xlsx data and read it into a DataFrame using pandas & numpy. After splitting 'category' and 'subcategory' into two different columns, we found that there are almost three times as many subcategories as categories.

![Figure 2](Images/Figure_2.png)

![Figure 3](Images/Figure_3.png)

<ins>Campaign DataFrame</ins>


*CRUD*

For this part of the project, we made a copy of the crowdfunding information and created a new DataFrame. We renamed some of the columns, converted the 'goal' and 'pledged' columns to float and formatted the launch_date and end_date columns to datetime. We also were able to drop the unwanted columns and export the data to a CSV file.

![Figure 4](Images/Figure_4.png)

<ins>Contacts DataFrame</ins>

We chose option 2 using regex because we are aware how pandas works and we wanted to practice using the new regex skills. We changed the data type for the contact_id column, extracted the email addresses, first and last names into their own columns. Finally, to clean up the data, we dropped uneccessary columns and reordered the information.

![Figure 5](Images/Figure_5.png)

~The Cool Cat Coders
![Cool Cat Coders:)](Images/cat_on_computer.jpg)

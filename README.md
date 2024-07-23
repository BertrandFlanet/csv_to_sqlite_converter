Step 1: Project Title and Description
Step 2: Table of Contents
Step 4: Usage
Step 5: Project Structure Describe the structure of your project directory. This helps readers understand where to find different components of your project.
Step 6: Data
Step 7: Analysis
Step 8: Results
Step 9: Visualizations
Step 10: Conclusions
Step 11: Contact


This is a simple csv to SQLite converter.
It was initially thought in the context of a boot camp at Masterschool, where students were eager to train their SQL skills.
We thus wanted to provide a hands-on solution for students to import a .csv of their liking to convert it in a SQLite database for data exploration.

As such, this code allows one to upload a .csv; normalize the column's names; and output a .db file for use in an application of choice.


- Usage
.ipynb: Google Colab: Upload directly via the "File" menu or open from Google Drive
Jupyter Notebook: Install Jupyter, start it via terminal, and open the .ipynb file through the interface


. If using another IDE, you will need the following libraries:
- os
- shutil
- pandas
- sqlite3
- sqlalchemy


- Project Structure

my_python_project/<br>
|<br>
├── `notebooks/`<br>
│   └── analysis.ipynb<br>
│<br>
└── README.md<br>


- Acknowledgement
Thanks to Mert Topcu and Thimo Wellner for the helpful advices and overlook.


- Contact
Bertrand Flanet<br>
E-mail: bertrand.flanet@gmail.com<br>
linkedIn: https://www.linkedin.com/in/bertrand-flanet-67b1b2299/<br>

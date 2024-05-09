DBMS Project: Transaction Management with Postgres and Python
Overview
This project implements transaction management in PostgreSQL using Python. Transaction management is a critical aspect of database systems, ensuring data integrity and consistency. The system allows users to perform transactions on a PostgreSQL database through Python scripts, handling operations such as querying, updating, and rolling back transactions.

Team Members
Akif Azher Qureshi - Lead Developer
Swetha Murlitharan - Developer
Technologies Used
PostgreSQL: A powerful open-source relational database management system.
Python: A versatile programming language for scripting and automation.
Visual Studio Code: The integrated development environment (IDE) used for writing and debugging code.
Project Structure
scripts/: Contains Python scripts for interacting with the PostgreSQL database.
sql_scripts/: Includes SQL scripts for creating the database schema and sample data.
requirements.txt: Lists the Python dependencies required for the project.
README.md: This file, providing an overview of the project and instructions for setting it up.
Setup Instructions
Clone the Repository: git clone https://github.com/yourusername/dbms-project.git
Set up PostgreSQL: Install PostgreSQL on your system if not already installed. Create a new database and user as per the requirements of the application.
Execute SQL Scripts: Run the SQL scripts provided in the sql_scripts/ directory to create the necessary database schema and insert sample data.
Install Dependencies: Install the required Python dependencies by running pip install -r requirements.txt.
Configure Database Connection: Update the database connection details in the Python scripts (scripts/ directory) to match your PostgreSQL setup.
Run Python Scripts: Execute the Python scripts to perform various transactions such as querying data, updating records, and rolling back transactions as required.
Usage
Open the Python scripts using your preferred text editor or IDE.
Customize the scripts according to your specific requirements, modifying SQL queries and transaction logic as needed.
Run the Python scripts to interact with the PostgreSQL database and perform transactions.
Monitor the database to observe changes and ensure transaction integrity.
Contribution Guidelines
Fork the repository and create a new branch for each feature or improvement.
Submit a pull request detailing the changes made and their significance.
Ensure code quality and adhere to best practices while contributing.
License
This project is licensed under the MIT License - see the LICENSE file for details.

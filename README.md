# Employee-Record-Storage-And-Retrieval-Using-HBASE
HBase table structure (recommendation)

Namespace / Table: employees:emp (namespace employees, table emp)

Column families:

info → basic info (name, age, department)

contact → email, phone

meta → hire_date, salary

# Sample Output

--- Employee Record Storage and Retrieval ---
1. Add Employee
2. View All Employees
3. Search Employee
4. Delete Employee
5. Update Employee
6. Exit
Enter your choice: 1
Enter Employee ID: E101
Enter Name: Ravi
Enter Age: 29
Enter Department: HR
Enter Email: ravi@gmail.com
Enter Salary: 40000
✅ Employee added successfully!

Enter your choice: 2
--- Employee Records ---
ID: E101
   name: Ravi
   age: 29
   dept: HR
   email: ravi@gmail.com
   salary: 40000
-----------------------

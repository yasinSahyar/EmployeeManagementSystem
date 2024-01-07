1. Create a class named Person with the following specifications:
     Attributes:
       - name (String)
       - age (int)
       - gender (char)

     Encapsulate all the fields.
     Add a constructor that can set all the fields when the Person class is created.

     Actions:
       - toString()

   2. Create another subclass of Person named Employee with the following specifications:
     Attributes:
       - employeeId (String)
       - salary (double)

     Encapsulate all the fields.
     Add a constructor that can set all the fields when the Employee object is created.

     Actions:
       - work()
       - displayInfo()

   3. Create a subclass of Employee named Developer with the following specifications:
     Attributes:
       - programmingLanguage;

     Encapsulate the fields.
     Add a constructor that can set all the fields when the Developer object is created.
     Override the work and displayInfo methods.


   4. Create another subclass of Employee named Manager with the following specifications:
     Attributes:
       - department (String)

     Encapsulate the fields.
     Add a constructor that can set all the fields when the Manager object is created.
     Override the work and displayInfo methods.

5. Create a class named Company with the following specifications:
     Attributes:
       - companyName (String)
       - location (String)
       - employees (ArrayList)

     Encapsulate the fields, but only generate getter for the employees ArrayList.
     Add a constructor that can set the companyName and location when the company object is created.

     Actions:
       - hireEmployee(Employee): takes an employee object and adds it to the employees list

       - fireEmployee(id): removes the employee with the given id from the employees list

       - toString(): returns the String representation of the company object which includes the companyName, location and total number of the employees.

       - displayEmployeesInfo(): displays the information of the employees in the company

 

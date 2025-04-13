# Final Exam Prep

<details>
  <summary>
    ✅ Part 1. While loop and built-in functions - (10 pts)
  </summary>

  <details>
    <summary>
      Practice Example 1:
    </summary>
 
  - write a while loop to
    - generate a random integer between two user input values
    - you must do validation to only allow integer values
    - if this random number is the radius of a circle, calculate the area of the circle. This is [the formula](https://github.com/suchialex/CINS3002-FinalExamPrep/blob/main/area.JPG) for area. pi = 3.142
    - Print `The area of circle with radius {random number} m is {calculated area rounded to three decimal places} sq. m.`
    - until user presses x or X
</details>


<details>
    <summary>
      Practice Example 2:
    </summary>
  
  - write a while loop to
    - generate a random float between two user input values
    - you must do validation to only allow floats greater than 0
    - if this number is the side of an equilateral triangle, calculate the area. The formula to calculate area is ![](area2.JPG)
    - print `The area of the triangle with side {random number} ft. is {calculated area rounded to two decimal places} sq. ft.`
    - until user presses 0
  </details>

  
</details>


  <details>
    <summary>
      ✅ Part 2. Files, Functions and Exceptions - (20 pts)
    </summary>
<details>
  <summary>
    Practice Example 1:
  </summary>
  
  - given the products.txt file
  - Product Name, Product ID, Product Price, Product Category, Product Quantity one in each line, in that order
  - user will enter Product ID
  - if product ID present,
  - display all the details of that product
  and
  - modify the product price to user entered value (validate user input to be float greater than zero)
  - if not present, print `Product Not Found`
  - use Option 2
  - handle all potential exceptions
</details>


<details>
  <summary>
    Practice Example 2:
  </summary>

  - given the products2.txt file
  - Product Name, Product ID, Product Price, Product Category, Product Quantity in that order, separated by commas
  - user will enter Product ID
  - if product ID present,
  - display all the details of that product
  - modify the product quantity to a user entered value, validate user input to be an integer
  - if not present, print Product Not Found
  - use Option 3
  - handle all potential exceptions
</details>
  
  </details>


<details>
  <summary>
    ✅ Part 3. Dictionary Manipulation - (20 pts)
  </summary>

  - Unpickle the dictionary stored in employees.bin in the datafiles folder
  - Practice the following operations. You will get a different dictionary in the exam and only five operations to perform
    
  1. Change employee's name ID 04568 to Roger Stevens
  2. For emp ID 04567 add a new certification EVA-L2 taken on March 22, 2023
  3. Add a new title - SGA President - for Riva Malik (you don't know her emp ID)
  4. For all the programmers, give a salary **increment** of 5000
  Must be case in-sensitive, i.e. you have to look for Programmer or PROGRAMMER or programmer as title 
  Hint: you may have to use list comprehension to convert all the titles to lowercase
  5. Add a new certification OCPL1 for emp 04569 taken on March 10, 2023
  6. Assign the project Compete to Roger Stevens (you don't know the emp ID)
  7. For Riva Malik, remove any previous titles and add Casual Wage Worker as the only title
  8. Compete project is taken over by Spring Valley, so change all occurrences of that project with the new name
  9. For anyone who has a certification that starts with OCPL1, add a title called Oracle Developer
  10. Ask the user for a certificate code and print the names of all the employees that have that certificate. Must be case-insensitive. If name is not available, print the emp ID
  11. Print the name and salaries of all the employees who are working on the project Spring Valley. Choose a nice format and alignment so they are displayed in a tabular fashion (name, left aligned over 20, salary right aligned over 8. If either name or salary not available, print -
  Hint: must use end in print statement
  12. Ask user for a new certification code and date taken and add that for emp ID 4571. Cert code must be all uppercase. Assume user will give good value for data in YYYY-MM-DD format
  13. Add a new title - Developer - for an employee name entered by the user, do a case-insensitive comparison 
  14. For all the employees working on Mayfield Inc, give a 25% raise in their salary. If anyone doesn't have a salary, set their salary at 65000
  15. Add a new certification OCPL1 for all employees in the IT department (IT is case-insensitive, could be it, It, iT) taken on March 10, 2023
  16. Print the name, salary and department of all the employees with more than one certification (in a tabular fashion), if name or salary or dept not available, print -
  17. Ask the user for an employee name and a title that he wants to add to this employee and add it. First letter of each word of name and title must be uppercase
  18. For anyone who has a SCJP certification, add a title called Java Developer, must be case-insensitive search
  19. Check the dictionary for any employee who might be missing a name, and if missing, print their ID and ask the user to set a name. Make sure that name doesn't have any special characters except space and first letter of each word must be uppercase. (You may implement it in a function named validate_name, or just a while loop)
  20. Print the names of employees with salaries more than 50000, skip employees that don't have a name
  21. Ask user to enter a department and display in a tabular format names, salaries of all the people in that department. Search for department must be case-insensitive. If names or salaries not available, print -. Choose your alignment and widths.
  
  - Pickle to modified_employees.bin the datafiles folder
</details>

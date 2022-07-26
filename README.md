## Pseudocode

1.  Open the file jsongenerator.py present inside project folder.

2.  Import a built-in package called `json`
3.  Import the following from a file called employee.py:

    - A function called `details`
    - Variables called `employee_name`, `age` and `title`
      <br><br>

4.  Implement the `create_dict()` function that returns a dictionary given employee information.  
    Create and return a dictionary with three key-value pairs where: - Keys are string variables: `"first_name"` `“age”` and `“title”`  
     and their respective values are `employee_name`, `age` and `title` variables that we have imported from the employee module. - Be sure to cast the values to the expected types.
    <br><br>

5.  Use a function called `dumps()` from the json module using dot notation and pass the `employee_dict` dictionary that we have created to it.  
    Return its value to a variable named `json_object`.

        The format of the same should look like:
        ```
        variable = json.dumps(dict)
        ```

6.  Complete the `write_json_to_file()` function - Use a built-in function called `open()` and pass the `output_file` argument and `“w”` to it.  
     Return the value of this function to a variable named newfile. - Call a function called `write()` over this variable newfile. Pass the `json_object` variable you created in Step 5 inside it. - Close this file by calling a built-in function `close()` directly on newfile. You don’t need to pass any arguments here.
    <br><br>

7.  Save the files

8.  Open the terminal to execute the files

9.  Run the code using the command (within project directory)
    ```
     python3 jsongenerator.py
    ```

<br>

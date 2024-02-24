# Activity Set Number 1
Instructions: Create a file for each of the activity and name it using the activity title. Using snake-casing format for your file names.

## variables.py

Task 1:
- Declare and Assign Values to Variables
- Declare a variable called `name` and assign your name as a string to it
- Declare a variable called `age` and assign your age as a number to it
- Declare a variable called `is_student` and assign a boolean value to it

Task 2
- Declare a variable called `birth_year` and `current_year` and calculate your birth year based on your current age

Task 3
- The first two years of a dog’s life count as 10.5 dog years each. Each year following equates to 4 dog years. Supposed your dog's age is your age right now, compute for their human age.

Task 4
- Declare a variable called `triangle_base` and assign width to it
- Declare a variable called `triangle_height` and assign height to it
- Calculate the area of the rectangle using this formula `area = (base * height) / 2` and assign it to `triangle_area` variable
- Print the result

## string.py
Task 1:
- String Slicing
  - Given the string: "MachineLearning"
  - Use slicing to get the first 5 characters and store the result in a variable called `output_1`
  - Print `output_1`

Task 2:
- Substring Extraction
  - Given the string: "PythonIsSuperFun"
  - Use the `string[start:end]` syntax to extract the substring between the 3rd and 7th characters (inclusive)
  - Store the result in a variable called `output_2`
  - Print `output_2`

Task 3:
- Substring Extraction with substr()
  - Given the string: "ExcitingTimes"
  - Use the `string[-x:]` syntax to extract the last 4 characters
  - Store the result in a variable called `output_3`
  - Print `output_3`

Task 4:
- String Replacement
  - Given the string: "orange,apple,orange"
  - Use the `string.replace()` method to replace "apple" with "orange"
  - Store the result in a variable called `output_4`
  - Print `output_4`

Task 5:
- Uppercase Conversion
  - Given the string: "hello, world!"
  - Use the `string.upper()` method to convert the string to uppercase
  - Store the result in a variable called `output_5`
  - Print `output_5`

Task 6:
- Lowercase Conversion
  - Given the string: "ELEPHANTS AND GIRAFFES"
  - Use the `string.lower()` method to convert the string to lowercase
  - Store the result in a variable called `output_6`
  - Print `output_6`

Task 7:
- String Concatenation
  - Given two strings:
    - String 1: "I love "
    - String 2: "machine learning."
  - Use the `string1 + string2` syntax to concatenate the two strings
  - Store the result in a variable called `output_7`
  - Print `output_7`

Task 8:
- Whitespace Removal
  - Given the string: " Welcome to the machine learning class! "
  - Use the `string.strip()` method to remove leading or trailing whitespace
  - Store the result in a variable called `output_8`
  - Print `output_8`

## conditionals.py

## conditionals.py

Task 1:
- Age-based Ticket Price
  - Create a variable called `age` and assign an age value.
  - Create a variable called `ticket_price` and use conditionals to calculate the ticket price based on the age.
    - If age is between 0 and 12 (inclusive), set `ticket_price` to $5.
    - If age is between 13 and 17 (inclusive), set `ticket_price` to $10.
    - If age is between 18 and 59 (inclusive), set `ticket_price` to $15.
    - If age is 60 or above, set `ticket_price` to $12.
  - Print the calculated ticket price.

Task 2:
- Day of the Week Translation
  - Create a variable called `day_number` and assign a value from 1 to 7.
  - Create a variable called `day_of_week` and use conditionals to determine the corresponding day of the week based on the `day_number`.
    - Use a mapping for association (1 for Sunday, 2 for Monday, and so on).
  - Print the corresponding day of the week.

Task 3:
- Discounted Price Calculation
  - Create a variable called `original_price` and assign the original price of an item.
  - Create a variable called `discount_percentage` and assign a discount percentage as a whole number.
  - Use conditionals to validate that the discount percentage is between 0 and 100 (inclusive).
  - Calculate the discounted price by subtracting the discount amount from the original price.
  - Print the discounted price.

Task 4:
- Greeting by Time of Day
  - Create a variable called `hour` and assign a value in 24-hour format.
  - Create a variable called `greeting` and use conditionals to determine the appropriate greeting based on the time of day.
    - If hour is before 12 PM, set `greeting` to "Good morning."
    - If hour is between 12 PM and 5 PM, set `greeting` to "Good afternoon."
    - If hour is after 5 PM, set `greeting` to "Good evening."
  - Print the corresponding greeting message.
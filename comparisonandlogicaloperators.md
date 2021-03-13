# Comparison and Logical Operator
  - You can evaluate a situation by comparing one value to what you think it'll be.
  - The result is boolean: either true or false.
# Equal to: This operator compares two values (numbers, strings, or Booleans) to see if they are the same.
  -"Hello" == "Goodbye" this is false because they are not the same string.
  -"Hello" == "Hello" this is true because they are the same string.
  - This method is most preferred. Considered strict.
# Not Equal to: This operator compares two values (numbers, strings, or Booleans) to see if they are not the same.
  - "Hello" != "Goodbye" is true because they are not the same string.
  - "Hello" != "Hello" returns false because they are the same string.
  - This method is also most preferred. considered strict.
  # Greater Than >: This operator checks to see if the number on the left is greater than the number on the right.
  - 4>3 returns true
  - 3>4 returns false
  # Less Than <: This operator checks to see if the number on the left is less than the number on the right.
  - 4<3 returns false
  - 3<4 returns true
  # Greater than or equal to >=: This operator checks to see if the number on the left is greater than or equal to the number on the right.
  - 4>=3 returns true
  - 3>=4 returns false
  - 3>=3 returns true
  # Less than or equal to <=: This operator checks to see if the number on the left is less than or equal to the number on the right.
  - 4<=3 returns false
  - 3<=4 returns true
  - 3<=3 returns true
  # Structuring Comparison Operators
  - In any conditions there's one operator and two operands
  - The operands are placed on each side of the operator.
  - They can be values or variables often enclosed in brackets.
      - ex: (score>=pass)
  # Using Comparison Operators
  - Most basic level you can evaluate two variables using a comparison operators to return a true or false value.
  - This example shows a user taking a test and the script lets the user know if they passed this round.
      - Example: var pass = 50; // pass mark
                 var score = 90; // score
                 //check if the user has passed
                 var has passed = score >= pass;
                 //write the message into the page
                 var el = document.getElementById("answer");
                 el.textContent = "Level passed: " + has passed;
                 Level passed = true
 # Logical Operators: allow you to compare the results of more than one comparison operator.
 - Example:
       (( 5 < 2) && (2 >= 3))
 # && || !
 # &&: This operator tells more than one condition
 - ((2 < 5) && (3 >= 2)) returns true
 - If both expressions evaluate to true then the expression returns true. 
 - If one expression returns false then the expression is false.
    - true && true returns true
    - true && false returns false
    - false && true returns false
    - false && false returns false
  # || : This operator tests at least one condition
  - ((2 < 5)) || (2 < 1)) returns true
  - If either expression evaluates true then the expression returns true 
  - If both return false then the expression returns false
    - true || true returns true
    - true || false returns true
    - false || true returns true
    - false || false returns true
  # !: This operator takes a single Boolean and inverts it
  -!(2 < 1) returns true
  - This reverses the state of an expression. 
  - If it was false without the ! it would return true.
  - If it was true without the ! it would return false.
  - ! true returns false
  - ! false returns true
  # Short-Circuit Evaluation
  - logical expressions are evaluated left to right
  - if the first condition can provide enough info to get the answer there's no need for
    - Example:
    - false && anything it has found a false.
    - true || anything it has found a true
  # Loops: check a certain conditon
  - if condition returns true, a code block will run
  - the condition will be checked again
  - if it's still true, the code block will run again
  - it will repeat until conditon returns false
  # Three types of Loops
  - For: If you need a specific code a number of times. 
    - It is the common loop
    - It's usually a counter to tell how many times a loop should run
  - While: If you're unsure how many times a code shoud run
    - This code is something other than a counter
    - the code will loop as long as the condition is true
  - Do While: 
    - similar to while loop
    - will always run condition in braces at least once
    - will run even if condition is false
  # Loop Counters
  - A for loop uses a counter as a condition
    - Initialization: create a variable set it to 0, variable is called i
     - example: var i = 0;
    - Condition: The loop should continue to run until it reaches a specified number
     - i < 10;
    - Update: Every time the loop has run the statement in the curyl braces, it adds one to the counter.
     - i++
   # Using While Loops
   - Here is an example of a while loop. It writes out the 5 times
   - table. Each time the loop is run, another calculation is written
   - into the variable called msg.
    - Example: c04/ js/while-1oop.js JAVASCRIPT
        var i = l ;
        var msg = ' ' ;
        II Set counter to 1
        II Message
        II Store 5 times tabl e in a variable
        while (i < 10) {
        msg += i + ' x 5 = ' + (i * 5) + '<br I>';
        i++;
        document .getEl ementByid( ' answer') . innerHTML = msg;
    - The first statement uses the+= operator, which is used to add
    - new content to the msg variable.
    - Each time the loop runs, a new
    - calculation and line break is
    - added to the end of the message
    - being stored in it. So+" works as
    - a shorthand for writing:
    - msg = msg + 'new msg'
    - (See bottom of the next page for
    - a breakdown of this statement.)
    - The second statement increments the counter variable by one. (This is done inside
    - the loop rather than with the condition.) When the loop has finished, the
    - interpreter goes to the next line of code, which writes the msg variable to the page.
        









 
  

          
  

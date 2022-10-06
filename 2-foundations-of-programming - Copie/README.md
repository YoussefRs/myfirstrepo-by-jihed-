# Part II: Foundations of Programming

*Note: Before getting started on these exercises, please be certain that you've read through the root [README.md](../README.md) file in this repository.*

## Exercises

### Basic Requirements

#### Numbers

1. Enter the following expressions into your console.

   ```js
   1 + 2 = 3
   3 * 5 = 15
   5 / 4 - 13 = -11.75
   5000 * 234 = 117000
   1073 / 57 + 200 = 218.824
   ```

2. Why are the values produced by the following two expressions different? What
   are they? Cause in mathematics, the priority is for what between parenthses.

   ```js
   3 + 2 * 4 - 1
   (3 + 2) * (4 - 1)
   ```

3. Calculate 50 years in minutes using the console. 
 Var result = 60*24*365*50;
 Console.log(result); 

4. What is the percentage of letters in the english alphabet that are vowels (including y)? Use the
   console to find out.  23.09%
Var vowels = 6;
Var TotalAlphabetsNumber = 26;
Var Result = (vowels/totalAlphabetsNumber)*100;
console.log(Result);

5. Try the following expressions in the console:

   ```js
   6 % 2 = 0 
   42 % 10 = 2
   5 % 2 = 1
   6 % 3 = 0
   7 % 4 = 3 
   100 % 12 = 4
   ```

   What is the significance of the result? How does the `%` (modulus) operator
   work?     It works as a remainder of a division operation. 

6. Try the following:

   ```js
   3 % 2 = 1
   4 % 2 = 0
   5 % 2 = 1 
   6 % 2 = 0
   ```

   What do the results tell you about the first operand to the modulus operator? 
   It reminds me of the type Boolean.

#### Strings

1. Write a string that represents your full name. "YoussefRouissi"

2. Write a string that represents your favorite food. "Pizza"

3. Use the `+` operator to combine (known as *concatenation*) two or more
   strings, *e.g.*:

   ```js
   // Your first and last names
   "John" + " " + "Doe"
   ```

   + Your first and last names (as shown above)
   + Your best friend's full name
   + Your home town, state and country

   "Youssef" + " Rouissi"
   "Islem" + " Arfaoui"
   "Hammem chatt" + "-Ben Arous" + "-Tunisia"



4. Fix the errors in the following strings:

   ```js
   Where are all the quotes?
   "hmm something is not right"
   "Do other " + "operators work with string concatenation?"
   ```

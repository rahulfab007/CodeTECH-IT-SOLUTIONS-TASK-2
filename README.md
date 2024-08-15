
### Abstract
The Temperature Conversion Program is a simple console-based application that facilitates the conversion of temperature values between Celsius, Fahrenheit, and Kelvin. Users can choose from a menu of conversion options and input the temperature they wish to convert. The program processes the input, performs the necessary calculations using predefined formulas, and displays the converted temperature. This project serves as an educational tool for understanding temperature units and their interrelationships while also providing hands-on experience with C programming concepts such as data types, conditional statements, and user input handling.

### Technologies Used
- **Programming Language:** C
- **Development Environment:** Any standard C compiler (e.g., GCC, Clang) or IDE (such as Code::Blocks, Dev-C++, or Visual Studio).
- **Input/Output Libraries:** The program utilizes the standard input/output library (`<stdio.h>`) for handling user input and displaying output.

### Key Points
1. **User Interaction:**
   - The program begins with a clear menu prompting the user to select a conversion option.
   - Users enter their choice as an integer, which drives the program’s flow based on the selected option.

2. **Conversion Options:**
   - The program provides six conversion options:
     - Celsius to Fahrenheit
     - Celsius to Kelvin
     - Fahrenheit to Celsius
     - Fahrenheit to Kelvin
     - Kelvin to Celsius
     - Kelvin to Fahrenheit
   - Each option corresponds to a specific conversion formula.

3. **Accurate Formulas:**
   - The program implements accurate temperature conversion formulas to ensure correct results:
     - **Celsius to Fahrenheit:** \( F = \frac{9}{5} \times C + 32 \)
     - **Celsius to Kelvin:** \( K = C + 273.15 \)
     - **Fahrenheit to Celsius:** \( C = (F - 32) \times \frac{5}{9} \)
     - **Fahrenheit to Kelvin:** \( K = (F - 32) \times \frac{5}{9} + 273.15 \)
     - **Kelvin to Celsius:** \( C = K - 273.15 \)
     - **Kelvin to Fahrenheit:** \( F = (K - 273.15) \times \frac{9}{5} + 32 \)

4. **Data Types and Calculations:**
   - The program uses `float` data types for temperature values to accommodate decimal points, ensuring accuracy in conversions.
   - Floating-point arithmetic is utilized where necessary to prevent integer division errors.

5. **Structured Control Flow:**
   - A `switch` statement is used to manage user choices effectively, allowing for a clean and organized flow of execution.
   - Each case in the switch statement handles a specific conversion and includes break statements to prevent fall-through.

6. **Error Handling:**
   - A default case is included in the switch statement to handle invalid user input, prompting users to select a valid option from the menu.

7. **User-Friendly Output:**
   - The output is formatted to display two decimal places for better readability, using the `%.2f` format specifier in the `printf` function.

8. **Educational Value:**
   - This project not only reinforces fundamental programming concepts but also educates users on temperature scales and conversions, making it suitable for learners and educators.

### Conclusion
The Temperature Conversion Program is an excellent example of how to apply C programming principles to create a functional and educational application. It demonstrates the effective use of control structures, data types, and mathematical operations, making it a valuable resource for beginners in programming and those seeking to understand temperature conversions. Further enhancements could include error checking for invalid temperature inputs or expanding the program to include more complex temperature-related functionalities.

![Screenshot 2024-08-15 151125](https://github.com/user-attachments/assets/9345a2db-e8f9-4c40-a870-a08e9c705778)

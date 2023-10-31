# CurrencyExchangeProject
Name: Denis Gomeze

Currency Exchange Program

This is a currency exchange program implemented in C# using Windows Forms. It allows users to convert dollars currency to cryptocurrency. The program assumes that the user has a certain amount in dollars and wants to know the equivalent amount in cryptocurrency based on the current exchange rate.

File 1: Program.cs
-------------------
This file contains the entry point of the application. It initializes the application's visual styles and runs the main form for currency conversion.

Implementation Details:
- The application enables visual styles.
- The compatible text rendering is set to false.
- The main form, Form1 (CurrencyConverter), is instantiated and run.

File 2: Form1.cs
----------------
This file defines the main form of the currency exchange application and its associated event handlers for currency conversion.

Implementation Details:
- The form contains a text box  for users to enter the amount in dollars.
- The form contains a button  to trigger the currency conversion.
- The event handler  handles the click event of the "Convert" button. It retrieves the entered dollar amount, converts it to cryptocurrency using the current exchange rate, and displays the result in a label (resultLabel).
- The event handler also includes logic to handle potential errors or invalid input.
- The program assumes that the exchange rate is pre-defined within the code.

File 3: Converter.cs
---------------------
This file, Converter.cs, is a utility class that can be used to manage the currency conversion logic.

Implementation Details:
- Implement methods for converting dollars to cryptocurrency based on the current exchange rate.
- Include error handling for invalid or unavailable exchange rates.

Note: The currency exchange program is a basic implementation and does not interact with live currency exchange data or APIs. Users should enter the amount in dollars, and the program will calculate the equivalent amount in cryptocurrency based on a predefined exchange rate. For a real-world application, you would need to incorporate live currency exchange data and ensure data security and accuracy.

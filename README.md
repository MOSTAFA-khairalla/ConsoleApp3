Sum of Numbers Program 🧮
This is a simple C# console application that calculates the sum of all numbers from 1 to a user-provided number.

📌 How It Works:
The program prompts the user to enter a number.
It initializes sum to 0.
Using a for loop, it iterates from 1 up to the number (exclusive) and adds each value to sum.
Finally, it prints the total sum.
💡 Example Input & Output:
vbnet
Copy
Edit
Enter a number: 5
Sum of numbers from 1 to 5 is: 10
(Note: The code currently excludes the entered number from the sum. Modify i < number to i <= number to include it.)

🚀 How to Run:
Copy the code into a .cs file (e.g., Program.cs).
Compile and run it using the .NET CLI:
sh
Copy
Edit
dotnet run
🛠️ Future Improvements:
Fix the loop condition to include the last number.
Allow multiple inputs in one session.
Add error handling for invalid inputs.

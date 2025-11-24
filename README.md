# 🎲 Lucky Number Game

A simple C program that lets users enter two numbers, calculates their sum, and checks if the result is a **Lucky Number** (divisible by 7). 

---

## 📖 Description
This project is a beginner-friendly C program designed to:
- Accept two integer inputs from the user.
- Compute their sum.
- Print the sum.
- Determine if the sum is divisible by 7.
  - If yes → Displays **"Lucky Number!!!"**
  - If no → Displays **"Not a Lucky Number :)"**

---

## 🛠️ Features
- Interactive input prompts.
- Basic arithmetic operations.
- Conditional check for divisibility.
- Clear output messages.

---

## 📂 Project Structure
```c
#include <stdio.h>

int main() {
// Display game title
    printf("======= This is a Lucky Number Game =======\n");
    
// Declare variable to store the first number
    int first_num;
    printf("Enter the First Number: ");
    scanf("%d", &first_num);   // Read input from user
    
// Declare variable to store the second number
    int second_num;
    printf("Enter the Second Number: ");
    scanf("%d", &second_num);  // Read input from user
    
// Calculate the sum of both numbers
    int sum;
    sum = first_num + second_num;
    printf("The sum is: %d", sum);   // Print the sum
    
// Check if the sum is divisible by 7
if (sum % 7 == 0) {
printf("\nLucky Number!!!");   // Print if divisible by 7
} 
else {
printf("\nNot a Lucky Number :)"); // Print if not divisible by 7
}
    
return 0;   // End of program
}

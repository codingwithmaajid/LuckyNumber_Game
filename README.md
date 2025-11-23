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

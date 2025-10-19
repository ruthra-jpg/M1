
# EX-01-Datatypes-Operators
## AIM:
Write a C program to read 3 characters one by one and print the characters in a reverse order.

## ALGORITHM:
1.	Declare three character variables to store the input characters.
2.	Use the scanf function to read the characters one by one from the user.
3.	Print the characters in reverse order using the printf function.
4.	End the program.

## PROGRAM:
```
#include <stdio.h>
int main()
{
    char c1,c2,c3;
    scanf("%c %c %c",&c1,&c2,&c3);
    printf("The reverse of %c%c%c is %c%c%c",c1,c2,c3,c3,c2,c1);
    return 0;
}
```
## OUTPUT:
![WhatsApp Image 2025-10-19 at 15 19 31_b79e7ee5](https://github.com/user-attachments/assets/16f53293-a109-4abc-86df-985d68919f69)


## RESULT:
Thus the program to read 3 characters one by one and print the characters in a reverse order has been executed successfully.


# EX-02- Conditional-Statements
## AIM:
Write a C program to read A values and check whether A is positive number or not.

# ALGORITHM:
1.	Declare a variable to store the input value A.
2.	Use the scanf function to read the value of A from the user.
3.	Check if the value of A is greater than zero.
4.	If A is greater than zero, print a message indicating that it's a positive number. 
5.	Otherwise, print a message indicating that it's not a positive number.
6.End the program.

# PROGRAM:
```
#include <stdio.h>

int main(void) {
    int A;

    printf("Enter a number: ");
    scanf("%d", &A);

    if (A > 0) {
        printf("%d is a positive number.\n", A);
    } else {
        printf("%d is *not* a positive number.\n", A);
    }
return 0;
	}
```

# OUTPUT:


![WhatsApp Image 2025-10-19 at 23 25 09_a5cdc59c](https://github.com/user-attachments/assets/fd0457fa-a448-49a2-a154-b24a1fe03b70)



# RESULT:
Thus the program to read A values and check whether A is positive number or not has been executed successfully.
 
 
 


# EX-03- Operators-Expressions
## AIM:
Write a program to find minimum between two fraction numbers using conditional operator or ternary operator.

## ALGORITHM:
1.	Declare variables to store the two fraction numbers and the result.
2.	Use the printf function to prompt the user to enter the first fraction number (numerator and denominator separately).
3.	Use the scanf function to read the numerator and denominator of the first fraction.
4.	Repeat steps 2 and 3 to get the second fraction from the user.
5.	Calculate the decimal values of both fractions by dividing the numerators by the denominators.
6.	Use the conditional (ternary) operator to compare the decimal values and store the minimum value in the result variable.
7.	Print the minimum value.

## PROGRAM:
```
#include <stdio.h>
int main()
{
    float num1,num2,min;
    scanf("%f %f",&num1,&num2);
    min = (num1<num2)? num1:num2;
    printf("Minimum between %.3f and %.3f is %.3f",num1,num2,min);
    return 0;
    
}
```
## OUTPUT:

![WhatsApp Image 2025-10-19 at 15 58 32_4b23f679](https://github.com/user-attachments/assets/347b6714-18d5-4c16-ab76-7fdb87b1014d)

## RESULT:
Thus the program to find minimum between two fraction numbers using conditional operator or ternary operator has been executed successfully.




# EX-04- Using Conditional Statements

## AIM:
Write a C program to check whether the input value is equal to 1 using simple if statement

## ALGORITHM:
1.	Declare a variable to store the input value.
2.	Use the scanf function to read the input value from the user.
3.	Use an if statement to check if the input value is equal to 1.
4.	If the condition in the if statement is true, print a message indicating that the input value is equal to 1.
5.	Otherwise, print a message indicating that it's not equal to 1.
6.	End the program.

## PROGRAM:
```
#include <stdio.h>

int main(void) {
    int A;

    printf("Enter a number: ");
    scanf("%d", &A);

    if (A == 1) {
        printf("The number is equal to 1.\n");
    }

    return 0;
		}
```
## OUTPUT:


![WhatsApp Image 2025-10-19 at 23 29 39_82d81384](https://github.com/user-attachments/assets/ddef7599-a942-4a92-a36f-91debde323e9)




## RESULT:
Thus the program to check whether the input value is equal to 1 using simple if statement has been executed successfully



# EX-05- Calculating Total, Percentage, And Division Using Conditional Statements 
## AIM:
To write a C program that reads marks of three subjects, calculates the total and percentage, and then determines the division (First, Second, Pass, or Fail) based on the percentage and minimum marks criteria.
## ALGORITHM:
1.	Start
2.	Declare integer variables m1, m2, m3 for marks, and float variables tot, per.
3.	Input the marks for three subjects.
4.	Calculate total marks: tot = m1 + m2 + m3
5.	Calculate percentage: per = tot / 3
6.	Display total and percentage.
7.	Check if all marks are greater than or equal to 40:
8.	If yes:
a.	If percentage >= 60: Print “Division = First”
b.	Else if percentage >= 48: Print “Division = Second”
c.	Else if percentage >= 36: Print “Division = Pass”
9.	Else: Print “Division = Fail”
10.	End
## PROGRAM:
```
#include <stdio.h>
int main()
{
    int s1,s2,s3,s4,s5,s6,s7;
    scanf("%d %d %d %d %d %d %d",&s1,&s2,&s3,&s4,&s5,&s6,&s7);
    float total,avg,percent;
    total = s1+s2+s3+s4+s5+s6+s7;
    avg = (total)/7.0;
    percent = ((total)/700.0) * 100;
    printf("Total marks = %.2f",total);
    printf("\nAverage marks = %.2f",avg);
    printf("\nPercentage = %.2f",percent);
    return 0;
}
```

## OUTPUT:
![WhatsApp Image 2025-10-19 at 16 10 58_d012d649](https://github.com/user-attachments/assets/81c4cd2f-f0cd-4450-b165-62b60c5bf6f0)

## RESULT:
The program successfully takes three subject marks, calculates the total and percentage, and correctly determines the division based on predefined grading logic.


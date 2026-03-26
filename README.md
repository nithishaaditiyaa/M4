# EX-16-LEFT-SHIFT-OPERATION

## NAME: R . NITHISH AADITIYAA

## REGISTER NO: 25011876 [ 212225040287 ]

## AIM
To write a C Program to perform the basic left shift operation for 44 integer number with 3 shifts.

## ALGORITHM
1.	Start the program.
2.	Assign values of a and b as 44 and 3.
3.	Use left shift operator (<<) and shift the value of a three times.
4.	Display the result.
5.	Stop the program.

## PROGRAM
```
#include<stdio.h>
int main()
{
    int a,b;
    printf("Assign the values as a and b: ");
    scanf("%d %d",&a,&b);
    printf("\nLeft shift operation of %d by %d is %d",a,b,a<<3);
    return 0;
}
```
## OUTPUT

<img width="884" height="255" alt="Screenshot 2026-03-26 141911" src="https://github.com/user-attachments/assets/7dc67ea0-c127-4327-a4f8-420ee96df0cc" />


## RESULT
Thus the program to perform the basic left shift operation for 44 integer number with 3 shifts has been executed successfully.


# EX-17-TWO-NUMBERS-ARE-EQUAL-OR-NOT

## AIM

Write a C Program to check whether the two numbers are equal or not using simple if statement.

## ALGORITHM

1.	Start the program.
2.	Read two numbers.
3.	If first number is equal to second number, display both are equal.
4.	Otherwise display both are not equal.
5.	Stop the program.

## PROGRAM
```
#include<stdio.h>
int main()
{
    int num1,num2;
    scanf("%d %d",&num1,&num2);
    if(num1==num2)
    {
        printf("Both the numbers are equal.");
    }
    else
    {
        printf("Both the numbers are not equal.");
    }
    return 0;
}
```
## OUTPUT

<img width="887" height="228" alt="Screenshot 2026-03-26 142737" src="https://github.com/user-attachments/assets/ccc9ef1d-3e77-46fc-a764-92015aa8f385" />


## RESULT

Thus the program to check whether the two numbers are equal or not using simple if statement has been executed successfully
 

# EX-18-STRING-LOWERCASE-CONVERSION

## AIM
Write a C Program to convert the given string into lowercase.

## ALGORITHM
1.	Start the program.
2.	Read a string variable.
3.	Using tolower( ) function convert the given string into its lowercase.
4.	Display the result.
5.	Stop the program.

## PROGRAM
```
#include<stdio.h>
#include<ctype.h>
int main()
{
    char ch[100];
    scanf("%[^\n]",ch);
    printf("After converting string to lowercase: ");
    for(int itr=0;itr<100,ch[itr]!='\0';itr++)
    {
        
        printf("%c",tolower(ch[itr]));
    }
    return 0;
}
```
## OUTPUT

<img width="911" height="194" alt="Screenshot 2026-03-26 142943" src="https://github.com/user-attachments/assets/21f750f4-445d-494b-b48b-1be128252a9c" />


## RESULT
Thus the program to convert the given string into lowercase has been executed successfully
 
 
# EX-19-COUNT-OF-WORDS-IN-A-STRING
## AIM
Write a C Program to count the total number of words in a given string using do While loop.

## ALGORITHM
1.	Start the program.
2.	Read a string variable.
3.	Using for loop, inspect the string character by character.
4.	Whenever a space is encountered increment count by 1.
5.	Display the result.
6.	Stop the program.

## PROGRAM
```
#include<stdio.h>
int main()
{
    int count=0,i=0;
    char ch[100];
    scanf("%[^\n]",ch);
    do
    {
        if(ch[i]!=' ')
        {
        count+=1;
        }
        i+=1;
    }
    while(ch[i]!='\0');
    printf("The total no of words = %d",count);
    return 0;
}
```
## OUTPUT

<img width="886" height="188" alt="Screenshot 2026-03-26 143037" src="https://github.com/user-attachments/assets/d1330f67-8a65-415c-99ed-4c0a1f61c46a" />


## RESULT
Thus the program to count the total number of words in a given string using do While loop has been executed successfully
 

# EX  -20 -COMPARING TWO STRINGS
## AIM
write a Program to compare two strings without using strcmp().
## ALGORITHM
Step 1: Start the program.
Step 2: Declare two character arrays c1 and c2 of size 100 to store the strings. Also, declare an integer variable
             flag and initialize it to 0, and i for indexing.      
Step 3: Read the first string c1 using scanf("%[^\n]", c1); — this reads input until a newline is encountered 
            (i.e., can include spaces).
Step 4: Read the second string c2 using scanf("%s", c2); — this reads input until a space or newline (i.e., no 
            spaces in the second string).
Step 5: Start comparing characters of both strings from index i = 0.
Step 6: Repeat the following while neither c1[i] nor c2[i] is '\0' (i.e., end of string):
•	If c1[i] is not equal to c2[i], set flag = 1.
•	Increment i by 1.
Step 7: After the loop, check the value of flag:
•	If flag == 0, print "strings are same".
•	Otherwise, print "strings are not same".
Step 8: End the program.

## PROGRAM
```
#include<stdio.h>
#include<string.h>
int main()
{
    int flag=0;
    char str1[100],str2[100];
    scanf("%[^\n]",str1);
    scanf("%s",str2);
    int itr=0;
    while(str1[itr]!='\0'&&str2[itr]!='\0')
    {
        if(str1[itr]!=' '&&str2[itr]!=' ')
        {
            if(str1[itr]==str2[itr])
                {
                    flag+=1;
                }
        }
        itr++;
    }
    if(flag==strlen(str1)&&flag==strlen(str2))
    {
        printf("Strings are same.");
    }
    else
    {
        printf("Strings are not same.");
    }
    return 0;
}
```
## OUTPUT

<img width="909" height="232" alt="Screenshot 2026-03-26 143205" src="https://github.com/user-attachments/assets/a635cb0a-a679-4906-a749-de0adedf7450" />
<img width="894" height="228" alt="Screenshot 2026-03-26 143151" src="https://github.com/user-attachments/assets/d3b7afaf-b652-4659-b745-940e3c67ede1" />



## RESULT
Thus the C Program to compare two strings without using strcmp() has been executed successfully.


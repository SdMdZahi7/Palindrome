# Palindrome


## Aim:
To write a C# program to find whether the given string is a Palindrome or not.
## Algorithm:
Step 1:
To start the C# program in visual Studio 2022.

Step 2:
Create a class and declare two variable with string datatype.

Step 3:
Loop over the entire string and reverse it.

Step 4:
Use if condition to check whether the string and the reversed string is equal or not.

Step 5:
print palindrome if it's equal else print not a palindrome.

Step 6:
Save the program and run the program in visual studio 2022.

## Program:
~~~
using System;
namespace  Palindrome
{
    public class program
    {
        static void Main(string[] args)
        {
            string s, rev = "";
            Console.WriteLine("Enter String: ");
            s = Convert.ToString(Console.ReadLine());
            for(int i=s.Length-1;i>=0;i--)
            {
                rev += s[i];
            }
            if(rev == s)
            {
                Console.WriteLine("{0} is the Entered String\n{1} is Palindrome",s, rev);
            }
            else
            {
                Console.WriteLine("{0} is the Entered String\n{1} is not Palindrome",s, rev);
            }
            Console.ReadLine();
        }
    }
}

~~~

## Output:
![2](https://user-images.githubusercontent.com/94187572/190057467-01fb5786-001d-4503-8e9c-fa9b26978672.png)
![1](https://user-images.githubusercontent.com/94187572/190057489-29402e21-191a-481f-b0c5-f7cb86384927.png)


## Result:
Thus the C# program to display whether the given string is Palindrome or not is executed successfully.

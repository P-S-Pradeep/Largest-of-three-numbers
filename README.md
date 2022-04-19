# Largest-of-three-numbers
## Aim:
To write a C# program to find the largest of three numbers

## Algorithm:
### Step1: 
Start
### Step2:
Create a class and declare three variable with integer datatype
### Step3:
Use if condition to check whether num1 is largest than num2 and num3
### Step4:
Use elif condition to check whether num2 is largest than num1 and num3
### Step5:
Use else condition to display that third variable is largest among all the variables
### Step6:
stop

## Program:
~~~
using System;
namespace Pradeep
{
    class program
    {
            static void Main(string[] args)
            {
                int num1, num2, num3;
                Console.WriteLine("Enter Three integer");
                num1 = Convert.ToInt32(Console.ReadLine());
                num2 = Convert.ToInt32(Console.ReadLine());
                num3 = Convert.ToInt32(Console.ReadLine());
            if ((num1 > num2) && (num1 > num3))
                Console.WriteLine(num1 + " is Greater");
            else if ((num2 > num1) && (num2 > num3))
                Console.WriteLine(num2 + " is Greater");
            else
                Console.WriteLine(num3 + " is Greater");
        }
    }
}
~~~

## Output:
![Screenshot (53)](https://user-images.githubusercontent.com/102652887/163914411-9fa61f32-73a3-47be-b245-0913b87ea2d4.png)
## Result:
Thus the C# program to find the largest of three numbers is executed successfully

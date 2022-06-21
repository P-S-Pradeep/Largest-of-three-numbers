### EX NO:01 
### DATE: 
# <p align="center"> Largest of three numbers</p> 
## Aim:
To write a C# program to find the largest of three numbers


## Algorith:

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
```C#
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
```
## Output:


![1](https://user-images.githubusercontent.com/102652887/174746601-6928a50a-fa9d-4e28-9310-f276646e491f.png)

## Result:
Thus the C# program to find the largest of three numbers is executed successfully

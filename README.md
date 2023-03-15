# Eligibility-for-Admission

## Aim:
To write C# program to find the eligibility for admission to an engineering course

## Algorithnm:
## step 1:
Create a New project or class.
## step 2:
Declare the variable and read the input from the user.
## step 3:
Find the total1 and total2.
## step 4:
Check the given condition using nested if statement.
## step 5:
Display the output whether the student is eligible or not.



## Program:
```
using System;

public class ConsoleApp1
{
    public static void Main(string[] args)
    {
        int phy, chem, mat, tot1, tot2;
        string name;
        Console.WriteLine("Enter the Phy mark:");
       phy = Convert.ToInt32(Console.ReadLine());
        Console.WriteLine("Enter the chem mark:");
       chem= Convert.ToInt32(Console.ReadLine());
        Console.WriteLine("Enter the mat mark:");
        mat= Convert.ToInt32(Console.ReadLine());
        Console.WriteLine("Enter a Name of the student");
        name = Console.ReadLine();
        tot1 = phy + chem + mat;
        tot2 = phy + mat;
        if(phy>=55 && chem>=50 && mat>=65)
        {
            if(tot1>=180 || tot2>=140)
            {
                Console.WriteLine("{0} is eligible for engineering admission",name);
            }
            else
            {
                Console.WriteLine(name + " is not eligible for engineering admission");

            }
        }
        else
        {
            Console.WriteLine("{0} is not eligible for engineering admission",name);
        }

    }
}
```




## Output:
![i1 (4)](https://user-images.githubusercontent.com/94508142/225380044-1f4e9c49-8f5f-46cb-b24c-67f7cdb14621.jpeg)
![i1 (5)](https://user-images.githubusercontent.com/94508142/225380097-7f35ec6c-36d1-4122-b5c1-00db684afde1.jpeg)
![i1 (6)](https://user-images.githubusercontent.com/94508142/225380113-50dd668a-8b68-45bb-9317-2d37bafd2d8e.jpeg)




## Result:
Thus the C# program to check the eligibility of a student on engineering admission is successfully executed.

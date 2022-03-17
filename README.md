# multiplication-runtime-constructor-
using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;

namespace constructor89
{
    class Program
    {
        //c# program to illustrate calling
        //a default constructor
        int fno;
        int sno,result;
        //this would be invoked while the object of class created.
        Program(int a,int b)
        {
            fno = a;
            sno = b;
            result = fno * sno;
            Console.WriteLine("multiplication of two number is:" + result);
        }
        //main method
        static void Main(string[] args)
        {
            int a,b;
             Console.WriteLine("enter first number:");
            a = Convert.ToInt32(Console.ReadLine());
            Console.WriteLine("enter second number:");
            b = Convert.ToInt32(Console.ReadLine());
            
            //this would invoke default  //constructor.
            Program p = new Program(a,b);
            
 //default constructor provides //the default values to the //int and object.
             
            Console.ReadLine();
        }
    }
}

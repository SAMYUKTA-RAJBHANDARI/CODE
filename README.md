// Take 3 integer from user and display which is greater
using System;

namespace Workshop1
{
    class Program
    {
        static void Main(string[] args)
        {
            for (int i=2, ,i++) { }
            int a; int b; int c;
            Console.WriteLine("Enter first number");
            a = int.Parse(Console.ReadLine());
            Console.WriteLine("Enter Second number");
            b = int.Parse(Console.ReadLine());
            Console.WriteLine("Enter Third number");
            c = int.Parse(Console.ReadLine());

            if (a > b)
            {
                if (a > c)
                {
                    Console.WriteLine("a is greater ");
                }
                else
                {
                    Console.WriteLine("c is greater ");

                }
            }
            else if (b > c)
                Console.WriteLine("b is greater");
            else
                Console.WriteLine("c is greater");


        }
    }
}
}

using System;

namespace Solution
{
    class Task
    {
        static void Main(string[] args)
        {
            Console.Write("Enter Positive Number : ");
            int number = int.Parse(Console.ReadLine());

            if (number < 0 )
            {
                Console.WriteLine("Please Enter a Positive Number.");
            }

            int Sum = 0;
            for (int i = 1; i <= number; i++)
            {
                Sum += i;
            }

            Console.WriteLine("The Total is : " + Sum);
        }
    }
}

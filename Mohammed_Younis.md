```C#
using System;

namespace Summition{

    public static class Program{

        public static void Main(){

            int n;
            Console.Write("Inter an integer number : ");
            n = int.Parse(Console.ReadLine());

            int sum = (n*(n+1))/2 ;

            Console.WriteLine($"Result is {sum}");

        }
    }
}
```

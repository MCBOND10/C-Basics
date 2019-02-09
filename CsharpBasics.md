# C Sharp Basics Challenge

```C#
using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace Csharp_Basics
{
    class Placeholder
    {
        static void Main(string[] args)
        {
            //declaring variables
            const byte sample1 = 0x3A;
            byte sample2;
            int heartRate;
            double deposits;
            const float acceleration = 9.800f;
            float mass;
            double distance;
            bool lost;
            bool expensive;
            int choice;
            const char integral = '\u222B';
            const String greeting = "Hello";
            String name;

            //initializing variables
            sample2 = 58;
            heartRate = 85;
            deposits = 135002796;
            mass = 14.6f;
            distance = 129.763001;
            lost = true;
            expensive = true;
            choice = 2;
            name = "Karen";

            //sample comparison
            if (sample1 == sample2)
                Console.WriteLine("The samples are equal.");
            else
                Console.WriteLine("The samples are not equal.");
            Console.WriteLine("\n");

            //heartrate if else
            if (heartRate >= 40 && heartRate <= 80)
                Console.WriteLine("Heart rate is normal.");
            else
                Console.WriteLine("Heart rate is not normal.");
            Console.WriteLine("\n");

            //deposits if else
            if (deposits >= 100000000)
                Console.WriteLine("You are exceedingly wealthy.");
            else
                Console.WriteLine("Sorry you are so poor.");
            Console.WriteLine("\n");

            //force calculation
            float force = mass * acceleration;
            Console.WriteLine("force = {0}", force);
            Console.WriteLine("\n");

            //distance display
            Console.WriteLine("{0} is the distance", distance);
            Console.WriteLine("\n");

            //lost and expensive true or false
            if (lost == true && expensive == true)
                Console.WriteLine("I am really sorry! I will get the manager.");
            if (lost == true && expensive == false)
                Console.WriteLine("Here is a coupon for 10% off.");
            Console.WriteLine("\n");

            //choice switch
            switch (choice)
            {
                case 1:
                    Console.WriteLine("You chose 1.");
                    break;
                case 2:
                    Console.WriteLine("You chose 2.");
                    break;
                case 3:
                    Console.WriteLine("You chose 3.");
                    break;
                case 4:
                    Console.WriteLine("You made an unknown choice.");
                    break;
            }
            Console.WriteLine("\n");

            //integral display
            Console.OutputEncoding = System.Text.Encoding.UTF8;
            Console.WriteLine("{0} is an integral", integral);
            Console.WriteLine("\n");

            //for loop
            int i;
            for (i = 5; i < 11; i++)
            {
                Console.WriteLine("i={0}", i);
            }
            Console.WriteLine("\n");

            //while loop
            int age = 0;
            while (age < 6)
            {
                Console.WriteLine("age={0}", age);
                age++;
            }
            Console.WriteLine("\n");

            //hI kArEn
            Console.WriteLine("{0} {1}!", greeting, name);
            Console.WriteLine("\n");
        }
    }
}
```

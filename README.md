using System;

class Program
{
    static void Main(string[] args)
    {
         int weekNumber = 4;
            switch (weekNumber) {
            case 1:
            Console.WriteLine("Monday");
            break;
            case 2:
            Console.WriteLine("Tuesday");
            break;
            case 3:
            Console.WriteLine("Wednesday");
            break;
            case 4:
            Console.WriteLine("Thursday");
            break;
            case 5:
            Console.WriteLine("Friday");
            break;
            case 6:
            Console.WriteLine("Saturday");
            break;
            case 7:
            Console.WriteLine("Sunday");
            break;
            default:
            Console.WriteLine("Invalid number of day.");
            break;
            }
            
        char letter = 'B';
            switch (letter) {
            case 'A':
            Console.WriteLine("Apple");
            break;
            case 'B':
            Console.WriteLine("Banana");
            break;
            case 'C':
            Console.WriteLine("Cherry");
            break;
            case 'D':
            Console.WriteLine("Dewberry");
            break;    
        }
    }
}

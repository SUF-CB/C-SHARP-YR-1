using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;
// Name of program- The Multiplication Quiz- 
// programmer-Sufyaan Shaikh 
// version 1.1
// Date Created- 5/02/2019

namespace ConsoleApp1
{
    class Program
    {
        static int num1;
        static int num2;
        static int question = 1;
        static int correct = 0;

        static void Main(string[] args)
        {
            while (true)// loop  - the program keeps on running 
            {
                Console.ForegroundColor = ConsoleColor.Cyan;
                Console.WriteLine("Welcome to the Multiplication Quiz!");
                Console.ForegroundColor= ConsoleColor.Yellow;
                Console.ReadLine();
                Console.WriteLine("You will be asked 10 multiplication questions, after you have typed your answer press  Enter key to move onto the next questions  ");
                Console.ReadLine();
                Console.WriteLine("Take your time ! if you dont know the answer just guess  ");
                Console.ReadLine();
                Console.WriteLine("Good luck !");
                Console.ReadLine();
                Console.WriteLine("Once you have read the instructions press the Enter key to begin ");
                Console.ReadLine();
            

                Multiply();
            }
        }

        static void Multiply()
        {
            Random r = new Random();

            num1 = r.Next(1, 13); // 2 random number are chosen between 1 and 12
            num2 = r.Next(1, 13);

            Questions();
        }

        static void Questions()
        {
            int user;
            int answer;
            answer = num1 * num2;
            Console.ForegroundColor = ConsoleColor.White;
            Console.Write("what is " + num1 + "X" + num2 + "? ");
            user = int.Parse(Console.ReadLine());

            if (user == answer)
            {
                correct = correct + 1;
                Console.ForegroundColor = ConsoleColor.Green;
                Console.WriteLine("Correct!"); // if the user has the answer correct it will display as a message
                Console.ReadLine();
            }
            else
            {
                Console.ForegroundColor = ConsoleColor.Red;
                Console.WriteLine("Wrong!");
                Console.ReadLine();
            }

            if (question != 10) // If the question is not equal to 10 then it will add one to the question integer and go to the multiply procedure  
            {
                question = question + 1;
                Multiply();
            }
            else
            {
                Console.ForegroundColor = ConsoleColor.Magenta;

                Console.WriteLine("You got " + correct + " out of 10");// outputs the number of correct answers out of the 10 questions
                Console.ReadLine();
            }
        }
    }
}

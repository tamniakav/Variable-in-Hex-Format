# Variable-in-Hex-Format
Just another repository
using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace Variable_in_Hexadecimal_Format
{
    class Program
    {
        static void Main(string[] args)
        {
            string hex = Console.ReadLine();

            Console.WriteLine(Convert.ToInt32(hex, 16));
        }
    }
}

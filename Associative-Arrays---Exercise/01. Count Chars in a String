using System;
using System.Collections.Generic;
using System.Linq;
using System.Numerics;

namespace ConsoleApp1
{
    class Program
    {
        static void Main(string[] args)
        {  
            Dictionary<char, int> characters = new Dictionary<char, int>();
            string input = Console.ReadLine().Trim();
            char[] chars = input.ToCharArray();

            for (int i = 0; i < chars.Length; i++)
            {
                if (chars[i]!=' ')
                {
                    if (!characters.ContainsKey(chars[i]))
                    {
                        characters[chars[i]] = 0;
                    }
                    characters[chars[i]] += 1;
                }
            }

            foreach (var c in characters)
            {
                Console.WriteLine($"{c.Key} -> {c.Value}");
            }
            
        }
    }
}

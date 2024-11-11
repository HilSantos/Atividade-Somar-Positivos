# Atividade-While-Somar-Positivos
Solicite ao usuário que digite números positivos para somar. O programa deve parar de pedir números e exibir o total acumulado quando o usuário digitar um número negativo.

using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace Ativ.WhileSomarPositivos
{
    public class Program
    {
        static void Main(string[] args)
        {
            int op, cont, numero, i = 1;

            Console.WriteLine("Digite o numero: ");
            numero = Convert.ToInt32(Console.ReadLine());

            while (i <= 0)
            {
                Console.WriteLine($"{i}+{i}={i + i}");
                i++
            }

            Console.ReadKey();
        }
    }
}

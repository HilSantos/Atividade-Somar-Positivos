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
            int soma = 0;
            int numero;

  Console.Write("Digite um número positivo (ou um negativo para parar): ");
            numero = int.Parse(Console.ReadLine());

  while (numero >= 0)
            {
                soma += numero;
                Console.Write("Digite outro número positivo (ou um negativo para parar): ");
                numero = int.Parse(Console.ReadLine());
            }

  Console.WriteLine($"A soma dos números positivos é: {soma}");
            Console.ReadKey();
        }
    }
}

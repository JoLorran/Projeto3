using System;

class Program
{
    static void Main()
    {
        // Solicita a base do retângulo
        Console.Write("Digite a base do retângulo: ");
        double baseRetangulo = double.Parse(Console.ReadLine());

        // Solicita a altura do retângulo
        Console.Write("Digite a altura do retângulo: ");
        double alturaRetangulo = double.Parse(Console.ReadLine());

        // Calcula a área do retângulo
        double area = baseRetangulo * alturaRetangulo;

        // Exibe o resultado
        Console.WriteLine($"A área do retângulo é: {area}");
    }
}

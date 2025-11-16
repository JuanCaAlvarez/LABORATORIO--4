"# PRACTICA-DE-CAMPO-4" 
C#:
using System;
class Program { 
    static double CalcularArea(double baseR, double altura)
    {
        return baseR * altura;
    }
    
    static void Main()
    {
        Console.Write("Ingrese la base: ");
        double b = double.Parse(Console.ReadLine());
        Console.Write("Ingrese la altura: ");
        double h = double.Parse(Console.ReadLine());

        double area = CalcularArea(b,h);
        Console.WriteLine($"El área del rectángulo es: {area}");

    }

}

PYTHOM:
def calcular_area(base, altura):
  return base * altura
base = float(input("ingrese la base: "))
altura = float(input("ingrese la altura: "))

area = calcular_area(base, altura)
print(f"El área del rectángulo es: {area}")

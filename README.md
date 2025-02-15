int suma(int num1, int num2)
{
    int resultado = 0;
    resultado = num1 + num2;
    return resultado;
}
int n1, n2;
Console.WriteLine("ingrese dos numeros");
n1 = int.Parse(Console.ReadLine());
n2 = int.Parse(Console.ReadLine());

Console.WriteLine("Quieres sumar estos números? (digito si/no)");
string respuesta = Console.ReadLine();
if (respuesta == "si")
{
    int resultado = suma(n1, n2);
    Console.WriteLine("El resultado de la suma es: " + resultado);
}
else if (respuesta == "no")
{
    Console.WriteLine("no se hizo nada");
}
else
{
    Console.WriteLine("Operación cancelada.");
}

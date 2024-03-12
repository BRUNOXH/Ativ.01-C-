using System;

class Programcs
{
    static void Main()
    {
        int n1, n2, n3, res;
        res = n1 = n2 = n3 = 0;
        string resultado;



        Console.WriteLine("digite qual a sua nota AC01: ");
        n1 = int.Parse(Console.ReadLine());
        Console.WriteLine("digite qual a sua nota AC02: ");
        n2 = int.Parse(Console.ReadLine());
        Console.WriteLine("digite qual a sua nota AC03: ");
        n3 = int.Parse(Console.ReadLine());

        res = n1 + n2 + n3;
        res = res / 3;

        if(res >= 6)
        {
            resultado = "aprovado";
        }
        else
        {
            resultado = "reprovado";
        }
        Console.WriteLine("nota final das AC: {0} resultado: {1}", res, resultado);
    }

}

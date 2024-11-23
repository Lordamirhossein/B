// See https://aka.ms/new-console-template for more information


Console.WriteLine("pls enter first number");
int num1 = int.Parse (Console.ReadLine());
Console.WriteLine("pls enter secend number");
int num2 = int.Parse (Console.ReadLine());
Console.WriteLine("pls enter third number");
int num3 = int.Parse (Console.ReadLine());


if (num1 > num2 && num1 > num3)
    Console.WriteLine("bigest number: "+num1);

if (num2 > num1 && num2 > num3)
    Console.WriteLine("bigest number: " + num2);

if (num3 > num2 && num3 > num1)
    Console.WriteLine("bigest number: " + num3);


Console.ReadKey();
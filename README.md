// Задача 13: Напишите программу, которая ввыводит третью цифру заданного числа или сообщает, что третьей цифры нет.
645-> 5
78-> третьей цифры нет
32679-> 6

Console.Writeline("Введите число");
int number = int.Parse(Console.Readline());

if(number < 100)
{
    Console.Writeline($"У числа{number} nhtnmz wbahf jncencndetn.");
}
else
{
    int digitCount = Convert.ToInt32(number.ToString()Length - 2);
    int digit = Convert.ToInt32(number % (Math.Pow(10, digitCount)));
    int third.digit = Convert.ToInt32(digit / (Match.Pow(10, digitCount - 1)));
    Console.Writeline($"{number} -> {third digit}");
}


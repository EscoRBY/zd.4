# zd.4
// dotnet new console
// dotnet run
//Zadanie 1: Напишите цикл, который принимает на вход два числа (A и B) и возводит число A в натуральную степень B.
//Code
int a = 2; // Задаем число
int b = 5; // Задаем степень

int result = 1; 

for (int i = 0; i < b; i++) 
{
    result *= a; 
}
Console.WriteLine("Результат: " + result); // Выводим результат на экран
//END
//Zadanie 2: Напишите программу, которая принимает на вход число и выдаёт сумму цифр в числе.
//Code
Console.Write("Введите трехзначное число: ");
int number = int.Parse(Console.ReadLine()); // Считываем введенное число

int sum = 0; 

while (number > 0) 
{
    int digit = number % 10; // Получаем последнюю цифру нашего числа
    sum += digit; // добавляем к сумме
    number /= 10; // Удаляем последнюю цифру нашего числа
}

Console.WriteLine("Сумма цифр: " + sum); // Выводим сумму 
//END
//Zadanie 3: Напишите программу, которая задаёт массив из 8 элементов (от -10 до 10) и выводит их на экран. 
//Code
int[] array = {-10,-2,1,4,5,7,8,10}; 

for (int i = 0; i < array.Length; i++) 
{
    Console.Write(array[i] + " "); // Выводим элементы массива
}
//END

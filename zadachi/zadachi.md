// Задача 25: Напишите цикл, который принимает на вход два числа 
// (A и B) и возводит число A в натуральную степень B.
// 3, 5 -> 243 (3⁵)
// 2, 4 -> 16

// int a = ReadInt("Введите число A: ");
// int b = ReadInt("Введите число B: ");
// NumberDegree(a,b);
// void NumberDegree(int a, int b)
// {
//     int res = 1;
//     for (int i = 1; i <= b; i++)
//     {    
//         res = a * res;
//     }
//     Console.WriteLine(res);         
// }
// int ReadInt(string message)
// {
//     Console.Write (message);
//     return Convert.ToInt32(Console.ReadLine());
// }


// Задача 27: Напишите программу, которая принимает на 
// вход число и выдаёт сумму цифр в числе.
// 452 -> 11
// 82 -> 10
// 9012 -> 12

// Вариант 1:
//  int a = ReadInt("Введите число A: ");
//  int sum = 0;
//  while (a > 0)
//     { 
//         sum = sum + a % 10;
//         a = a /10 ; 
//     }
//  Console.WriteLine(sum);
//  int ReadInt(string message)
//  {
//     Console.Write (message);
//     return Convert.ToInt32(Console.ReadLine());
//  }

// Вариант 2:
//  int a = ReadInt("Введите число A: ");
//  string b = a.ToString();
//  int v = b.Length; 
//  SumNumber(a, v);
//  void SumNumber(int a, int v)
// {
//     int sum = 0;
//     for (int i = 1; i <= v; i++)
//     {
//         sum = sum + a % 10;
//         a = a / 10;
//     }
//     Console.WriteLine(sum);
// }
//  int ReadInt(string message)
//  {
//     Console.Write (message);
//     return Convert.ToInt32(Console.ReadLine());
//  }


// Задача 29: Напишите программу, которая задаёт 
// массив из 8 элементов и выводит их на экран.
// 1, 2, 5, 7, 19 -> [1, 2, 5, 7, 19]
// 6, 1, 33 -> [6, 1, 33]

// int lenArray = ReadInt("Введите длинну массива: ");
// int[] randomArray = new int[lenArray];
// for (int i = 0; i < randomArray.Length; i++)
// {
//     randomArray[i] = new Random().Next(1,100);
//     Console.Write(randomArray[i] + " ");
// }
// int ReadInt(string message)
// {
//     Console.Write(message);
//     return Convert.ToInt32(Console.ReadLine());
// }

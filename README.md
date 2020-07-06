# - Апроксимизация 
using System;

namespace ConsoleApp17
{
class Program
{
static void Main(string[] args)
{

Double c, num1, num2, num3, num4, num5, num6, num7, num8, num9, num10, num11, num12, num13, num14, num15, num16, num17, num18, num19, num20;
Console.WriteLine("Выберите количество переменных Х и У (от 5 до 10)");
c = Convert.ToDouble(Console.ReadLine());
if (c == 10)
{
Console.WriteLine("Введите значения столбца Х");
Console.WriteLine("x1");
num1 = Convert.ToDouble(Console.ReadLine());
Console.WriteLine("x2");
num2 = Convert.ToDouble(Console.ReadLine());
Console.WriteLine("x3");
num3 = Convert.ToDouble(Console.ReadLine());
Console.WriteLine("x4");
num4 = Convert.ToDouble(Console.ReadLine());
Console.WriteLine("x5");
num5 = Convert.ToDouble(Console.ReadLine());
Console.WriteLine("x6");
num6 = Convert.ToDouble(Console.ReadLine());
Console.WriteLine("x7");
num7 = Convert.ToDouble(Console.ReadLine());
Console.WriteLine("x8");
num8 = Convert.ToDouble(Console.ReadLine());
Console.WriteLine("x9");
num9 = Convert.ToDouble(Console.ReadLine());
Console.WriteLine("x10");
num10 = Convert.ToDouble(Console.ReadLine());

Console.WriteLine("Введите значения столбца Y");
Console.WriteLine("y1");
num11 = Convert.ToDouble(Console.ReadLine());
Console.WriteLine("y2");
num12 = Convert.ToDouble(Console.ReadLine());
Console.WriteLine("y3");
num13 = Convert.ToDouble(Console.ReadLine());
Console.WriteLine("y4");
num14 = Convert.ToDouble(Console.ReadLine());
Console.WriteLine("y5");
num15 = Convert.ToDouble(Console.ReadLine());
Console.WriteLine("y6");
num16 = Convert.ToDouble(Console.ReadLine());
Console.WriteLine("y7");
num17 = Convert.ToDouble(Console.ReadLine());
Console.WriteLine("y8");
num18 = Convert.ToDouble(Console.ReadLine());
Console.WriteLine("y9");
num19 = Convert.ToDouble(Console.ReadLine());
Console.WriteLine("y10");
num20 = Convert.ToDouble(Console.ReadLine());

const int N = 10;
double[] y = new double[N] { num1, num2, num3, num4, num5, num6, num7, num8, num9, num10 };
double[] x = new double[N] { num11, num12, num13, num14, num15, num16, num17, num18, num19, num20 };
double S1x = 0, S2y = 0, S3 = 0, S4 = 0;
for (int i = 0; i < N; ++i)
{
S1x += x[i];
S2y += y[i];
S3 += x[i] * y[i];
S4 += x[i] * x[i];
}
double a = (N * S3 - S1x * S2y) / (N * S4 - S1x * S1x);
double b = (S2y - a * S1x) / N;
Console.WriteLine("F=" + a + "*x+" + b);
}

else if (c == 9)

{
Console.WriteLine("Введите значения столбца Х");
Console.WriteLine("x1");
num1 = Convert.ToDouble(Console.ReadLine());
Console.WriteLine("x2");
num2 = Convert.ToDouble(Console.ReadLine());
Console.WriteLine("x3");
num3 = Convert.ToDouble(Console.ReadLine());
Console.WriteLine("x4");
num4 = Convert.ToDouble(Console.ReadLine());
Console.WriteLine("x5");
num5 = Convert.ToDouble(Console.ReadLine());
Console.WriteLine("x6");
num6 = Convert.ToDouble(Console.ReadLine());
Console.WriteLine("x7");
num7 = Convert.ToDouble(Console.ReadLine());
Console.WriteLine("x8");
num8 = Convert.ToDouble(Console.ReadLine());
Console.WriteLine("x9");
num9 = Convert.ToDouble(Console.ReadLine());

Console.WriteLine("Введите значения столбца Y");
Console.WriteLine("y1");
num11 = Convert.ToDouble(Console.ReadLine());
Console.WriteLine("y2");
num12 = Convert.ToDouble(Console.ReadLine());
Console.WriteLine("y3");
num13 = Convert.ToDouble(Console.ReadLine());
Console.WriteLine("y4");
num14 = Convert.ToDouble(Console.ReadLine());
Console.WriteLine("y5");
num15 = Convert.ToDouble(Console.ReadLine());
Console.WriteLine("y6");
num16 = Convert.ToDouble(Console.ReadLine());
Console.WriteLine("y7");
num17 = Convert.ToDouble(Console.ReadLine());
Console.WriteLine("y8");
num18 = Convert.ToDouble(Console.ReadLine());
Console.WriteLine("y9");
num19 = Convert.ToDouble(Console.ReadLine());

const int N = 9;
double[] y = new double[N] { num1, num2, num3, num4, num5, num6, num7, num8, num9, };
double[] x = new
 
double[N] { num11, num12, num13, num14, num15, num16, num17, num18, num19, };
double S1x = 0, S2y = 0, S3 = 0, S4 = 0;
for (int i = 0; i < N; ++i)
{

S1x += x[i];
S2y += y[i];
S3 += x[i] * y[i];
S4 += x[i] * x[i];
}
double a = (N * S3 - S1x * S2y) / (N * S4 - S1x * S1x);
double b = (S2y - a * S1x) / N;
Console.WriteLine("F=" + a + "*x+" + b);
}

else if (c == 8)
{
Console.WriteLine("Введите значения столбца Х");
Console.WriteLine("x1");
num1 = Convert.ToDouble(Console.ReadLine());
Console.WriteLine("x2");
num2 = Convert.ToDouble(Console.ReadLine());
Console.WriteLine("x3");
num3 = Convert.ToDouble(Console.ReadLine());
Console.WriteLine("x4");
num4 = Convert.ToDouble(Console.ReadLine());
Console.WriteLine("x5");
num5 = Convert.ToDouble(Console.ReadLine());
Console.WriteLine("x6");
num6 = Convert.ToDouble(Console.ReadLine());
Console.WriteLine("x7");
num7 = Convert.ToDouble(Console.ReadLine());
Console.WriteLine("x8");
num8 = Convert.ToDouble(Console.ReadLine());


Console.WriteLine("Введите значения столбца Y");
Console.WriteLine("y1");
num11 = Convert.ToDouble(Console.ReadLine());
Console.WriteLine("y2");
num12 = Convert.ToDouble(Console.ReadLine());
Console.WriteLine("y3");
num13 = Convert.ToDouble(Console.ReadLine());
Console.WriteLine("y4");
num14 = Convert.ToDouble(Console.ReadLine());
Console.WriteLine("y5");
num15 = Convert.ToDouble(Console.ReadLine());
Console.WriteLine("y6");
num16 = Convert.ToDouble(Console.ReadLine());
Console.WriteLine("y7");
num17 = Convert.ToDouble(Console.ReadLine());
Console.WriteLine("y8");
num18 = Convert.ToDouble(Console.ReadLine());


const int N = 8;
double[] y = new double[N] { num1, num2, num3, num4, num5, num6, num7, num8, };
double[] x = new double[N] { num11, num12, num13, num14, num15, num16, num17, num18, };
double S1x = 0, S2y = 0, S3 = 0, S4 = 0;
for (int i = 0; i < N; ++i)
{
S1x += x[i];
S2y += y[i];
S3 += x[i] * y[i];
S4 += x[i] * x[i];
}
double a = (N * S3 - S1x * S2y) / (N * S4 - S1x * S1x);
double b = (S2y - a * S1x) / N;
Console.WriteLine("F=" + a + "*x+" + b);
}

else if (c == 7)
{
Console.WriteLine("Введите значения столбца Х");
Console.WriteLine("x1");
num1 = Convert.ToDouble(Console.ReadLine());
Console.WriteLine("x2");
num2 = Convert.ToDouble(Console.ReadLine());
Console.WriteLine("x3");
num3 = Convert.ToDouble(Console.ReadLine());
Console.WriteLine("x4");
num4 = Convert.ToDouble(Console.ReadLine());
Console.WriteLine("x5");
num5 = Convert.ToDouble(Console.ReadLine());
Console.WriteLine("x6");
num6 = Convert.ToDouble(Console.ReadLine());
Console.WriteLine("x7");
num7 = Convert.ToDouble(Console.ReadLine());



Console.WriteLine("Введите значения столбца Y");
Console.WriteLine("y1");
num11 = Convert.ToDouble(Console.ReadLine());
Console.WriteLine("y2");
num12 = Convert.ToDouble(Console.ReadLine());
Console.WriteLine("y3");
num13 = Convert.ToDouble(Console.ReadLine());
Console.WriteLine("y4");
num14 = Convert.ToDouble(Console.ReadLine());
Console.WriteLine("y5");
num15 = Convert.ToDouble(Console.ReadLine());
Console.WriteLine("y6");
num16 = Convert.ToDouble(Console.ReadLine());
Console.WriteLine("y7");
num17 = Convert.ToDouble(Console.ReadLine());



const int N = 7;
double[] y = new double[N] { num1, num2, num3, num4, num5, num6, num7 };
double[] x = new double[N] { num11, num12, num13, num14, num15, num16, num17 };
double S1x = 0, S2y = 0, S3 = 0, S4 = 0;
for (int i = 0; i < N; ++i)
{
S1x += x[i];
S2y += y[i];
S3 += x[i] * y[i];
S4 += x[i] * x[i];
}
double a = (N * S3 - S1x * S2y) / (N * S4 - S1x * S1x);
double b = (S2y - a * S1x) / N;
Console.WriteLine("F=" + a + "*x+" + b);
}

else if (c == 6)
{
Console.WriteLine("Введите значения столбца Х");
Console.WriteLine("x1");
num1 = Convert.ToDouble(Console.ReadLine());
Console.WriteLine("x2");
num2 = Convert.ToDouble(Console.ReadLine());
Console.WriteLine("x3");
num3 =
 
Convert.ToDouble(Console.ReadLine());
Console.WriteLine("x4");
num4 = Convert.ToDouble(Console.ReadLine());
Console.WriteLine("x5");
num5 = Convert.ToDouble(Console.ReadLine());
Console.WriteLine("x6");
num6 = Convert.ToDouble(Console.ReadLine());



Console.WriteLine("Введите значения столбца Y");
Console.WriteLine("y1");
num11 = Convert.ToDouble(Console.ReadLine());
Console.WriteLine("y2");
num12 = Convert.ToDouble(Console.ReadLine());
Console.WriteLine("y3");
num13 = Convert.ToDouble(Console.ReadLine());
Console.WriteLine("y4");
num14 = Convert.ToDouble(Console.ReadLine());
Console.WriteLine("y5");
num15 = Convert.ToDouble(Console.ReadLine());
Console.WriteLine("y6");
num16 = Convert.ToDouble(Console.ReadLine());
;


const int N = 6;
double[] y = new double[N] { num1, num2, num3, num4, num5, num6 };
double[] x = new double[N] { num11, num12, num13, num14, num15, num16 };
double S1x = 0, S2y = 0, S3 = 0, S4 = 0;
for (int i = 0; i < N; ++i)
{
S1x += x[i];
S2y += y[i];
S3 += x[i] * y[i];
S4 += x[i] * x[i];
}
double a = (N * S3 - S1x * S2y) / (N * S4 - S1x * S1x);
double b = (S2y - a * S1x) / N;
Console.WriteLine("F=" + a + "*x+" + b);
}

else if (c == 5)
{
Console.WriteLine("Введите значения столбца Х");
Console.WriteLine("x1");
num1 = Convert.ToDouble(Console.ReadLine());
Console.WriteLine("x2");
num2 = Convert.ToDouble(Console.ReadLine());
Console.WriteLine("x3");
num3 = Convert.ToDouble(Console.ReadLine());
Console.WriteLine("x4");
num4 = Convert.ToDouble(Console.ReadLine());
Console.WriteLine("x5");
num5 = Convert.ToDouble(Console.ReadLine());


Console.WriteLine("Введите значения столбца Y");
Console.WriteLine("y1");
num11 = Convert.ToDouble(Console.ReadLine());
Console.WriteLine("y2");
num12 = Convert.ToDouble(Console.ReadLine());
Console.WriteLine("y3");
num13 = Convert.ToDouble(Console.ReadLine());
Console.WriteLine("y4");
num14 = Convert.ToDouble(Console.ReadLine());
Console.WriteLine("y5");
num15 = Convert.ToDouble(Console.ReadLine());



const int N = 5;
double[] y = new double[N] { num1, num2, num3, num4, num5 };
double[] x = new double[N] { num11, num12, num13, num14, num15 };
double S1x = 0, S2y = 0, S3 = 0, S4 = 0;
for (int i = 0; i < N; ++i)
{
S1x += x[i];
S2y += y[i];
S3 += x[i] * y[i];
S4 += x[i] * x[i];
}
double a = (N * S3 - S1x * S2y) / (N * S4 - S1x * S1x);
double b = (S2y - a * S1x) / N;
Console.WriteLine("F=" + a + "*x+" + b);
}
}
}
}

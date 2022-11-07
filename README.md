# clangua
using System;

namespace ConsoleApp1
{
    class Program
    {
        static void Main(string[] args)
        {

            /*
            Console.Write("Введите трехзначное число по цифре за раз: ");///зд1
            int[] values;
            values = new Int32[3];

            for (int i = 0; i < values.Length; i++)
            {
                values[i] = Convert.ToInt32(Console.ReadLine());


            }
            Console.WriteLine("Число посередине :{0} ", values[1]);
            */
            /*
            Console.Write("Генерируем ваше рандомное число:\n ");  ///зд2
            int[] values;
            values = new Int32[3];
            for (int i = 0; i < values.Length; i++)
            {
                Random rnd = new Random();
                values[i] = rnd.Next(1,9);


            }
            Console.WriteLine("\n полное число :{0} {1} {2} \n", values[0], values[1], values[2]);
            Console.WriteLine("\n числа с краев :{0} {1} \n", values[0],values[1]);

             */
            /*
           Console.Write("введите максимальную длинну числа:\n ");///зд3
           int[] values;

           int x = Convert.ToInt32(Console.ReadLine());

           Console.Write("Введите трехзначное число по цифре за раз:\n ");
           values = new Int32[x];

           for (int i = 0; i < values.Length; i++)
           {
               values[i] = Convert.ToInt32(Console.ReadLine());


           }
           if (x < 3)
           {
               Console.Write("Третьей цифры нет! \n ");
           }
           else
           {
               Console.WriteLine("\n третье число :{0} \n", values[2]);
           }
           */
            Console.Write("введите день недели что бы проверить на выходной :\n ");///зд4
            

            int vubor = Convert.ToInt32(Console.ReadLine());

            if(vubor == 6 || vubor==7)
            {
                Console.WriteLine("\n Этот день выходной! \n");
            }
            else
            {
                Console.WriteLine("\n Этот день рабочий! \n");
            }


        }


    }
}

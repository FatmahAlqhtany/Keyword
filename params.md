<div dir="rtl">



## المفهوم 

`params`
تقوم كلمه params بتحديد عدد متغير من الـ paramerter 
 
## المثال
يوضح المثال التالي استخدام كلمة `params`:
</div>

```C#
   public static void Myparams (params string [] MyList)
            {
                for(int i = 0; i<MyList.Length; i++)
                {
                    Console.Write(MyList[i] + " ");
                }
                Console.WriteLine();
            }

            Myparams("fatimah ", "Abdulaziz", "Alqhtany ");

```

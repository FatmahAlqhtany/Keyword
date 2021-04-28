<div dir="rtl">



## المفهوم 
تقوم كلمة
`params`
تقوم كلمة params بتحديد paramerter تاخذ عدد متغير من الـ arguments ويجب ان تكون احاديه الابعاد
## المثال
يوضح المثال التالي كفية إستخدام كلمة `params`:
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

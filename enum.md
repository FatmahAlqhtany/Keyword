<div dir="rtl">



## المفهوم 
تقوم كلمة
`enum `.

هو مجموعة من ثوابت الأعداد الصحيحة يتم التصريح عن نوع تم تعداده باستخدام الكلمة الأساسية للتعداد. يحتوي التعداد على قيمه الخاصة


## المثال

يوضح المثال التالي استخدام كلمة `enum `:

</div>

  

```C#

public  enum  Day {

SUNDAY, MONDAY, TUESDAY, WEDNESDAY,

THURSDAY, FRIDAY, SATURDAY

}
static  void  Main(string[] args) {
int  WeekdayStart = (int)Day.MONDAY;
int  WeekdayEnd = (int)Day.FRIDAY;
Console.WriteLine("Monday: {0}", WeekdayStart);
Console.WriteLine("Friday: {0}", WeekdayEnd);
}

  

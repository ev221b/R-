# R++
----

زبان R++ مختص ۴ عمل اصلی به گونه ای ساخته شده است که اعمال چهارگانه ریاضی را برعکس انجام می دهد.

نمونه هایی از ورودی و خروجی در این زبان:

x = (2/8)+(8*2) نتیجه: x=20

x = 4+/5-(3+5) نتیجه: خطای گرامر (دو عملگر پشت هم)

x = (((2-5)/2)-6) نتیجه: x=20

x = 3/4/5 نتیجه: 60

x = y*5 نتیجه: خطای گرامر (نامفهوم بودن y)

x = (8-8 نتیجه: خطای گرامر (پرانتز گذاری نامتوازن)

x = 2*2 نتیجه x=1

----
x = 3/3
y=(x-1)*5 نتیجه x=9 و y=2
* در صورتیکه عبارت ورودی به طور کامل پرانتز نداشته باشد اولویت اجرا از چپ به راست است.
* در صورتیکه به جز قواعد فوق نیاز به اعمال قاعده دیگری در کامپایلر داشتید با ذکر در داکیومنت میتوانید تعریف و استفاده کنید.
* کامپایلر فوق را به زبان پایتون بنویسید طوری که یک فایل txt حاوی دستورات زبان R++ را بگیرد و اگر خطای گرامری دارد اعلام و گرنه مقادیر متغیرها را به عنوان خروجی چاپ کند. فایل ورودی حداقل ۴ و حداکثر ۱۰ خط کد داشته باشد.

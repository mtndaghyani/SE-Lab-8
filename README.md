# SE-Lab-8

سناریو اول:

![image](https://github.com/mtndaghyani/SE-Lab-8/assets/59438691/39605088-9c66-4226-868f-9df13c04da9c)


![8](https://github.com/mtndaghyani/SE-Lab-8/assets/63471751/84acd0da-c89b-43ae-a773-3eb7089c2001)

![10](https://github.com/mtndaghyani/SE-Lab-8/assets/63471751/cf44f003-a67f-4635-80c6-b58c3d51ef73)

![image](https://github.com/mtndaghyani/SE-Lab-8/assets/59438691/8e1e4db3-b284-49f1-a6fa-54b362b83542)


بهبود فایل JavaCup:
سپس عملکرد تابع temp را به گونه‌ای تغییر می‌دهیم که میزان مصرف منابع را به حداقل برسانیم. ابتدا الگوریتم تابع را بررسی می‌کنیم. همانطور که مشاهده می‌شود، این تابع هرکدام از اعداد 0 تا 9999 را با اعداد 0 تا 19999 جمع می‌کند. پس از کمی تحلیل، مشاهده می‌شود که اعداد حاصل به صورت زیر هستند:

هرکدام از اعداد 0 تا 9998 و 20000 تا 29998، به طور یک به یک (0 با 29998، 1 با 29997 و …) تعداد برابری در لیست دارند، و تعداد اعداد 0 تا 9998، برابر یکی بیشتر از مقدار آنهاست (تعداد 0 یکی، تعداد 1 دوتا و …)
هر کدام از اعداد 9999 تا 19999 نیز، 10هزاربار تکرار شده‌اند. در نتیجه، یک لول از بهینه سازی این است که به جای sum، هر عدد را به اندازه لازم تکرار کنیم. در گام بعد باید این اعداد را در یک لیست قرار دهیم. اگر از ArrayList استفاده می‌کردیم، هزینه مرج کردن این اعداد بسیار زیاد می‌گشت، به گونه‌ای که از هزینه الگوریتم اولیه نیز بیشتر می‌شد. در این قسمت، به جای استفاده از ArrayList، از LinkedList استفاده می‌کنیم. در این صورت تنها با وصل کردن تعدادی پوینتر به هم، لیست جدید را می‌سازیم و هزینه مصرف منابع با این روش به طور چشم‌گیری کاهش می‌یابد. 

![image](https://github.com/mtndaghyani/SE-Lab-8/assets/59438691/c2556f91-8a3f-481e-a4dd-cbd6994beca9)
![image](https://github.com/mtndaghyani/SE-Lab-8/assets/59438691/cd1af8bc-a6fa-41cb-b93f-756f0aa03b49)
![image](https://github.com/mtndaghyani/SE-Lab-8/assets/59438691/2e4b3c08-637d-413b-a51b-6b801d469b43)
![image](https://github.com/mtndaghyani/SE-Lab-8/assets/59438691/ddaad4da-c2d7-418d-879b-4db0a91dbfe5)





سناریو دوم:
روش غیر بهینه:


![1](https://github.com/mtndaghyani/SE-Lab-8/assets/63471751/05f20cfa-58ac-4b43-a9d9-c0778021dc46)

![2](https://github.com/mtndaghyani/SE-Lab-8/assets/63471751/c8ccb20e-7d9e-4fe7-b21e-eecff2770620)

![3](https://github.com/mtndaghyani/SE-Lab-8/assets/63471751/2d0a3338-e82d-496c-b94f-9066eb22defa)

روش بهتر شده:

![4](https://github.com/mtndaghyani/SE-Lab-8/assets/63471751/512cdbdf-c20b-43dc-b49b-e843b4b7389b)

![5](https://github.com/mtndaghyani/SE-Lab-8/assets/63471751/edada909-d04c-41f4-868e-f5218ac414ce)

![6](https://github.com/mtndaghyani/SE-Lab-8/assets/63471751/a014bcd7-de2f-4683-b0fb-7f150ac56774)





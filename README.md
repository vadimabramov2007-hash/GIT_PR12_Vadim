# GIT_PR12_Vadim
> [!NOTE]
:hand: _Меня зовут **Абрамов Вадим Артурович** я студент группы ИС-23Б_\
~~Учусь уже на третьм курсе~~ :muscle:\
Вот мой профиль на **GitHub** 
> [vadimabramov2007-hash](https://github.com/vadimabramov2007-hash "Ссылка на мою страницу GitHub")

У меня на этой страничке есть несколько работ по _**Инструментальным средствам** МДК 02.02_ :sunglasses:

+ [ПР07](https://github.com/vadimabramov2007-hash/GIT_PR07_Vadim)

+ [ПР10](https://github.com/vadimabramov2007-hash/GIT_PR10_Abramov)

+ [megasupersite](https://github.com/vadimabramov2007-hash/megasupersite)

*~~Ну и еще парочку, если интересно - чекните~~*

|Номер|Название|Оценка|
|:-|:-:|-:|
|1|Химия|5|
|2|Биология|5|
|3|Физра|5|
|4|История|5|
|5|Математика|5|
|6|Русский|5|

> [!IMPORTANT]
> **Пример простенького кода на C#**

![C#](https://www.google.com/url?sa=i&url=https%3A%2F%2Fwww.jetbrains.com%2Fguide%2Fdotnet%2Ftechnologies%2Fcsharp%2F&psig=AOvVaw2Dddy-0vm8skR2EP9KXJA_&ust=1764253658331000&source=images&cd=vfe&opi=89978449&ved=0CBUQjRxqFwoTCIiiwJuDkJEDFQAAAAAdAAAAABAE)

```csharp
    Console.WriteLine("Задание 1");
M1:
    try
    {
        int a = 0;
        Console.WriteLine("Введите число:");
        a = Convert.ToInt32(Console.ReadLine());
        if (a > 99 && a < 999 && a % 2 != 0)
        {
            Console.WriteLine("Истина: нечетное положительное трехзначное число");
        }
        else
        {
            Console.WriteLine("Ложь");
        }
    }
    catch (System.FormatException ex1)
    {
        Console.WriteLine("Ошибка! Вы ввели не число {0}", ex1.Message.ToString());
        goto M1;
    }
    catch (System.OverflowException ex2)
    {
        Console.WriteLine("Переполнение! Значение большое! {0}", ex2.Message.ToString());
        goto M1;
    }
```

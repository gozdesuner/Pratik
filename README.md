```csharp 
 using System;

class program
{
    static void Main()
    {
        Console.WriteLine("Lütfen bir sayı giriniz:");
        string metin = Console.ReadLine();
        int sayi;
        if (int.TryParse(metin, out sayi))
        {
            if (sayi > 10)
            {
                Console.WriteLine("Girilen sayı 10'dan büyüktür.");
            }
            else if (sayi < 10)
            {
                Console.WriteLine("Girilen sayı 10'dan küçüktür.");
            }
            else
            {
                Console.WriteLine("Sayı 10'dur.");
            }
            if (sayi % 2 == 0)
            {
                Console.WriteLine("Sayı çifttir.");
            }
            else
            {
                Console.WriteLine("Sayı tektir.");
            }
        }
    }
}

```


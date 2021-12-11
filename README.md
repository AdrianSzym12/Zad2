# Zad2
{           ulong a= 9;
            ulong b = 20;
            ulong c = 243;
            ulong wynika = a;
            ulong wynikb = b;
            ulong wynikc = c;

            for(ulong i=1; i < a; i= i+1)
            {
                wynika = wynika * (a - i);
                wynikb = wynikb * (b - i);
                wynikc = wynikc * (c - i);

            }
            Console.WriteLine("Wynik 9!= "+ wynika);
            Console.WriteLine("Wynik 20!= " + wynikb);
            Console.WriteLine("Wynik 243!= " + wynikc);

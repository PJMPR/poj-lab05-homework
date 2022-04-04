# Zadanie (rozszerzenie zadania z labratorium 5)

System bankowy pozwala na zlecenie operacji bankowych na rachunku klienta.
Do takich operacji należą:
* wpłata środków na konto - możliwe zawsze
* wypłata środków z konta - możliwe gdy na koncie jest wystarczająca ilość środków
* wykonanie przelewu z konta na konto - możliwe gdy na koncie jest wystarczająca ilość środków
    + przelewy wykonywane są 2 razy dziennie

Każda taka operacja jest odkładana w historii rachunku bankowego, bądź rachunków w przypadku transferu środków.
Klient banku może przeglądać historię swojego konta z wybranego przedziału czasowego.

Zaprojektuj zestaw klas, które będą modelowały zachowanie historii rachunku bankowego oraz napisz logikę, dzięki której będzie można wybrać logi historii z dowolnego przedziału czasowego.



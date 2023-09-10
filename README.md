# TASK 1
---
## Subtask 1
### 10/10 💪💪💪 💅

## Subtask 3 
### Dlaczego zdecydowałam się wziąć udział w challenge portfolio?

#### *Od dawna chciałam wziąć udział w challengu na testowanie manualne. Jednak pierwszy dostępny nabór był do testowania automatycznego, więc ten skończyłam najpierw.* 😉 *Bardzo spodobało mi się wyzwanie, chciałabym pogłębić swoją wiedzę i wzbogacić portfolio. Na aktualnym stanowisku zajmuję się trochę testowaniem, jednak nigdy nie miałam przygotowania teoretycznego, więc z ogromnym entuzjazmem podchodzę do nauki. Chciałabym się rozwijać w tym kierunku i przejść na stanowisko na którym wszystkie moje obowiązki skupiają się na testowaniu.* 🤓

---
## Subtask 4
* Na czym polega ta aplikacja? Do czego służy?
    * Aplikacja zbiera informacje o piłkarzach nożnych oraz o odbytych rozgrywkach piłkarskich. Ma za zadanie ułatwienie wyszukania obiecujących młodych zawodników dla klubów piłkarskich. 

* Jakie funkcjonalności znajdują się w aplikacji? Do czego służą. Czy są intuicyjne, czy może byś coś zmienił_a? (Nie bój się wyrażać opinię!)
    * przyciskiem "Add player" możemy dodać nowego zawodnika do systemu, podając wiele szczegółów, które mogą być istotne dla klubów (tj. data urodzenia, doświadczenie, noga prowadząca zawodnika itd). Brakuje mi tu pewnych funkcjonalności lub ograniczeń w istniejącym formularzu dodania nowego zawodnika (np. ograniczenie liczby znaków w nazwie klubu, pozycji, i innych pól, które z domysłu powinny być określone maksymalnie trzema słowami).
    * W formularzu "add player" przydałoby się pole na dodatkowe komentarze, by nadrobić określoną liczbę znaków w niektórych polach. 
    * Mamy dostęp do bazy wszystkich dodanych do aplikacji zawodników (znajdziemy ich w zakładce "players"). Dane możemy przefiltrować (szukając np. zawodników z konkretnego klubu, w określonym wieku), lub posortować (wg. imienia, nazwiska, klubu, pozycji, ratingu). Niestety nie ma możliwości sortowania po numerze odbytych meczów lub numerze istniejących raportów.
    * Istnieje możliwość zmiany języka (PL<>EN) oraz wylogowania się.
    * Aplikacja pozwala nam na otwarcie ostatnio dodanego i zakualizowanego zawodnika, ostatnio dodanego i zaktualizowanego meczu i ostatniego zaktualizowanego raportu (brakuje więc konsystencji, przydałby się też ostatnio utworzony raport)
    * Link do kontaktu z deweloperami, który przekierowuje nas do kanału na slacku. 

* Oceń interfejs aplikacji (wygląd) – czy Ci się podoba, czy nie?
    * Wygląda uporządkowanie i estetycznie. Mnie się podoba. :)

* Czy aplikacja jest intuicyjna? (Intuicyjna, czyli np. nie masz problemu ze zrozumieniem, co należy kliknąć, żeby wejść do formularza dodawania nowego zawodnika piłki nożnej do systemu).
    * Wg mnie jest intuicyjna, jednak brakuje mi pewnych funckjonalności. Np. w //main/div[2] znajdują się 4 zakładki, które informują nas o ilości graczy w aplikacji, meczów, raportów, wydarzeń, lecz nie są one klikalne, a intuincja podpowiada, że powinny być. Dodatkowo na stronie nie mogę znaleźć miejsca w którym mogłabym wyświelić wszyskie raporty, mecze i eventy, taka opcja istnieje tylko dla zawodników. Dodatkowo wydaje mi się, że sekcja "Shortcuts" (//div[3]/div[2]/div/div), jest niedopracowana. Jedyną opcją w tej sekcji jest dodanie nowego zawodnika, więc najlepiej by było nazwać tę sekcję "Zawodnicy" i umieścić tam opcję dodania nowego zawodnika (//div[2]/div/div/a/button) oraz opcję wyświetlenia wszystkich (//ul[1]/div[2]/div[2]), który aktualnie znajduje się w liście po lewej stronie.
    * [UPDATE]: Jednak mamy możliwość wyświetlenia meczy i raportów, jednak droga tam jest bardzo skomplikowana... :) Wydaje się to być możliwe jedynie po wyświetleniu ostatnio dodanego/zaktualizowanego zawodnika/meczu/raportu z sekcji "Activity". 

* Czy zauważasz jakieś błędy? Albo coś wydaje Ci się błędem? Zapisz swoje przemyślenia w pliku. Tutaj masz na to miejsce, czas i przestrzeń! ;)
    * Tłumaczenie zakładki "shortcuts" (//div[2]/div/div/h2) po polsku tłumaczy się na "Linki pomocnicze", uważam, że jest to nieprawidłowe tłumaczenie (chociaż to zależy jaki jest zamysł tej zakładki, opisałam już ten problem w podpunkcie wyżej).
    * Klikając na ostatnio dodany/aktualizowany mecz/zawodnik/raport w sekcji "Activity" (//div[3]/div[3]/div) mamy możlwość edycji danego rekordu, a nie tylko wyświetlenie szczegółów, nie wydaje mi się to poprawne.
    * "Mecze" i "Raporty" nie wyświetlają się w menu po lewej stronie (jedynie po kliknięciu ostatnio dodanego/zaktualizowanego zawodnika/meczu/raportu z sekcji "Activity")

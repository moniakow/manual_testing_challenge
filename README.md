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

---
# TASK 2

## Subtask 1 : Test Cases based on User Stories
https://docs.google.com/spreadsheets/d/1ImCItmukbeS-AvDGWTX-eeJze1goA_HZH4wVOpHmUdE/edit?usp=sharing

## Subtask 2: Test Cases 
https://docs.google.com/spreadsheets/d/1R0_Itc__Yf_gVgWW2AyZdKfsSYxe1bzkEYqts5zTXME/edit?usp=sharing

## Subtask 3: Why do we write test cases?
* We write test cases to document that new development works as requested by the client.
* To manage testing. Test cases can be distributed among the team. The person performing the test does not need to be the one who designed the test, but with a test case should be able to easily perform all required tests.
* To be able to prepare a detailed test report.
* Might help us to think ahead where possible bugs could appear.

  ---
# TASK 3

## Subtask : Bug Report
  https://drive.google.com/drive/folders/14g2Hs4oCHaIr5Y1YTQ2IHVJleJ4EKuBb?usp=sharing

## Subtask : Test Report
  https://docs.google.com/presentation/d/1WOg5Z-CRFK7VaRjeRKEy8RWHhaLQMf5kN1PSM1Q4QiA/edit?usp=sharing

---
# TASK 4 

## Subtask: Testowanie aplikacji mobilnych - Bug Report
   https://docs.google.com/spreadsheets/d/1RrG41au7ZqUI3FL6aqlcD-TpXslwPCs1QzaTiLuHscU/edit?usp=sharing

## Subtask: Q&A 
   * **Do czego służy ta aplikacja? Jaki jest cel tej aplikacji?**
      * Aplikacja umożliwia udostępnienie ogłoszeń lokalnych (sprzedaż, oddam za darmo, wynajmę, dam pracę, itd.) oraz wyszukiwanie takich samych ogłoszeń. Aplikacja umożliwia zalogowanie do platformy, udostępnianie ogłoszeń, wgląd do statystyk wystawionego ogłoszenia, wyszukiwanie ogłoszeń w wybranych miejscach, kontakt z wystawiającym, zakup przez ptalformę, płatność. Ustawianie alertów na dane wyszukiwania. 
   * **Kto ma być użytkownikiem końcowym aplikacji?**
      * Ludzie, którzy szukają wszelkich ogłoszeń lokalnych lub chcą coś ogłosić.
        
   * **Czy według Ciebie aplikacja jest user friendly? (Przyjazna dla użytkownika- np. wchodzisz do aplikacji i szybko łapiesz do czego służą przyciski. Poczytaj na ten temat w internecie- co to znaczy, że aplikacja jest przyjazna dla użytkownika)**
        * Uważam, że aplikacja jest bardzo przyjazna użytkownikowi. Menu znajduje się na dole, blisko kciuka, ikony są przejrzyste. Łatwo się w niej odnaleźć.

   * **Jak byś usprawnił aplikację? Co byś w niej poprawił. Czy masz jakiś pomysł na dodatkową funkcjonalność?**
        * W aplikacji poprawiłabym zgłoszone bugi. :) z możliwych dodatkowych funkcji, fajnie by było jakby była jakaś strefa NGO: gdzie lokalne fundacje i stowarzyszenia mogłyby wrzucać zapotrzebowanie na darowizny materialne / wsparcie finansowe.  Połączenie "szukam/oddam". Jeśli ktoś oddaje jakiś przedmiot za darmo, op wstawieniu ogłoszenia aplikacja by mogła szukać ogłoszeń "szukam" które by się pokrywały i umożliwić i zautomatyzować pozbycie się rzeczy za darmo. :)

   * **Jakie dostrzegasz różnice pomiędzy testowaniem aplikacji internetowej, a natywnej?**
         * testowanie aplikacji natywnej skupia się na testowaniu funkcjonalności danej aplikacji na konkretnym rodzaju urządzenia. Możemy do tego użyć prawdziwego urządzenia mobilnego, bądź skorzystać ze specjalnego emulatora.  

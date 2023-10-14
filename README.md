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

---
# TASK 5 - SQL 1
## Subtask 3 

* **Wyświetl tabelę actors w kolejności alfabetycznej sortując po kolumnie surname.**
    
   * SELECT * FROM `actors` order by name  
       
   ![image](https://github.com/moniakow/manual_testing_challenge/assets/18737946/a5ee5011-a6a7-49b7-a480-b6d4d97f9041)  

* **Wyświetl film, który powstał w 2019 roku.**

  SELECT * FROM `movies` WHERE year_of_production=2019

   ![image](https://github.com/moniakow/manual_testing_challenge/assets/18737946/1e9a1b2e-cd73-4695-a377-d0d0e7cafa3c)  

* **Wyświetl wszystkie filmy, które powstały między 1900, a 1999 rokiem.**

  SELECT * FROM `movies` WHERE `year_of_production` BETWEEN 1990 and 1999

    ![image](https://github.com/moniakow/manual_testing_challenge/assets/18737946/89568c3e-c088-44a9-99c1-b3c017435c1a)  

* **Wyświetl JEDYNIE tytuł i cenę filmów, które kosztują poniżej 7$**

  SELECT `title`,`price` FROM `movies` WHERE `price` <7;

   ![image](https://github.com/moniakow/manual_testing_challenge/assets/18737946/d4055a20-0529-4738-9f86-4d79eb7ff42d)

* **Użyj operatora logicznego AND, aby wyświetlić aktorów o actor_id pomiędzy 4-7 (4 i 7 powinny się wyświetlać). NIE UŻYWAJ operatora BETWEEN.**

   SELECT * FROM actors where actor_id>3 and actor_id<8;

    ![image](https://github.com/moniakow/manual_testing_challenge/assets/18737946/6ba3b00f-57e9-4e89-994d-4cfa96613ba3)
  
* **Wyświetl klientów o id 2,4,6 wykorzystaj do tego warunek logiczny.**

    SELECT * FROM `customers` where customer_id=2 or customer_id=4 OR customer_id=6;

     ![image](https://github.com/moniakow/manual_testing_challenge/assets/18737946/26bd794d-ae1c-4407-b63d-1b1fefdacc88)
    
* **Wyświetl klientów o id 1,3,5 wykorzystaj do tego operator IN.**

    SELECT * FROM `customers` WHERE customer_id IN (1,3,5)

    ![image](https://github.com/moniakow/manual_testing_challenge/assets/18737946/8b87c565-d76b-435e-92ea-5b0f0cfaa8a2)
  
* **Wyświetl dane wszystkich osób z tabeli ‘actors’, których imię zaczyna się od ciągu “An”.**

    SELECT * FROM actors WHERE name like 'an%'

    ![image](https://github.com/moniakow/manual_testing_challenge/assets/18737946/de2e4799-a10a-409e-84a3-bd00ed781033)
    
* **Wyświetl dane klienta, który nie ma podanego adresu email.**

    SELECT * FROM `customers` WHERE email IS null  

     ![image](https://github.com/moniakow/manual_testing_challenge/assets/18737946/7ef34cde-9153-4b6c-9bf2-e6e89ae6cd15)

* **Wyświetl wszystkie filmy, których cena wynosi powyżej 9$ oraz ich ID mieści się pomiędzy 2 i 8 movie_id.**

    SELECT * FROM `movies` WHERE price>9 AND movie_id>1 AND movie_id<9;

    ![image](https://github.com/moniakow/manual_testing_challenge/assets/18737946/1fe2e350-16b6-4062-9146-c42e63880100)
  
---
# TASK 6 
## Subtask 1 - SQL 2

*  **Popełniłam błąd wpisując nazwisko Ani Miler – wpisałam Muler. Znajdź i zastosuj funkcję, która poprawi mój błąd.**
     
   ```
   UPDATE customers
   SET surname = 'Miler'
   WHERE surname = 'Muler'
   ```

   ![image](https://github.com/moniakow/manual_testing_challenge/assets/18737946/d36ecba5-1812-41b3-8bcf-0aca0622b2f0)


* **Pobrałam za dużo pieniędzy od klienta, który kupił w ostatnim czasie film o id 4. Korzystając z funkcji join sprawdź, jak ma na imię klient i jakiego ma maila. W celu napisania mu wiadomości o pomyłce fantastycznej szefowej.**

   ```
   SELECT customers.name, customers.email, sale.movie_id 
   FROM `customers` 
   LEFT JOIN sale 
   ON customers.customer_id = sale.customer_id 
   WHERE movie_id = 4 

![image](https://github.com/moniakow/manual_testing_challenge/assets/18737946/7d669523-d86d-4c92-8d1f-01c2a7958a82)  

* **Na pewno zauważył_ś, że sprzedawca zapomniał wpisać emaila klientce Patrycji. Uzupełnij ten brak wpisując: pati@mail.com**

   ```
   UPDATE customers
   SET email = 'pati@mail.com'
   WHERE surname = 'Komor'
   SELECT * FROM customers  

![image](https://github.com/moniakow/manual_testing_challenge/assets/18737946/583bc674-400f-42a0-88ca-1d8cff4ba11c)  

* **Dla każdego zakupu wyświetl, imię i nazwisko klienta, który dokonał wypożyczenia oraz tytuł wypożyczonego filmu. (wykorzystaj do tego funkcję inner join, zastanów się wcześniej, które tabele Ci się przydadzą do wykonania ćwiczenia).**

    ```
   SELECT customers.name, customers.surname,sale.sale_date, movies.title
   FROM ((customers INNER JOIN sale on customers.customer_id = sale.customer_id) INNER JOIN movies ON movies.movie_id = sale.movie_id)
    ```
  ![image](https://github.com/moniakow/manual_testing_challenge/assets/18737946/75f7fca0-002c-4412-9e90-e11b024d1075)

* **W celu anonimizacji danych, chcesz stworzyć pseudonimy swoich klientów. - Dodaj kolumnę o nazwie ‘pseudonym’ do tabeli customer,- Wypełnij kolumnę w taki sposób, aby pseudonim stworzył się z dwóch pierwszych liter imienia i ostatniej litery    nazwiska. Np. Natalie Pilling → Nag**
    
  ```
   ALTER TABLE customers
   ADD COLUMN pseudonym varchar(3)
   ***
   UPDATE customers 
   SET pseudo2 = CONCAT(LEFT(name, 2), RIGHT(surname,1))  
  ```
  ![image](https://github.com/moniakow/manual_testing_challenge/assets/18737946/ebee26b1-5334-40d2-a10d-ed0f10a22722)

  
* **Wyświetl tytuły filmów, które zostały zakupione, wyświetl tabelę w taki sposób, aby tytuły się nie powtarzały.**
  
  ```
  SELECT DISTINCT title
  FROM movies INNER JOIN sale ON movies.movie_id = sale.movie_id
  ```
  ![image](https://github.com/moniakow/manual_testing_challenge/assets/18737946/ce48e2f2-cd91-4937-97b0-9108fa25ca73)

  
* **Wyświetl wspólną listę imion wszystkich aktorów i klientów, a wynik uporządkuj alfabetycznie. (Wykorzystaj do tego funkcji UNION)**

  ```
  SELECT name FROM customers 
  UNION
  SELECT name FROM actors
  ORDER BY name ASC;
  ```

  ![image](https://github.com/moniakow/manual_testing_challenge/assets/18737946/90e87e80-197b-4244-a8cb-889c19724b08)

* **Polskę opanowała inflacja i nasz sklepik z filmami również dotknął ten problem. Podnieś cenę wszystkich filmów wyprodukowanych po 2000 roku o 2,5 $ (Pamiętaj, że dolar to domyślna jednostka- nie używaj jej nigdzie).**
   ```
   UPDATE movies
   SET price = price + 2.5 WHERE year_of_production > 2000
   ```
 ![image](https://github.com/moniakow/manual_testing_challenge/assets/18737946/92f0eb6e-4df8-4a14-8d28-c6573d1080cb)
 ![image](https://github.com/moniakow/manual_testing_challenge/assets/18737946/f086d125-30a9-460d-b192-95f3d469e91a)

  
* **Wyświetl imię i nazwisko aktora o id 4 i tytuł filmu, w którym zagrał**

   ```
   SELECT actors.name, actors.surname, movies.title 
   FROM ((cast INNER JOIN actors ON cast.actor_id = actors.actor_id) INNER JOIN movies ON cast.movie_id = movies.movie_id) WHERE movies.movie_id = 4
  ```
   ![image](https://github.com/moniakow/manual_testing_challenge/assets/18737946/bb0391c4-7a05-46a3-8fd4-2070b47dcf27)
  
* **A gdzie nasza HONIA!? Dodaj do tabeli customers nową krotkę, gdzie customer_id = 7, name = Honia, surname = Stuczka-Kucharska, email = honia@mail.com oraz pseudonym = Hoa**
  
  ```
   INSERT INTO customers (customer_id, name, surname, email, pseudonym)
   VALUES ('7', 'Honia', 'Stuczka-Kucharska', 'honia@mail.com', 'Hoa')
  ```
  ![image](https://github.com/moniakow/manual_testing_challenge/assets/18737946/3830c731-b01c-43e5-8a8e-feb6a388bf7d)

    

    

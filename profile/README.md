# Book Review Service

## Zespół

* [Michał Wójcik](https://github.com/wojcikm11)
* [Katarzyna Grygorowicz](https://github.com/kasiagrygorowicz)
* [Marek Nowakowski](https://github.com/MarekSNowakowski)
* [Szymon Szafrański](https://github.com/SmiledProgrammer)
* [Hubert Mazur](https://github.com/JayHubPL)
* [Bartosz Kabała](https://github.com/BarKabal)

## Cel projektu
 Wiele osób regularnie czytających książki dochodzi do momentu w którym nie mają co czytać i próbują znaleźć odpowiednią dla siebie powieść. Aby ułatwić im zadanie, przygotowaliśmy serwis rekomendacyjny, gdzie użytkownik oprócz znalezienia interesującej go książki i przejrzenia lub pozostawienia opinii, może zapoznać się z rekomendacjami wybranymi specjalnie dla niego na podstawie jego wyszukiwań. Aby strona była przyjazna dla wszystkich, opinie zostawiane przez użytkowników są sprawdzane automatycznie, w celu wykrycia i zablokowania obraźliwych bądź szkodliwych treści. Jest to więc miejsce dla miłośników książek, poszukujących czegoś nowego, bądź chętnych do podzielenia się swoją opinią.

## Opis projektu i funkcjonalności
### Funkcjonalności rozwiązania
* Rejestracja oraz logowanie do serwisu
* Wyświetlanie rekomendowanych książek
* Wyszukiwanie książek po tytule
* Wyświetlanie szczegółów książek
* Wyświetlanie opinii innych oraz dodawanie swoich opinii o książkach

### Przykładowy scenariusz
Użytkownik loguje się do serwisu i wyszukuje interesującą go książkę. Następnie przegląda opinie innych użytkowników lub pozostawia własną. Potem cofa się do strony głównej, gdzie przegląda książki rekomendowane dla niego. Wybiera interesującą go książkę i zapoznaje się z informacjami oraz opiniami na jej temat. Użytkownik powtarza wyszukiwanie kilkukrotnie wyszukując interesujące go książki, zwiększając tym samym trafność przygotowywanych dla niego rekomendacji.

## Schemat działania
- Użytkownik rejestruje się w serwisie
- Użytkownik loguje sie do serwisu podając dane z rejestracji
- Użytkownik wyszukuje ostatnio przeczytaną książkę po tytule
- Serwis rekomendacyjny zapisuje informację o wyszukaniu użytkownika
- Uzytkownik wchodzi w szczegóły wybranej książki
- Użytkownik pisze oraz wysyła recenzję
- Moderator kontentu sprawdza treść recenzji pod kątem jej bezpieczeństwa
- Baza danych zapisuje recenzję
- Użytkownik powraca na stronę główną serwisu
- Serwis rekomendacyjny wybiera książki dopasowane do zainteresowań użytkownika
- Aplikacji internetowa wyświetla książki rekomendowane dla użytkownika

## Diagram architektury
![image](https://user-images.githubusercontent.com/61696629/211648280-a537ebcc-8b96-4957-bd16-f57e4853ec3a.png)

## Opis wybranych serwisów i stosu technologicznego
- Frontend - App Service, React - deployment przez VS Code
- Backend - Azure Spring Apps, Spring
- Baza danych - Azure Database for MySQL flexible server
- Rekomendacje - App Service, Python
- Moderacja treści - Content Moderator
- Przechowywanie zdjęć - Storage Account
- Inne: Key Vault, Virtual Network, Managed Identity, Private DNS zone

## Demo aplikacji

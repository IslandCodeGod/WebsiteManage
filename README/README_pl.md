# Flask Web Application - system zarządzania stronami internetowymi w przedsiębiorstwie (wersja szyfrowana)

## Wprowadzenie do projektu

To jest **zaszyfrowana wersja** korporacyjnego systemu zarządzania stronami internetowymi opracowanego w oparciu o framework Flask.Główny kod został zaciemniony i zaszyfrowany przez PyArmor w celu ochrony praw własności intelektualnej.System obsługuje wiele języków (chiński i angielski), uwierzytelnianie użytkowników, zarządzanie produktami i wiadomościami, wyświetlanie informacji o firmie i inne funkcje.

## Zrzut ekranu aplikacji

Poniżej znajduje się zrzut ekranu głównego interfejsu aplikacji:

### Dom
![首页](screenshots/index.png)

### Doświadczenie w zarządzaniu
![管理后台](screenshots/admin_dashboard.png)

## Informacje o wydaniu

Ta wersja to podstawowa wersja szyfrowania, która zapewnia pełne funkcje zarządzania korporacyjną stroną internetową.Jeśli potrzebujesz:

- **Pełna wersja kodu źródłowego**: Zawiera niezaszyfrowany, kompletny kod źródłowy, aby ułatwić rozwój wtórny
- **Niestandardowy rozwój funkcji**: dostosowywanie i rozszerzanie funkcji zgodnie z Twoimi konkretnymi potrzebami
- **Usługi wsparcia technicznego**: Skorzystaj z profesjonalnego wsparcia technicznego i usług konserwacyjnych

Skontaktuj się z nami za pomocą poniższych danych kontaktowych, a my przedstawimy Ci szczegółowe plany i oferty.

## Funkcje szyfrowania

- **Ochrona kodu**: Pliki Core Python (app.py, init_db.py, models.py) są zaciemniane i szyfrowane
- **Ochrona środowiska wykonawczego**: Użyj środowiska wykonawczego PyArmor, aby zapobiec dekompilacji kodu
- **Pełna funkcjonalność**: Zaszyfrowany kod zachowuje całą oryginalną funkcjonalność i funkcje
- **Obsługa wielu języków**: wbudowana funkcja przełączania w języku chińskim i angielskim

## Dołącz pliki

__KOD_BLOKU_0__

## Szybki start

### Wymagania środowiskowe

- Python 3.9 lub nowszy
- Zainstalowane pakiety zależności:
- Kolba 3.0.0+
- Flask-SQLAlchemy 3.1.1+
- Logowanie do kolby 0.6.3+
- Flask-Babel 4.0.0+
- Werkzeug 3.0.1+

### Zainstaluj zależności

Jeśli wymagane zależności nie są jeszcze zainstalowane, zainstaluj je najpierw:

__KOD_BLOKU_1__

### Uruchom aplikację

1. **Zainicjuj bazę danych**

Przed pierwszym uruchomieniem należy zainicjować bazę danych:

__KOD_BLOKU_2__

2. **Uruchom aplikację**

__KOD_BLOKU_3__

3. **Dostęp do aplikacji**

Otwórz przeglądarkę i odwiedź: http://127.0.0.1:5000

## Instrukcje użytkowania

### Odwiedź stronę internetową

1. Otwórz przeglądarkę i odwiedź http://127.0.0.1:5000
2. Użyj przycisku zmiany języka w prawym górnym rogu, aby przełączać się między chińskim i angielskim

### Doświadczenie w zarządzaniu

1. Odwiedź http://127.0.0.1:5000/admin/login
2. Zaloguj się na konto administratora (domyślna nazwa użytkownika i hasło: admin/admin123)
3. Produkty, aktualności i informacje o firmie można zarządzać w tle zarządzania

## Opis funkcji

### Funkcje frontonu

- **Strona główna**: Wyświetl profil firmy i główne produkty
- **O nas**: Pokaż dane firmy
- **Wyświetlanie produktów**: Przeglądaj wszystkie oferty produktów
- **Aktualności branżowe**: Wyświetl najnowsze wiadomości i informacje
- **Przełączanie języka**: Obsługuje przełączanie między chińskim i angielskim

### Zarządzaj funkcjami w tle

- **Zarządzanie produktami**: dodawaj, edytuj, usuwaj produkty
- **Zarządzanie wiadomościami**: publikuj, edytuj, usuwaj wiadomości
- **Informacje o firmie**: aktualizacja podstawowych informacji o firmie
- **Uwierzytelnianie użytkownika**: bezpieczny system logowania

## Przewodnik po zrzutach ekranu

Aby uzyskać najlepszy efekt wyświetlania README, zaleca się tworzenie i dodawanie zrzutów ekranu zgodnie z poniższymi wytycznymi:

1. **Utwórz folder zrzutów ekranu**: Utwórz folder `screenshots/` w katalogu `dist/`
2. **Rozmiar zrzutu ekranu**: Użyj zrzutu ekranu w rozdzielczości 1920x1080 lub 1366x768, aby upewnić się, że zawartość jest dobrze widoczna
3. **Zawartość zrzutu ekranu**:
- Strona główna: Wyświetla kompletny interfejs strony głównej, łącznie z paskiem nawigacyjnym i głównym obszarem zawartości
- Przełączanie języka: Pokaż efekt porównawczy przełączania między chińskim i angielskim (można używać zrzutów ekranu na podzielonym ekranie)
- Wyświetlacz produktu: wyświetla listę produktów i szczegóły poszczególnych produktów
- Strona wiadomości: wyświetla listę wiadomości i szczegóły wiadomości
- Backend zarządzający: wyświetla dashboard i interfejs funkcjonalny po zalogowaniu się administratora
4. **Format zrzutu ekranu**: Użyj formatu PNG, aby uzyskać najlepszą jakość
5. **Nazewnictwo plików**: Zapisz zrzut ekranu zgodnie z nazwą pliku określoną w pliku README (index.png, język_switch.png itp.)

## Notatki

1. **Integralność pliku**: Upewnij się, że wszystkie pliki zostały pobrane poprawnie, zwłaszcza katalog `pyarmor_runtime_000000` i jego zawartość

2. **Plik bazy danych**:
- Plik bazy danych zostanie automatycznie utworzony w katalogu `instancja`
- Jeśli chcesz wykonać kopię zapasową danych, regularnie twórz kopię zapasową pliku `instance/site.db`

3. **Obsługa wielu języków**:
- Wszystkie pliki tłumaczeń znajdują się w katalogu `translations`
- Aby dodać nowe języki tłumaczeń, zapoznaj się z oryginalną dokumentacją projektu

4. **Środowisko operacyjne**:
- Upewnij się, że wersja Pythona nie jest niższa niż 3.9
- Upewnij się, że wszystkie niezbędne zależności są zainstalowane

5. **Wskazówki dotyczące bezpieczeństwa**:
- Podczas wdrażania w środowisku produkcyjnym zmień domyślne hasło administratora.
- Rozważ użycie serwera WSGI (takiego jak Gunicorn) zamiast serwera programistycznego
- Skonfiguruj odpowiednie reguły zapory sieciowej

## Zalecenia dotyczące wdrożenia

### Środowisko programistyczne

Skorzystaj z wbudowanego serwera programistycznego Flask (pokazanego w krótkim przewodniku powyżej).

### Środowisko produkcyjne

1. **Użyj serwera WSGI**:
__KOD_BLOKU_4__

2. **Użyj odwrotnego proxy**:
- Skonfiguruj Nginx lub Apache jako odwrotne proxy
- Skonfiguruj certyfikat SSL, aby włączyć HTTPS

3. **Optymalizacja bazy danych**:
- Rozważ użycie PostgreSQL lub MySQL zamiast SQLite
- Skonfiguruj mechanizm regularnego tworzenia kopii zapasowych

## Rozwiązywanie problemów

### Często zadawane pytania

1. **Nie można uruchomić aplikacji**:
- Sprawdź, czy wersja Pythona spełnia wymagania
- Sprawdź, czy wszystkie pakiety zależne zostały poprawnie zainstalowane
- Sprawdź, czy katalog `pyarmor_runtime_000000` istnieje i jest kompletny

2. **Zmiana języka nie działa**:
- Potwierdź, że katalog `tłumaczenia` i jego zawartość są kompletne
- Sprawdź, czy ustawienia plików cookies w przeglądarce są dozwolone

3. **Błąd połączenia z bazą danych**:
- Potwierdź, że katalog „instancja” istnieje i ma uprawnienia do zapisu
- Spróbuj ponownie uruchomić `init_db.py`, aby zainicjować bazę danych

### Widok dziennika

Po uruchomieniu aplikacji informacje dziennika zostaną wyświetlone na konsoli.Jeśli napotkasz problemy, możesz sprawdzić te dzienniki, aby uzyskać więcej informacji.

## Licencja

[MIT License](LICENSE)

## Informacje kontaktowe

Jeśli masz jakieś pytania, sugestie lub potrzebujesz opracowania pełnej wersji/niestandardowych funkcji, skontaktuj się z nami za pomocą następujących metod:

- **E-mail**: austinlive666@gmail.com (zalecane)
- **Niezgoda**:[https://discord.gg/7AN9PuGn](https://discord.gg/7AN9PuGn)

---

Dziękujemy za skorzystanie z tego projektu!
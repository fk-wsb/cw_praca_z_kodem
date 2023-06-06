# cw_praca_z_kodem

## Opis projektu:

Aplikacja webowa napisaną w języku Python przy użyciu frameworka Flask

## Instalacja:

1. Sklonuj repozytorium na swoje urządzenie.
2. Zainstaluj wymagane biblioteki za pomocą pip install -r requirements.txt.
3. Uruchom aplikację za pomocą python app.py.
4. Otwórz przeglądarkę internetową i przejdź do adresu http://localhost:5000.
5. Na stronie głównej zobaczysz powitanie, a następnie możesz kliknąć link, aby zobaczyć powitanie personalizowane. Wprowadź swoje imię i zobacz wynik.


## Pliki w projekcie:

app.py: Główny plik aplikacji. Zawiera funkcje, które odpowiadają na żądania HTTP i renderują szablony HTML.

templates/index.html: Szablon HTML dla strony głównej. 

templates/hello.html: Szablon HTML dla strony z powitaniem personalizowanym. 

requirements.txt: Plik zawierający listę bibliotek wymaganych do poprawnego działania aplikacji.

## Funkcjonalności:

Po uruchomieniu aplikacji i przejściu do strony głównej, użytkownik może kliknąć link, aby przejść do strony z powitaniem personalizowanym. Na tej stronie użytkownik zobaczy powitanie, które będzie zawierać jego imię (przekazane jako parametr name).

# POSTURAJsie

Trener personalny w kieszeni. Aplikacja webowa do treningu na siłowni, w języku polskim.

## Funkcje

- **Profil i BMI**: wiek, waga, wzrost i płeć. BMI liczone na bieżąco wg skali WHO, zakres zdrowej wagi, BMR (Mifflin-St Jeor), zapotrzebowanie kaloryczne i białko.
- **Cel**: schudnąć, przybrać na wadze albo zwiększyć mięśnie. Dla kobiet dodatkowo partie, na których plan się skupia (brzuch, uda, pośladki, ramiona, plecy).
- **Plan tygodniowy**: 2–5 treningów, dopasowany do celu i poziomu. Każde ćwiczenie można zamienić na inne.
- **Moja dieta**: dziennik żywienia w stylu Fitatu, czyli 5 posiłków dziennie, baza 136 produktów (w tym tofu, tempeh i inne roślinne źródła białka) z kaloriami i makroskładnikami, własne produkty, kopiowanie posiłku z poprzedniego dnia, licznik wody i nawigacja po dniach.
- **Sposób odżywiania**: jem wszystko, bez mięsa (z rybami), wegetariańska albo wegańska. Wybór filtruje przepisy, produkty i podpowiedzi trenera.
- **Przepisy**: 40 przepisów z wyliczonymi kaloriami i makro na porcję, ułożonych pod Twój cel kaloryczny. Każdy można dodać do dziennika jednym kliknięciem.
- **Aktywność**: wpisy z zegarka (czas, kalorie, prędkość, dystans, nachylenie, tętno), podsumowanie 7 dni i wykres kalorii z 14 dni. Bez zegarka kalorie można oszacować metodą MET.
- **Baza 140 ćwiczeń**: maszyny, wolne ciężary i cardio, z techniką i zamiennikami.
- **Trener (chatbot)**: w wersji offline odpowiada na podstawowe pytania (technika, zamienniki, kalorie, białko, regeneracja).

Wszystkie dane (profil, plan, dieta, aktywność, rozmowa z trenerem, ostatnio otwarta zakładka) zapisują się automatycznie w przeglądarce (`localStorage`) i są dostępne po ponownym wejściu. W zakładce Profil możesz pobrać kopię zapasową (.json) i wczytać ją na innym urządzeniu. Nie ma serwera ani kont użytkowników.

## Uruchomienie lokalne

Otwórz `index.html` w przeglądarce.

## GitHub Pages

1. Utwórz repozytorium, np. `posturajsie`, i wrzuć do niego wszystkie pliki z tego folderu.
2. Wejdź w **Settings → Pages**, w polu *Source* wybierz **Deploy from a branch**, gałąź `main`, folder `/ (root)`, i kliknij **Save**.
3. Po około minucie strona będzie pod adresem `https://<twoj-login>.github.io/posturajsie/`.

Na telefonie możesz dodać stronę do ekranu głównego. Wtedy otwiera się jak aplikacja, z ikoną z `icon-512.png`.

## Pliki

| Plik | Opis |
|---|---|
| `index.html` | cała aplikacja (HTML, CSS i JS w jednym pliku) |
| `logo.svg` | logo wektorowe, bez tła |
| `logo.png` | logo PNG 1024 px, przezroczyste tło |
| `icon-192.png`, `icon-512.png` | kwadratowe ikony aplikacji |
| `manifest.webmanifest` | manifest do instalacji na ekranie głównym |

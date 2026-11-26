# Angielski - nauka

Aplikacja do nauki angielskiego (PWA). Działa w przeglądarce, da się ją zainstalować na telefonie i działa bez internetu.

## Jak wrzucić na GitHub (GitHub Pages)

1. Wejdź na github.com i zaloguj się (albo załóż darmowe konto).
2. Kliknij **+** (prawy górny róg) → **New repository**.
3. Nazwa np. `angielski`, ustaw **Public**, kliknij **Create repository**.
4. Kliknij **uploading an existing file** i przeciągnij **wszystkie pliki z tego folderu**:
   - `index.html`
   - `manifest.webmanifest`
   - `sw.js`
   - folder `icons` (z `icon-192.png` i `icon-512.png`)
   - `README.md` (opcjonalnie)

   Kliknij **Commit changes**.
5. Wejdź w **Settings → Pages**.
6. W polu **Branch** wybierz `main` i folder `/ (root)`, kliknij **Save**.
7. Po 1-2 minutach strona będzie pod adresem:
   `https://TWOJA-NAZWA.github.io/angielski/`

## Jak zainstalować na telefonie

- **Android (Chrome):** otwórz adres, menu (trzy kropki) → **Zainstaluj aplikację** lub **Dodaj do ekranu głównego**.
- **iPhone (Safari):** otwórz adres, przycisk **Udostępnij** → **Do ekranu początkowego**.

Ikona pojawi się na ekranie głównym i aplikacja otworzy się jak zwykła, bez paska przeglądarki.

## Aktualizacja

Podmień `index.html` w repozytorium. Jeśli zmiana nie pojawia się od razu, w pliku `sw.js` zmień `angielski-v1` na `angielski-v2`.

## Google Play (opcjonalnie)

Gotowy adres z GitHub Pages możesz wpisać na pwabuilder.com, wygenerować paczkę Androida i wysłać do Google Play (potrzebne konto deweloperskie, jednorazowo ok. 25 USD).

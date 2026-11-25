# Strona gabinetu – jak uzupełnić i opublikować

## Pliki
- `index.html`: strona gabinetu (z quizem „Dobierz zabieg” i programem poleceń)
- `karta-opinii.html`: generator kart z kodem QR do opinii Google (do druku)
- `js/qrcode.js`: biblioteka do generowania kodów QR (licencja MIT, nie ruszać)

## Uzupełnianie (ok. 30 minut)
1. Otwórz `index.html` i na samym dole znajdź blok `CONFIG`. Wpisz tam nazwę, telefon, link do Booksy, Instagrama i link do opinii Google.
2. Wyszukaj w pliku wszystko, co jest w nawiasach kwadratowych `[ ... ]`, oraz komentarze `✏️ UZUPEŁNIJ` i podmień na prawdziwe dane (ceny, adres, „O mnie”, opinie).
3. Zdjęcia wrzuć do folderu `img/` i odkomentuj linijki `<img ...>` w sekcjach hero i „O mnie”.
4. Mapa: Google Maps → wyszukaj gabinet → Udostępnij → „Umieść mapę” → skopiuj `<iframe>` i podmień ten w sekcji Kontakt.

## Publikacja za darmo (GitHub Pages)
Repozytorium → **Settings → Pages** → Source: *Deploy from a branch* → Branch: `main`, folder `/docs` → Save.
Po około minucie strona działa pod adresem `https://<login>.github.io/<repo>/`.
Własna domena (np. `nazwagabinetu.pl`, ok. 50 zł/rok) ustawia się w tym samym miejscu, w polu „Custom domain”.

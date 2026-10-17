# Strona aplikacji — GitHub Pages

Ten folder to cała strona aplikacji: `index.html` (opis, funkcje, zrzuty, cennik, pomoc), `prywatnosc.html` (polityka
prywatności — ta sama co w aplikacji; zmieniaj ją w `web/prywatnosc.html` i kopiuj tutaj, test w
`tests/test_offline.py` pilnuje, żeby były identyczne), `favicon.svg` i `zrzuty/*.jpg`.

- Repozytorium: https://github.com/adym203/skarbiec (Settings → Pages: Deploy from a branch, main, /(root)).
- Adresy: strona https://adym203.github.io/skarbiec/, pomoc …/#pomoc, polityka …/prywatnosc.html
  (wpisane w `ios/Skarbiec/Info.plist` → SkarbiecPrivacyURL i w `ios/AppStore.md`).
- Zmiana: popraw plik tutaj, potem na GitHubie Add file → Upload files → przeciągnij zmienione pliki → Commit changes.
  Po 1–2 minutach strona jest zaktualizowana.
- Po publikacji w App Store: przycisk `id="appstore"` w `index.html` dostaje adres aplikacji (opis w komentarzu nad nim).

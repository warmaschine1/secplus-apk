# Security+ Learning – budowa APK

## Wariant A: bez instalowania czegokolwiek (GitHub Actions)
1. Załóż darmowe konto na github.com i utwórz nowe repozytorium (Private jest OK).
2. Wgraj do niego całą zawartość tego folderu (Add file -> Upload files). Folder .github musi zostać wgrany razem z resztą.
3. Wejdź w zakładkę Actions -> "Build APK" -> poczekaj ok. 5-8 minut na zielony znaczek.
4. Wejdź w ukończone uruchomienie i pobierz plik "security-plus-learning-apk" (zip z app-debug.apk).
5. Przerzuć app-debug.apk na telefon, otwórz go i zezwól na instalację z nieznanych źródeł.

## Wariant B: lokalnie (Node 20+, Android Studio, JDK 21)
npm install
npx cap add android
npx cap sync android
npx cap open android   # Build -> Build APK(s)

Zmiana pytań lub wyglądu: edytuj www/index.html i zbuduj ponownie.

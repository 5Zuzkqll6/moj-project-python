# Symulator Wyprawy Robota GIGA-1

### Opis projektu
Projekt został stworzony na konkurs Gigathon 2026. Jest to tekstowy symulator wyprawy robota po dwuwymiarowym świecie. Robot porusza się po współrzędnych (x, y), zarządza swoimi zasobami energii i reaguje na losowe zdarzenia na trasie.

### Funkcje programu:
* **Zarządzanie zasobami:** Robot startuje z określoną ilością energii, która zużywa się przy każdym ruchu.
* **System współrzędnych:** Program śledzi położenie robota na mapie (północ, południe, wschód, zachód).
* **Zdarzenia losowe:** Podczas wyprawy robot może znaleźć dodatkową energię (baterie) lub trafić na trudny teren, który ją zabiera.
* **Raport końcowy:** Po zakończeniu wyprawy wyświetlane jest podsumowanie z przebytą trasą i stanem końcowym.

### Instrukcja uruchomienia
1. Upewnij się, że masz zainstalowanego Pythona (wersja 3.11 lub nowsza).
2. Pobierz plik `main.py`.
3. Otwórz terminal/wiersz poleceń w folderze z plikiem.
4. Uruchom program komendą: `python main.py`
5. Podaj parametry początkowe (energia, liczba kroków) i śledź przebieg wyprawy

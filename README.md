
# 📊 Ankieta WPF – Statystyki użytkowników

Aplikacja desktopowa stworzona w technologii **C# i WPF (.NET)**. Umożliwia zbieranie danych ankietowych oraz automatyczne generowanie statystyk na podstawie zapisanych odpowiedzi.

## ✨ Funkcje

- 👤 Wybór płci: mężczyzna, kobieta lub inne.
- 🎂 Podanie wieku (od 1 do 120 lat).
- 🎨 Wybór ulubionego koloru.
- ☑️ Zaznaczenie zgody.
- 💾 Zapisywanie odpowiedzi do pliku `dane.txt`.
- 📈 Automatyczne obliczanie statystyk:
  - średni wiek uczestników,
  - najczęściej wybierany kolor,
  - liczba mężczyzn, kobiet i osób wybierających „Inne”,
  - liczba osób, które wyraziły zgodę.
- 📄 Zapisywanie podsumowania do pliku `statystyki.txt`.

## 🛠️ Technologie

- C#
- WPF (Windows Presentation Foundation)
- .NET
- XAML
- System plików .NET

## 🚀 Uruchomienie projektu

1. Sklonuj repozytorium:

   ```bash
   git clone <URL_REPOZYTORIUM>
   ```

2. Otwórz plik rozwiązania `.sln` lub projekt `.csproj` w Visual Studio.

3. Upewnij się, że masz zainstalowane środowisko .NET odpowiednie dla projektu.

4. Uruchom aplikację za pomocą `F5` lub przycisku **Start**.

5. Wypełnij formularz i kliknij **Zapisz**.

## 📁 Pliki aplikacji

| Plik | Opis |
|---|---|
| `MainWindow.xaml` | Interfejs użytkownika |
| `MainWindow.xaml.cs` | Logika formularza, zapis danych i obliczanie statystyk |
| `dane.txt` | Zapisane odpowiedzi ankietowe |
| `statystyki.txt` | Wygenerowane statystyki |

Pliki tekstowe są tworzone w katalogu uruchomieniowym aplikacji, np. `bin/Debug/net8.0-windows/`, zależnie od konfiguracji projektu.

## 📊 Przykładowe dane – `dane.txt`

```text
Mężczyzna;25;Niebieski;Tak
Kobieta;31;Czerwony;Nie
Inne;20;Niebieski;Tak
```

## 📈 Przykładowe statystyki – `statystyki.txt`

```text
STATYSTYKI
Liczba osób: 3
Średni wiek: 25,33
Najczęstszy kolor: Niebieski (2)
Mężczyźni: 1
Kobiety: 1
Inne: 1
Zgody: 2
```

## 🔒 Informacje o danych

Aplikacja zapisuje odpowiedzi lokalnie w plikach tekstowych. Przed wykorzystaniem jej do zbierania rzeczywistych danych należy zadbać o odpowiednią ochronę danych osobowych i prawidłową treść zgody.

## 📌 Możliwe rozszerzenia

- Dodanie wykresów statystycznych.
- Eksport danych do CSV lub Excel.
- Dodanie możliwości usuwania rekordów.
- Zmiana miejsca zapisu plików.
- Zastąpienie plików tekstowych bazą danych SQLite.

## 📄 Licencja

Projekt edukacyjny. Możesz dostosować go do własnych potrzeb.

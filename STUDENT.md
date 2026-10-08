# Moje wykonanie Lab00

- Login GitHub / pseudonim: tkuznowicz
- System i terminal (np. Windows + WSL Ubuntu): Windows / Powershell
- Edytor / IDE: VSCode
- Wersja Git: 2.56.0.windows.1
- Wersja kompilatora C++: g++ (GCC) 13.4.0
- Wersje java i javac: openjdk 25.0.2 2026-01-20 LTS/javac 25.0.2
- Link do pierwszego PR (uzupełnij w zadaniu 5): https://github.com/tkuznowicz/oop-lab00-tkuznowicz/pull/1

## Uruchomienie lokalne
Wynik programu C++:
```Hello from C++! Author: tkuznowicz
...
```
Wynik programu Java:
```Hello from Java! Author: tkuznowicz
...
```

## Błąd i poprawka (zadanie 5)
- Krótki fragment komunikatu błędu i numer linii: cpp/main.cpp:5:62: error: expected ‘;’ before ‘return’
- Przyczyna oraz sposób naprawy: dodanie średnika na końcu linii
- Commit z błędem (SHA lub link): https://github.com/tkuznowicz/oop-lab00-tkuznowicz/commit/920a951e61015cc4e84fe58d6859bfd3e84a4291
- Czy Actions pokazały błąd, a po naprawie sukces? tak

## Krótkie odpowiedzi
1. Co różni commit od push? Commit zapisuje zmiany lokalnie, push wysyła lokalne commity na serwer
2. Dlaczego po scaleniu PR wykonuję lokalnie pull? Wykonanie pull pobiera najnowsze zmiany z serwera i aktualizuje lokalną gałąź. 
3. Co potwierdza zielony wynik naszego CI, a czego nie potwierdza? Potwierdza poprawną kompilację kodu i zakończenie sukcesem testów automatycznych. Nie potwierdza, że kod nie ma żadnych błędów logicznych, program działa zgodnie z oczekiwaniami użytkownika i spełnia jego wymagania.

## Ewentualne problemy środowiska
Brak

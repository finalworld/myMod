# Bubbsun v0.04

En offline inköpslista i retrostil för Danne och Sanja.

## Funktioner
- Flera namngivna listor
- Aktivt och klart
- Avbockat flyttas till KLART
- Klart ligger kvar tills det raderas
- Dublettskydd
- Om en klar vara läggs till igen återaktiveras den
- Sök bland tidigare varor
- Frivillig mängd
- Danne = gul, Sanja = rosa
- Ljust och mörkt retrotema
- Statistik: livstid och 30 dagar
- Mest köpta, mest borttagna, användarfördelning och Bubbsun Awards
- Offline-lagring
- Långtryck och dra i handtaget för att sortera aktiva varor

## Bygga APK med GitHub
1. Packa upp zip-filen.
2. Skapa ett tomt GitHub-repository.
3. Ladda upp **innehållet** i mappen, inte själva zip-filen.
4. Öppna fliken **Actions**.
5. Kör workflowet **Build Bubbsun APK** eller vänta på automatisk körning.
6. Öppna den gröna körningen och hämta artifacten `Bubbsun-v0.04-debug-apk`.
7. Packa upp artifact-zippen och installera `app-debug.apk`.

Android kan fråga om tillåtelse att installera okända appar från webbläsaren eller filhanteraren.

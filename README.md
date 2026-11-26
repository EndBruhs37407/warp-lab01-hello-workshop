Aplikacja konsolowa .NET stworzenia podczas laboratorium.

## Uruchomienie
\`\`\`bash
dotnet run
\`\`\`

## Kontakt
Autor: Student (szymkowyrz)
Zespół: Warsztat Programisty

## Instrukcyja
\`\`\`bash
dotnet run
\`\`\`

### Continuous Integration
- Zdarzenia uruchamiające workflow:
    workflow uruchamia się przy push oraz przy pull_requestach
- Lista kontroli:
    No w sumie to se sprawdza ta akcja czy sie zgadza to i tamto tak w skrócie cn, mozna se przeczytac w build.yml (dla chcącego nic trudnego)
- Gdzie znaleźć logi i artefakty:
    Logi i artefakty można znaleźć po wejściu w akcje i workflow runa. Artefakt znajduje się w podsumowaniu na dole strony.
- Sprawdzany projekt i używana wersja .NET:
    Projekt HelloWorkshop.csproj jest sprwadzany
    Wersja .NET Core Runtime: 10.0.15
    Wersja .NET Core SDK: 10.0.404
- Artefakt:
    żyje sobie przez 7 dni, nazywa się app-[magiczne literki i cyferki here]
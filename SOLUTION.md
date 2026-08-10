# Lösning

## Nyckelkommandon

```bash
git branch
git status
git fetch origin
git merge origin/main
git status
```

## Därför händer det

Branchen `case-01-glomde-pull` skapades från en äldre version av projektet och innehåller därför inte de senaste ändringarna som finns i `main`.

Git låter dig hämta den senaste informationen från GitHub och sedan lägga in ändringarna från `main` i din egen branch utan att dina egna ändringar behöver försvinna.

## Tips

- Använd `git branch` för att kontrollera att du står i `case-01-glomde-pull`.
- Använd `git fetch origin` för att hämta den senaste informationen från GitHub.
- I det här caset ska du lägga in den senaste versionen från `main` i din egen branch.
- Kontrollera att både dina egna ändringar och ändringarna från `main` finns kvar efteråt.
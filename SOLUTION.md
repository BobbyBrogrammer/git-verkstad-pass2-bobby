# Lösning

## Nyckelkommandon

```bash
git log --oneline
git switch case-02-ratt-branch
git cherry-pick <commit-id>
git switch case-02-fel-branch
git reset --hard HEAD~1
git status
```

## Därför händer det

Commits tillhör den branch där de skapades.

Om du råkar arbeta i fel branch kan du flytta commiten till rätt branch med `git cherry-pick` och sedan ta bort den från den felaktiga branchen.

## Tips

- Använd `git log --oneline` för att hitta commit-id.
- Kontrollera att du står i `case-02-ratt-branch` innan du kör `git cherry-pick`.
- I det här caset ska commiten flyttas från `case-02-fel-branch` till `case-02-ratt-branch`.
- Kontrollera med `git status` att allt är klart.
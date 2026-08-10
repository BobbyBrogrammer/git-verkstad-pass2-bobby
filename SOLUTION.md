# Lösning

## Nyckelkommandon

```bash
git log --oneline
git switch feature-ny-rubrik
git cherry-pick <commit>
git switch case-02-fel-branch
git reset --hard HEAD~1
git status
```

## Därför händer det

Commits tillhör den branch där de skapades.

Om du råkar arbeta i fel branch kan du flytta commiten till rätt branch med `git cherry-pick` och sedan ta bort den från den felaktiga branchen.

## Tips

- Använd `git log --oneline` för att hitta commit-hashen.
- Kontrollera att du står i rätt branch innan du kör `git cherry-pick`.
- Kontrollera att commiten finns i `feature-ny-rubrik`.
- Kontrollera med `git status` att allt är klart.
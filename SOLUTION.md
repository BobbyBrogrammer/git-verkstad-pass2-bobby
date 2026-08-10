# Lösning

## Nyckelkommandon

```bash
git status
git ls-files .env
git rm --cached .env
git status
git commit -m "Stop tracking .env"
git push
```

## Därför händer det

`.env` är redan committad och spåras därför av Git. Att lägga till `.env` i `.gitignore` gör inte att Git slutar spåra en fil som redan finns i historiken.

Med `git rm --cached .env` tar du bort filen från Git men inte från datorn. Eftersom `.env` finns i `.gitignore` kommer Git sedan att ignorera filen.

## Tips

- Använd `git ls-files .env` för att kontrollera om `.env` fortfarande spåras.
- Använd `git rm --cached .env` för att ta bort `.env` från Git utan att ta bort filen från datorn.
- Kontrollera med `git status` att `.env` inte längre är tracked.
- Kontrollera att `.env` fortfarande finns kvar på datorn.
- Kontrollera att `.env` finns med i `.gitignore`.
- Committa och pusha ändringen när du har kontrollerat att allt fungerar.
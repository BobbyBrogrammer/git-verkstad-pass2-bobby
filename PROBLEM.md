# Case 05 – .env är fortfarande spårad av Git

## Scenario

En utvecklare har av misstag committat och pushat filen `.env` till Git.

Efteråt skapades en `.gitignore` där `.env` lades till, men filen fortsätter ändå att spåras av Git.

## Din uppgift

- Undersök varför `.env` fortfarande spåras av Git.
- Se till att Git slutar spåra filen utan att ta bort den från datorn.
- Kontrollera att `.env` nu ignoreras av Git.

> **Tips:** Att lägga till en fil i `.gitignore` räcker inte om filen redan är committad.
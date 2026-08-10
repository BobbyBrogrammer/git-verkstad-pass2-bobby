# Case 05 – .env är fortfarande spårad av Git

## Scenario

En utvecklare har av misstag committat och pushat filen `.env` till Git.

Efteråt skapades en `.gitignore` där `.env` lades till, men filen fortsätter ändå att spåras av Git.

## Din uppgift

1. Kontrollera varför `.env` fortfarande spåras av Git.
2. Se till att Git slutar spåra `.env` utan att filen tas bort från datorn.
3. Kontrollera att `.env` nu ignoreras av Git.
4. Kontrollera att `.env` fortfarande finns kvar på datorn.

> **Tips:** Att lägga till en fil i `.gitignore` räcker inte om filen redan är committad.
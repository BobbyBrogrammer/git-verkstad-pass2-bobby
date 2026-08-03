# Lösning – Case 01

## Steg 1 – Kontrollera vilken branch du arbetar i

```bash
git branch
```

## Steg 2 – Hämta den senaste informationen från GitHub

```bash
git fetch origin
```

## Steg 3 – Hämta in de senaste ändringarna från `main`

```bash
git merge origin/main
```

> Alternativt:

```bash
git pull origin main
```

## Steg 4 – Kontrollera att ändringarna finns

- Kontrollera att de nya ändringarna från `main` finns i projektet.
- Kontrollera att dina egna ändringar fortfarande finns kvar.

## Vad lärde du dig?

- Att alltid uppdatera din branch innan du fortsätter arbeta.
- Skillnaden mellan `fetch`, `merge` och `pull`.
- Hur du hämtar in de senaste ändringarna från `main` till din egen branch.
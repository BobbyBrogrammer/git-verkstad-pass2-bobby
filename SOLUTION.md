# Lösning – Case 02

## Steg 1 – Gör en ändring och skapa en commit

```bash
git add .
git commit -m "Min ändring"
```

## Steg 2 – Skapa den rätta branchen

```bash
git switch -c feature-ny-rubrik
```

Din commit följer automatiskt med till den nya branchen.

## Steg 3 – Gå tillbaka till den felaktiga branchen

```bash
git switch case-02-fel-branch
```

## Steg 4 – Ta bort den felaktiga commiten

```bash
git reset --hard HEAD~1
```

## Kontrollera resultatet

- `feature-ny-rubrik` innehåller din commit.
- `case-02-fel-branch` är återställd till sitt ursprungliga läge.
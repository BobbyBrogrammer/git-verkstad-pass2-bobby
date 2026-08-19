# Git-verkstad – Pass 2

Detta repo används under Git-verkstadens andra pass.

Fokus i detta pass är hur utvecklare samarbetar med Git i ett gemensamt projekt.

## Starta projektet

Öppna `index.html` i webbläsaren eller använd Live Server i Visual Studio Code.

## Så fungerar övningarna

Varje övning ligger i en egen branch.

Byt till den branch du vill arbeta med och läs `PROBLEM.md` för att förstå scenariot och uppgiften.

Där finns även tips som hjälper dig att komma igång.

Om du fastnar kan du använda `SOLUTION.md` som vägledning.

Du byter branch med:

```bash
git switch <branch-namn>
```

## Brancher

### Case 01 – Jag glömde hämta senaste ändringarna

Tränar på vad som händer när någon annan har hunnit göra ändringar innan du själv försöker fortsätta arbeta.

### Case 02 – Min push nekas

**Branch:** `case-02-ratt-branch`

Tränar på att förstå varför en push kan nekas och hur man hanterar att remote-branchen innehåller ändringar man själv inte har lokalt.

### Case 03 – Pull Request

**Branch:** `case-03-pull-request`

Tränar på att skapa en branch, göra ändringar och öppna en Pull Request för att få sina ändringar granskade.

### Case 04 – Code review

**Branch:** `case-04-code-review`

Tränar på att granska en annan persons Pull Request och lämna kommentarer på koden.

### Case 04 – Feature review

**Branch:** `case-04-feature-review`

Tränar på att granska en större ändring eller feature och bedöma om den är redo att slås ihop.

### Case 05 – .gitignore

**Branch:** `case-05-gitignore`

Tränar på vad man gör när filer som exempelvis `node_modules` eller `.env` redan har committats innan de lades till i `.gitignore`.

## Rekommenderad ordning

1. Hämta senaste ändringar
2. Push nekas
3. Pull Request
4. Code review
5. Feature review
6. .gitignore

## Tips

Använd `git status`, `git log` och `git branch` ofta för att förstå vad som händer.

Läs alltid `PROBLEM.md` först och försök lösa uppgiften själv innan du tittar i `SOLUTION.md`.

## Projektets filer

```text
git-verkstad-pass-2/
├── README.md
├── index.html
├── artiklar.html
├── om.html
├── kontakt.html
├── style.css
└── script.js
```

## Mål

Efter detta pass ska du känna dig tryggare med att samarbeta i Git genom att arbeta med brancher, Pull Requests, code review och vanliga problem som uppstår när flera utvecklare arbetar i samma projekt.
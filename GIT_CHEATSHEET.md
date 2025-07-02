# Git Cheat Sheet

## Grundlæggende kommandoer

### 1. Se status
```bash
git status
Viser ændringer og hvad der er staged.

2. Tilføj ændringer til staging

git add .
Tilføjer alle ændringer til staging. Kan også tilføje enkeltfiler:


git add FILNAVN
3. Commit ændringer (lokal gemning)

git commit -m "Beskriv hvad du har lavet"

4. Push til GitHub (send til fjernlager)

git push

5. Pull fra GitHub (hent og merge ændringer)

git pull

6. Ekstra kommandoer
Se commit-log

git log --oneline

7. Annullér ændringer i en fil (tilbage til sidste commit)

git checkout FILNAVN

8. Annullér staging af en fil

git reset FILNAVN


HUSK!!!
Commit = gem lokalt

Push = send til GitHub

GitHub opdateres kun, når du pusher
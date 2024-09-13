# my-command-line-program
=======
# Check Name Script

## Oversigt

`check_name`-scriptet er en Python-kommando, der beder brugeren om at indtaste deres navn. Det giver specifikke svar, hvis navnet er "Patrick Bateman" og generel feedback for andre navne.

## Funktioner

- **Specifikt Svar for "Patrick Bateman":**
  - Viser en besked, der angiver, at personen er en psykopat.
  - Angiver en reservationsstatus.
  - Spørger, om brugeren vil returnere nogle videotapes og giver et svar baseret på deres input.

- **Generel Respons:**
  - Udskriver det indtastede navn.

## Forudsætninger

- **Python 3**: Scriptet er skrevet i Python 3. Sørg for, at Python 3 er installeret på dit system.

## Installation og Opsætning

Kopier og indsæt følgende kommandoer direkte i din terminal for at opsætte scriptet:

```bash
# Klon repository fra GitHub til dit device 
git clone https://github.com/Natazja/my-command-line-program.git

# Skift til projektmappen
cd my-command-line-program

# Ændr tilladelserne for scriptet for at gøre det eksekverbart
chmod +x check_name

# Flyt scriptet til en katalog i din PATH
sudo mv check_name /usr/local/bin/
```

## Brug

Når scriptet er flyttet til en katalog i din PATH, kan du køre det fra enhver terminal med følgende kommando:
```bash
check_name
```
Hvis du ikke har flyttet scriptet, kan du køre det direkte fra projektmappen med:
```bash
./check_name
```
## Kontakt
For spørgsmål eller feedback, kontakt venligst natazjadahl@gmail.com

# expense-tracker

Hold styr på dine udgifter fra terminalen. Alt gemmes i en almindelig CSV-fil, som du også kan åbne i Excel eller Google Sheets.

## Brug

```bash
python expenses.py add 49.50 mad Frokost med Anna
python expenses.py add 299 tøj Nye sko --date 2026-11-10
python expenses.py list
python expenses.py list --month 2026-11
python expenses.py summary
```

`summary` viser, hvor meget du har brugt per kategori, med procentandel.

Data gemmes i `~/.expenses.csv`. Sæt miljøvariablen `EXPENSE_FILE` for at bruge en anden fil.

## Krav

Python 3.8 eller nyere.

## Licens

MIT

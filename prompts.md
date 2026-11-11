# Revenue review prompts

## Fictional worked example

```text
Using only the fictional data below, review revenue against budget. All amounts are USD. Calculate variance as Actual minus Budget and variance percentage as variance divided by Budget. Show one table sorted by absolute variance, largest first; break ties alphabetically by region. Show the overall totals and three short commentary bullets. Do not invent causes; suggest questions to investigate instead.

Region | Actual | Budget
East | 10000 | 12000
West | 15000 | 14000
North | 8000 | 10000
South | 11000 | 11000
```

## Reusable version

Replace every bracketed field before running. If you use the current workbook as the source, remove the unused paste-data placeholder at the end.

```text
Review revenue against budget for [MONTH AND YEAR], using only [IDENTIFY THE CURRENT WORKBOOK, SHEET AND TABLE, OR PASTE THE CURRENT DATA BELOW].

All amounts are [CURRENCY]. Confirm the source contains Region, Actual and Budget before calculating. If the source is missing or ambiguous, ask me to identify it.

Calculate variance as Actual minus Budget and variance percentage as variance divided by Budget. If Budget is zero, show N/A for that percentage and flag the row. Show one table sorted by absolute variance, largest first; break ties alphabetically by region. Show overall totals and the overall percentage calculated from those totals, not an average of the regional percentages.

Finish with three short commentary bullets. Separate observations from questions to investigate. Do not invent causes or modify the workbook.

[IF PASTING DATA, INSERT THE CURRENT DATA HERE.]
```

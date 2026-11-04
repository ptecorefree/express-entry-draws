# Express Entry draws (rounds of invitations), 2015 to today

Every Express Entry round of invitations that Immigration, Refugees and Citizenship Canada (IRCC) has published, in one clean CSV and Excel file.

| Column | Meaning |
|---|---|
| Round | IRCC round number |
| Date | Date of the round (YYYY-MM-DD) |
| Draw type | Program or category drawn (e.g. Canadian Experience Class, French-language proficiency, Healthcare occupations) |
| CRS cutoff | Comprehensive Ranking System score of the lowest-ranked candidate invited |
| Invitations | Number of invitations to apply issued |
| Tie-breaking rule | Profile-submission time used to break ties at the cutoff score, when IRCC published one |

Files:
- `data/express-entry-draws.csv` (UTF-8, comma separated)
- `data/express-entry-draws.xlsx`

## Source and updates

- Source: IRCC, "Express Entry rounds of invitations" (https://www.canada.ca/en/immigration-refugees-citizenship/services/immigrate-canada/express-entry/rounds-invitations.html), reproduced under the Open Government Licence – Canada.
- A live, automatically refreshed version with a cutoff chart and the language scores each draw implies is at **https://ptecorefree.com/express-entry-draws/** (PTE Core Free). This repository is updated from it.
- This is not an official IRCC product and has no affiliation with IRCC or the Government of Canada. Always check the latest round on canada.ca before making a decision.

## Licence

The compilation is released under **CC BY 4.0**. Please credit:

> Express Entry draws dataset, PTE Core Free (ptecorefree.com), compiled from IRCC rounds of invitations (Open Government Licence – Canada).

## Related free tools

- CRS calculator using PTE Core scores: https://ptecorefree.com/tools/crs-calculator/
- PTE Core to CLB converter: https://ptecorefree.com/tools/pte-core-to-clb/
- Language requirements by category draw: https://ptecorefree.com/express-entry-draws/categories/

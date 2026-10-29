# Data Dictionary & Source Notes

Fill in this document after selecting the dataset. Do not assume a field exists until you inspect the source file.

## Dataset source
- Dataset name:
- Publisher / source URL:
- Download date:
- License / permitted use:
- File name:
- Number of rows:
- Number of columns:
- Season / date coverage:
- Row meaning (e.g., one driver per race, one race per row):

## Fields to look for
| Field | Meaning | Possible use | Notes |
|---|---|---|---|
| Season / year | Race season | Season filters and trend charts | Verify coverage |
| Driver | Driver name or ID | Driver leaderboard | Standardize names |
| Constructor / team | Team name or ID | Constructor comparison | Historical team names may change |
| Race / circuit | Event or circuit | Circuit analysis | Check event identifiers |
| Host country | Country hosting the event | Country ranking | Normalize country names |
| Points | Points awarded | Driver/team performance | Scoring systems vary by era |
| Position / status | Race result or completion status | Results and DNF analysis | Document DNF definition |
| Tyre compound | Soft, Medium, Hard, Intermediate, etc. | Tyre strategy | Use only if provided |
| Driver nationality | Nationality field | Talent-pool overview | Do not infer from names |
| Podium position | Finishing position 1–3 | Podium analysis | Define podium consistently |
| Failure reason | Retirement / failure classification | DNF reason analysis | May be absent or coarse |

## Data quality checks
- [ ] Check duplicate rows and key fields.
- [ ] Inspect missing driver, team, season, and race values.
- [ ] Confirm what one row represents.
- [ ] Standardize team, circuit, and country names where appropriate.
- [ ] Check status values and define how DNFs are counted.
- [ ] Check whether tyre data is race-level or lap-level.
- [ ] Document unavailable fields and any assumptions.

## Limitations
Record coverage gaps, missing tyre or failure details, historical scoring changes, and assumptions used in calculated measures.

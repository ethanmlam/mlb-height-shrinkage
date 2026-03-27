# MLB Height Shrinkage

How much did MLB players "shrink" when officially measured for the 2026 ABS (Automated Ball-Strike) challenge system?

For the first time, players were measured shoes-off, back-against-the-wall. This project compares those real measurements against years of self-reported heights from Baseball Reference.

**Live visualization:** [index.html](index.html)

## Key Findings

### 3-Year View (561 players with data in 2024, 2025, and 2026)
- **176 players shrunk**, 38 grew, 347 stayed the same
- Average shrinkage (for those who shrunk): **-1.31"**
- 38.1% of players had a height change over the 3-year period

### 2-Year View (710 players with 2025 and 2026 data)
- **101 players shrunk**, 25 grew, 584 stayed the same
- Average shrinkage (for those who shrunk): **-1.03"**
- 17.7% of players had a height change

### Notable 3-Year Shrinkage (-3 inches)
- **Bo Naylor** (C): 6'0" to 5'9"
- **Bryson Stott** (SS): 6'3" to 6'0"
- **Gleyber Torres** (2B): 6'1" to 5'10"
- **Connor Wong** (C): 6'1" to 5'10"

### Interesting Patterns
- 18 players had 2024 = 2026 height but a *different* 2025 height, suggesting Baseball Reference had typos or corrections in 2025 that didn't reflect reality
- The 3-year view shows higher change rates because it captures cumulative drift in self-reported heights over time

## Data Sources
- **2024 heights:** Baseball Reference (via Wayback Machine snapshots)
- **2025 heights:** Baseball Reference (via Wayback Machine snapshots)
- **2026 heights:** MLB Stats API (ABS-measured)

## Files
| File | Description |
|------|-------------|
| `index.html` | Self-contained visualization with both datasets embedded |
| `data.json` | 710 players, 2025 vs 2026 comparison |
| `data_3year_clean.json` | 561 players with all 3 years (2024, 2025, 2026) |
| `data.csv` | 710 player CSV export |
| `data_3year.csv` | 561 player CSV with 3-year data |

## Notes
- **Max Muncy fix:** There are two MLB players named Max Muncy (one born 1990, one born 2002). The 2024 scrape matched the wrong one, so Max Muncy was removed from the 3-year dataset to avoid incorrect comparisons.
- The 2-year dataset (710 players) includes players who only appeared in 2025+2026, while the 3-year dataset (561 players) requires presence in all three years.

## Author
Built by [@ethanmlam](https://twitter.com/ethanmlam)

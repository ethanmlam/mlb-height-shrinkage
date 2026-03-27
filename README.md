# MLB Height Shrinkage

How much did MLB players "shrink" when measured for the 2026 ABS challenge system?

## The Data

For the 2026 season, MLB implemented the Automated Ball-Strike (ABS) challenge system. The strike zone is now calculated precisely based on each batter's measured height (27% to 53.5% of height). This meant players had to be officially measured—shoes off, back against the wall.

For the first time, we have *actual* heights instead of the self-reported numbers teams have used for decades.

## Key Findings

- **711 players** analyzed
- **127 heights changed** (17.9%)
- **101 players shrunk**, 26 grew
- **Average shrinkage: 1.03 inches**

### Biggest Shrinkage

| Player | Old | New | Diff |
|--------|-----|-----|------|
| Bo Naylor | 6'0" | 5'9" | -3" |
| Michael Lorenzen | 6'3" | 6'1" | -2" |
| (99 more at -1") | | | |

### Notable Shrinkage

- Mookie Betts: 5'10" → 5'9"
- Alex Bregman: 5'11" → 5'10"
- Alec Bohm: 6'5" → 6'4"
- Byron Buxton: 6'2" → 6'1"

### Players Who Grew

- Max Muncy: 5'10" → 6'0" (+2")
- Elly De La Cruz: 6'5" → 6'6" (+1")

## Data Sources

- **2026 heights**: MLB Stats API (measured for ABS)
- **2025 heights**: Baseball Reference roster pages via Wayback Machine (pre-ABS listed heights)

## Files

- `index.html` - Interactive visualization
- `data.json` - Full dataset (JSON)
- `data.csv` - Full dataset (CSV)

## Author

[@ethanmlam](https://twitter.com/ethanmlam)

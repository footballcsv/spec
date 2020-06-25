# Football.CSV Format Spec (& Tests)

## Intro

One line is one match record. A datafile ALWAYS MUST start with a header. 
Example:

```
Team1,                FT,  HT,  Team2
Arsenal,              1-3, 1-1, Aston Villa
Liverpool,            1-0, 1-0, Stoke City
Norwich City,         2-2, 0-0, Everton
Sunderland,           0-1, 0-0, Fulham
Swansea City,         1-4, 0-2, Manchester United
West Bromwich Albion, 0-1, 0-0, Southampton
West Ham United,      2-0, 1-0, Cardiff City
Chelsea,              2-0, 2-0, Hull City
Crystal Palace,       0-1, 0-0, Tottenham Hotspur
Manchester City,      4-0, 2-0, Newcastle United 
...
```

## Headers

### Teams

- `Team 1`    - use for the "home" team
- `Team 2`    - use for the "away" or "visiting" team

### Scores

- `FT`    - full time score e.g. `1-3` or `4-0` etc.
- `HT`    - half time score e.g. `1-1` or `2-0` etc.
- `Score`   - use score if the score is "undetermined", that is, if you do NOT know if its fulltime (ft) or extra time (et) or penality etc.
...

### Dates & Times

- `Date`
- `Time`
...

### Rounds & Matchdays

- `Round` or `Matchday`
...


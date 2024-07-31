# DA_FootballData
Database for the Odds-, Events-Analysis
CSV-Files (Comma Separated Values)
Prefixes: (no Prefix) Bundesliga Values, Ligue1_ , PL_, SerieA_, LaLiga_

Group: "pivotDyn_tables_20XX"
  Resource aligning each table position for each team per matchday

Group: "inputs_20XX"
  edited; based on data downloaded from football-data.co.uk
  edits: added Match IDs, added Matchday, added Current Rank (Home Team and Away Team)
    additional scores: Historic (see Whitepaper), Median Odds, "Great Odds", Small Spread odds, Big Spread odds, Odds Higher tha Pinnacle
      "IF H -..." result 0 if lost
    column "If Higher than Pinnacle" contains figures for total profits (cost included!)

Group: "HistoryBetting_20XX"

"RanksUntil_2011" Teamname (Col. A) ,
  Bundesliga Ranks/Years 2002 - 20120 Col.s B-J - all teams in history pool 2002 - 2023
  Rank figure "22" (int) - team not in Bundesliga / season

"Teams_lookUp" -
  Bundesliga Ranks/Years 2002 - 20120 Col.s B-J - all teams in history pool 2002 - 2023
  Rank figure "22" (int) - team not in Bundesliga / season

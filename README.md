# FIP 16 v62 CAF

Edited with CM16 v2.0 beta 2 


## Installation

1. Install the fip16 v62 mod on your FIFA 16 (https://dl.fifa-infinity.com/fifa-16/fifa-infinity-patch-16-v6/).
2. Open fip16 version manager, select v62 CAF and apply 
3. Open CM16 editor, load the files and Regenerate BH (maybe it's not necessary). 
4. Download (Code >> Download ZIP) and replace the files in this repository on your FIFA 16 root folder.
5. Open CM16 editor again load the files and use the Regenerate BH function.
6. Start a new career (it doesn't work with an existing one)

## Why this exists?

Noticing the lacking of realism and the abuse of shortcuts made by EA, made me have a desire to rebuild the entire tournaments tree, to make it the most realistic possible. The FIP 16 CAF version was the most close to my vision that I found, so I decided to improve it, then this repository was born.

### Routes

FIFA WC Route:
- UEFA: 2024 WC Qualifiers top 15 nations
- CONCACAF: 2025 Gold Cup top 3 nations + 1 playoff
- AFC: 2024 WC Qualifiers top 3 nations + 1 playoff
- CONMEBOL: 2023 WC Qualifiers top 5 nations + 1 playoff
- CAF: 2025 AFCON top 4 nations
- OFC: New Zealand direct on playoffs

FIFA Club WC Route:
- UEFA: Champions League winner
- CONCACAF: Champions League winner
- AFC: Champions League winner
- CONMEBOL: Libertadores winner
- CAF: Champions League winner
- OFC: Auckland City direct on Round 1
- Home Country Team: Random between Saudi/Morocco/Japan/UAE

### Most important improvements made (TL/DR)

- MLS reworked to fix wrong advancements in final stages
- FIFA WC Asia Qualifiers enabled and working
- FIFA WC UEFA Qualifiers entire reworked, all nations playing and playoffs at the end
- UEFA Euro Qualifiers entire reworked, all nations playing and playoffs at the end
- FIFA WC Starting in 2022 with Playoff round
- ConcaChampions with 12 teams (Canada + Costa Rica) now working
- Copa Libertadores expanded to 32 teams with playoff round
- AFC Champions League expanded to 24 teams using Rest of the world (China,Japan,UAE,India), 6 groups + Round of 16
- Fixed TBD error: FIFA CWC G3: Winner Saudi/RSL + Special Teams Hosts (Japan, Marrocos, UAE) + Stadiums

## Selected Cups on fip16 tournaments manager

- Extra tournaments minus DENM,IRL,NORW,POL,SWE,SUI,RUS,ROU
- Compids 94/99

### Current used compdata spaces:

- Compids 94/99
- Compobj 1790/1809
- Advancement 3438/3549
- Tasks 791/800
- Settings 3750/3752
- Standings 5274/5278(5274)
- Initteams 256/366
- Schedule 6449/6995


## Fixes/modifications:
  
v62.007
- FIFA CWC table now is being generated at earlier DEC
  
v62.006
- GERM/ENGL adjusted possible conflicting dates with FIFA WC playoffs
- DENM/ROMA adjusted possible conflicting dates with FIFA WC dates
- **MLS reworked to fix wrong advancements in final stages**
- Revisited all leagues calendars to avoid any conflict with FIFA WC Playoff
- COLB Adjusted Apertura Final date
- MEXI Adjusted Clausura Final date
- Working even with dates during FIFA WC (no changes made): KORE/UNIT
- NORW/IREL/SWED extra dates added to avoid league ending with fewer games than they should have
- Changed FIFA WC Playoff games to 12/jun
- **Small fix ARGE Cup final date "conflict" with FIFA WC - 9/jun (Crashing starting new career)**

v62.005
- **FIFA WC Asia Qualifiers enabled and working**
- Ajusted "Colors" in group stage of all competitions
- FIFA WC slots: Conmebol +1, UEFA -1
- AFCON / Asian Cup / Copa America dates adjustment
- Changed AFCON and Asian Cup setup stage pots to be more realistic
- **FIFA WC UEFA Qualifiers entire reworked, all nations playing and playoffs at the end**
- EURO Qualifiers entire reworked, all nations playing and playoffs at the end
- Fine tuning AFC CL setup group stage for JAPAN/AUSTR/KOREA
- **FIFA WC Starting in 2022 with Playoff round**
- New Zealand removed from CONCACAF Gold Cup
- Added AFC Group stage Pots to make the draw more similar to real life 
- ASTR extra setup stage to better draw clubs to AFC CL
- Prize money defined for all clubs championships Finals
- CONCACAF Gold Cup Final game added
- Norway cup deleted
- Small calendar overhaul on SARB/KORE to avoid calendar conflicts
- Big overhaul on ASTR calendar to avoid conflicts 
- Small calendar overhaul on EGYP/SAFR/TUNI to avoid calendar conflicts
- FIFA CWC more balanced definition of host team between Japan/Saudi/Morroco

v62.004
- Failsafe config on UEFA CL and Libertadores to avoid TBD in rare case where a Rest of the world team wins the competition and gets automatic qualification to next year edition
- **ConcaChampions with 12 teams (Canada + Costa Rica) now working**
- Added extra setup stage on UNIT/COLB Leagues to define extra Continental comp. slots 
- Deleted DENM Cup and reduced DENM League Rankings table to free space to CONCAChampions Playoff round
- Improved Rounds draw on Libertadores to be identical to real life
- Improved Round of 16 draw on AFC Champions League + Stadiums
- Adjusted dates of CONMEBOL countries to avoid conflict with new Libertadores dates
- Reduced the excessive number of ranking tables slots in IREL and SWED to free space in tasks
- Increased slots in ranking tables for all CONMEBOL countries considering that the champion of Libertadores have guarantee slot next season
- Fixed Libertadores playoffs TBD after first season because of COLB playoffs qualified teams
- Reserved space for FIFA WC Playoff round
- **Fixed TBD error: Long term error on CONCAChampions because of getting 2 best teams from LigaMX, the same team won Apertura and Clausura demanding an extra option to fill the slots**
- Removed Rankings table from FIFA WC AFC Qual to free tasks space
- Deleted SWED cup to free enough spaces to avoid crashing when selecting pre-season tournament
- "Setup Stage > Special Standing Rules > Team Rating" for Libertadores
- Libertadores Final changed to KO1LEG
- "Setup Stage > Special Standing Rules > Previous Ranking" for "Copa Brasil" and "Copa Argentina"
- Playoff round added to Copa Libertadores
- **Copa Libertadores expanded to 32 teams**
- Deleted Polonese and Russian cups to have enough free compobj to use in other expansions
- FIFA CWC Setup Stage 2, trying to avoid a rare TBD when the host team and the AFC/CAF champions are the same.

v62.003
- AFCON and AFC Cup periodicity of 2 years (Only the results of the closer one before the WC will be used to qualify)
- BRAZ/ARGE calendar overhaul, avoided all date conflicts between championships
- Removed BELG Leagues Relegation Round, not being used. Adjusted final league date to avoid euro conflicts
- IREL removed confict date with euro clubs calendar
- NORW fixed end of the season in the first month
- COLB adjusted dates conflicting with FIFA CWC
- Fixed POLA cup semifinal missing one date
- Adjusted SCOT league qualification table colors
- Small adjustments on SWED cup calendar to avoid euro dates conflict 
- SWIT/TURK/RUSS/ROMA removed unused dates
- MEXI/UNIT/BRAZ/ARGE avoiding conflicts with International friendly dates
- COLB removed extra dates on Apertura, avoid conflicts with International friendly dates
- CHIL removed extra unused dates
- **AFC Champions League expanded to 24 teams using Rest of the world (China,Japan,UAE,India), 6 groups + Round of 16**
- Added extra clubs to CONCAChampions and Libertadores setup stage (preparing to expand). 
- Set Ranking Tables (Winners) of all Sulamerican leagues.
- Manually removed num_games=1 in settings.txt for International Friendlies to fix duplicated games

v62.002
- "Check Schedule Conflicts" enabled for all continental clubs competitions and FIFA CWC
- Austria: changed december league dates
- Belgium: changed cup and league december dates
- Added more dates to Egypt (WE PL) to avoid FIFA CWC date conflict
- Ireland: changed dates avoid FIFA CWC date conflict
- Netherlands/Norway/Poland: changed dates avoiding conflicts
- **Fixed TBD error: CM16 Europa League Setup Stage (Portuguese League champion)**
- African Cup of Nations first year in 2023, kept periodicity in 2 years
- Portugal/Spain changed december games dates to avoid conflicts
- **Fixed TBD error: Broken "Supercopa de Espana". Setup Stage G1, Ranking table "Copa del Rey" adjusted**
- Fixed CONCACAF Gold Cup dates, bigger gap between games
- Removed ENGL PL / FRAN L1 / GERM B1 / ITAL A december dates that conflicts with FIFA CWC
- Reduced number of dates on IREL League to avoid "end of the season" in the beginning
- SCOT/SWIT/TURK/ROMA ajusted dates
- Big overhaul on CONCACAF / MEXI / UNIT calendar and clubs that qualifies to ConcaChampions

v62.001
- **Fixed TBD error: CONCACAF champions setup stage G2: winners ligaMX and MLS**
- **Fixed TBD error: FIFA CWC G3: Winner Saudi/RSL + Special Teams Hosts (Japan, Marrocos, UAE) + Stadiums**
- Fixed all continental clubs competitions prize money

## Important info about editing:

- Reserving extra slots in league's Ranking tables is needed when the continental competition guarantees slot for the last champion, otherwise long term TBD can happen (not mandatory to define all slot teams, but it doesn't save space).  
- MLS using world cup dates, changes in CM16 on MLS calendar doesn't have any effects.
- Getting 2 best teams from a LEAGUE/CUP which has Final game cause TBD after the first season(in the first season filling the rankings table makes it work). Maybe the same team won more than one trophy, in this case an extra qualification rule is needed 
- Avoid access Intl Friendly/G1 screen on CM16 because it creates a num_games=1 line in settings.txt which duplicate games

## Issues: 

- Other Leagues screen crashing on ENGL when you're playing in a league of other continent (problem exists in the fip16 v62 CAF original) 
- A chance of conflict on FIFA CWC exists between the host team and the winners of AFC / CAF Champions league being the same teams, it's very rare, doesn't crash, cup still playable, no further action for now.
- CONCACAF Gold Cup not showing on tables full screen, same problem of AFC Asian Cup, still playable.

- v62 CAF Al Ahly (as saudi arabia national team manager): shows "Copa America" table instead of "AFC Asian Cup" table. Not crashing, competition still playable. (not showing on original version too)

## Future Features:

- Adjust prize money for all competitions
- Try code 4004 (random) for AFCON
- test tournaments in tournaments mode ASIAN CUP (verify the ids before execution):

```
in the compobj text assign it to a nation and select it in tournament mode.
1667,3,C960,TrophyName_Abbr15_950,1666

change the line above to the line below.
1667,3,C960,TrophyName_Abbr15_950,1505

settings.txt Remove INTERCUP parameters manually (First year, Peridiocity, Start Month)
850,asset_id,950
850,comp_type,CUP
850,match_matchimportance,100

load tournament mode and select saudi arabia. 
``` 
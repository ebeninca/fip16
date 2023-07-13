# FIP 16 v62 CAF

Edited with CM16 v2.0 beta 2 


## Installation

1. Install the fip16 v62 mod on your FIFA 16 (https://dl.fifa-infinity.com/fifa-16/fifa-infinity-patch-16-v6/).
2. Open fip16 version manager, select v62 CAF and apply 
3. Open CM16 editor, load the files and Regenerate BH (maybe it's not necessary). 
4. Copy and replace the files in this repository on your FIFA 16 root folder.
5. Open CM16 editor again load the files and use the Regenerate BH function.


## Selected Cups on fip16 tournaments manager

- Extra tournaments minus ROU,SUI,IRL
- Compids 99/99


## Fixes/modifications:

v62.003
- AFCON and AFC Cup periodicity of 2 years (Only the results of the closer one before the WC will be used to qualify)
- BRAZ calender overhaul, avoided all date conflicts between championships.

v62.002
- "Check Schedule Conflicts" enabled for all continental clubs competitions and FIFA CWC.
- Austria: changed december league dates
- Belgium: changed cup and league december dates
- Added more dates to Egypt (WE PL) to avoid FIFA CWC date conflict
- Ireland: changed dates avoid FIFA CWC date conflict
- Netherlands/Norway/Poland: changed dates avoiding conflicts
- Fixed TBD on CM16 Europa League Setup Stage (Portuguese League champion)
- African Cup of Nations first year in 2023, kept periodicity in 2 years
- Portugal/Spain changed december games dates to avoid conflicts
- Fixed broken "Supercopa de Espana", TBD error. Setup Stage G1, Ranking table "Copa del Rey" adjusted
- Fixed CONCACAF Gold Cup dates, bigger gap between games
- Removed ENGL PL / FRAN L1 / GERM B1 / ITAL A december dates that conflicts with FIFA CWC
- Reduced number of dates on IREL League to avoid "end of the season" in the beginning.
- SCOT/SWIT/TURK/ROMA ajusted dates
- Big overhaul on CONCACAF / MEXI / UNIT calendar and clubs that qualifies to ConcaChampions

v62.001
- CONCACAF champions setup stage G2: winners ligaMX and MLS
- FIFA CWC G3: Winner Saudi/RSL + Special Teams Hosts (Japan, Marrocos, UAE) + Stadiums
- Fixed all continental clubs competitions prize money


## Issues: 
 
- Canadian clubs on MLS doesn't participate in the US Open Cup, no further action for now.
- A chance of conflict on FIFA CWC exists between the host team and the winners of AFC / CAF Champions league being the same teams, it's very rare, doesn't crash, cup still playable, no further action for now.
- New Zealand is qualifying to WC through CONCACAF Gold Cup, no changes made on it.
- CONCACAF Gold Cup not showing on tables full screen, same problem of AFC Asian Cup, still playable.
- FIFA CWC Cup has been generated in AUG 26, Libertadores champion have to wait an entire year to participate, Is it possible to change this date to earlier DEC?

- v62 CAF Real Madrid (as ukraine national team manager): ukraine isn't in the euro qualifiers competition
- v62 CAF Al Ahly (as saudi arabia national team manager): shows "Copa America" table instead of "AFC Asian Cup" table. Not crashing, competition still playable. (not showing on original version too)
- v62 CAF Real Madrid (as USA national team manager): FIFA CWC, Usan Hyundai always winning AFC Champions League? something broken?


## Future Features:

** VERIFICAR SE TODOS AS LIGAS MODIFICADAS TEM TODOS OS JOGOS SENDO REALIZADOS, CONFLITOS DE CALENDARIO FAZENDO PARTIDAS SUMIREM

- Do a better use of the teams from Rest of the world in continental cups.
- test ligamx with different config qualy for concachampions
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


***** Test check schedule conflicts - LigaMX / Real Madrid / Flamengo
- Change dates on "Brasileirao" in december to avoid FIFA CWC date conflict
- Add more dates to Liga MX in december to avoid FIFA CWC date conflict

***** Enable World Cup in 2022 - Asian qualifying not been used, New Zealand qualifying through CONCACAF Gold Cup.
- Define a final game for Gold Cup

***** Try to simplify the setup stages to leave some free compobjs to be used for new competitions or expand existing competitions (maybe this is causing long term crashings) 
- Expand CONCACAF CHAMPIONS League to 16 teams
- Libertadores with 32 teams
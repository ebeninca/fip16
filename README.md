# FIP 16 v62 CAF

Edited with CM16 v2.0 beta 2 

## Installation

1. Install the fip16 v62 mod on your FIFA 16 (https://dl.fifa-infinity.com/fifa-16/fifa-infinity-patch-16-v6/).
2. Open Version manager, select v62 CAF and apply (maybe it's not necessary). 
3. Copy and replace the files in this repository on your FIFA 16 root folder.
4. Open CM16 editor load the files and use the Regenerate BH function.

## Selected Cups

- Extra tournaments minus ROU,SWI,IRL
- Compids 99/99

## Fixes/modifications:

v62.002
- "Check Schedule Conflicts" enable for all continental clubs competitions and FIFA CWC.
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

v62.001
- CONCACAF champions setup stage G2: winners ligaMX and MLS
- FIFA CWC G3: Winner Saudi/RSL + Special Teams Hosts (Japan, Marrocos, UAE) + Stadiums
- Fixed all continental clubs competitions prize money


## Issues: 

data alteradas na premier league geram fim de temporada no primeiro mes

- Retestar todas as copas desde a Austria pra ver se nao tem TBD

- test tournaments in tournaments mode ASIAN CUP:

in the compobj text assign it to a nation and select it in tournament mode.

1667,3,C960,TrophyName_Abbr15_960,1666

change the line above to the line below.

1667,3,C960,TrophyName_Abbr15_960,1505

load tournament mode and select saudi arabia. 
 
 
- A chance of conflict on FIFA CWC exists between the host team and the winners of AFC / CAF Champions league being the same teams, it's very rare, doesn't crash, cup still playable, no further action for now.
- New Zealand is qualifying to WC through CONCACAF Gold Cup, no changes made on it.
- CONCACAF Gold Cup not showing on tables full screen, same problem of AFC Asian Cup, still playable.
- Definir um jogo de final na Gold Cup, 

- v62 CAF Real Madrid (as ukraine national team manager): ukraine isn't in the euro qualifiers competition
- v62 CAF Al Ahly (as saudi arabia national team manager): shows "Copa America" table instead of "AFC Asian Cup" table. Not crashing, competition still playable. (not showing on original version too)
- v62 CAF Real Madrid (as USA national team manager): FIFA CWC, Usan Hyundai always winning AFC Champions League? something broken?


## Future Features:

***** Testar check schedule conflicts - LigaMX / Real Madrid / Flamengo
- Change dates on "Brasileirao" in december to avoid FIFA CWC date conflict
- Add more dates to Liga MX in december to avoid FIFA CWC date conflict

***** TESTAR SIMULACAO COPA DO MUNDO EM 2022 - Eliminatorias Asia não está sendo usada, Nova zelandia não é considerada / Setar selecoes no ranking das eliminatorias para gera a copa corretamente.

***** Try to simplify the setup stages to leave some free compids to be used for new competitions or expand existing competitions (maybe this is causing long term crashings)
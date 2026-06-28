# South Korea 2026 FIFA World Cup Performance Analysis: Why Did the Results Fall Short?

This project analyzes South Korea's 2026 FIFA World Cup group-stage performance using match-level football statistics, including expected goals (xG), possession, shots, shots on target, big chances, and touches in the opposition box.

## Data Source

The dataset was manually collected from FotMob match statistics pages for South Korea's 2026 FIFA World Cup group-stage matches.

Sources:

* [South Korea vs Czechia - FotMob Match Stats](https://www.fotmob.com/matches/south-korea-vs-czechia/273opa#4667752:tab=stats)
* [Mexico vs South Korea - FotMob Match Stats](https://www.fotmob.com/matches/mexico-vs-south-korea/1qpvav#4667754)
* [South Africa vs South Korea - FotMob Match Stats](https://www.fotmob.com/matches/south-africa-vs-south-korea/1ncyls#4667756)

## Research Question

Did South Korea underperform because of poor finishing, weak chance creation, tactical inefficiency, defensive vulnerability, or a combination of these factors?

## Tools Used

* Python
* pandas
* SQLite / SQL
* matplotlib
* Google Colab

## Key Findings

* South Korea scored 2 goals from 4.11 expected goals, producing a finishing gap of -2.11.
* South Korea generated more total shots than its opponents, 32 vs 28.
* South Korea produced higher xG per shot than its opponents, 0.128 vs 0.090.
* Despite averaging 62.7% possession, South Korea did not consistently convert possession into goals or positive match results.
* The data suggests that finishing and attacking efficiency were more visible issues than being completely outplayed.

## Project Structure

* `south_korea_2026_worldcup_performance_analysis.ipynb`: Main analysis notebook
* `korea26.csv`: Match-level dataset

## Limitations

This project uses match-level data from three group-stage matches. It cannot directly prove coaching quality, tactical preparation, player selection, or broader organizational causes. Further analysis would require player-level data, shot locations, lineup/substitution data, and event-level tactical data.

## Future Work

Future analysis could include player-level xG, shot location analysis, pass maps, progressive passing data, substitution timing, and tactical event data.

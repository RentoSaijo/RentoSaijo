## About

### ✉️ [Email](mailto:rentosaijo0527@gmail.com) | [LinkedIn](https://www.linkedin.com/in/rentosaijo/) | [X](https://x.com/RentoSaijo) | [YouTube](https://www.youtube.com/@RentoSaijo)
I build hockey analytics from the data layer up. I created nhlscraper, a CRAN R package with 5,000+ downloads covering 125+ NHL/ESPN endpoints. During my NHL Stats R&D internship, I helped refine a 71-value puck-touch taxonomy and built an R Shiny/JavaScript tracking system with 100+ validation rules. Across five NHL games, it tripled tracking throughput and prevented roughly 500 detectable data-entry errors per game. I study Statistics & Data Science and Computer Science at Connecticut College and am joining Clear Sight Analytics as a 2026–27 Analytics Engineer.

## Experience

### 🏒 Analytics Engineer @ [Clear Sight Analytics](https://www.csahockey.com) | R / SQL / Power BI
To be added.

### 🏒 Intern, Stats R&D @ [National Hockey League](https://www.nhl.com) | R / SQL / JavaScript
Co-improved a 71-value puck-touch taxonomy spanning 25 actions, 9 touch types, and 37 outcomes, testing 15 V1-to-V2 revisions and documenting definitions, clarifications, and standards for future trackers and auditors. Engineered an R Shiny/JavaScript tracker app backed by SQLite and Parquet with 100+ row- and sequence-level validation rules, outcome inference, and synchronized visualizers; then, led 3 user training sessions for the app. Deployed the system to complete ground-truth tracking for 5 NHL games, tripling the previous workflow’s throughput and eliminating ~500 detectable human-errors per game.

## Projects

### 🏒 [nhlscraper](https://github.com/RentoSaijo/nhlscraper) | R / C / Developer Tools
I created and maintain nhlscraper, an [R package](https://rentosaijo.github.io/nhlscraper/) that makes NHL and ESPN data more accessible by scraping, cleaning, and analyzing data from 125+ API endpoints. Since publishing it on [CRAN](https://cran.r-project.org/package=nhlscraper), the package has surpassed 5,000 downloads, been added to the [SportsAnalytics CRAN Task View](https://cran.r-project.org/view=SportsAnalytics), and appeared in academic papers and course materials. I also reverse-engineered more than 50 undocumented NHL EDGE endpoints and built native C routines that accelerate play-by-play and shift-processing workflows by up to 167× while preserving reliable R fallbacks.

### 🏒 [rentosrink](https://github.com/RentoSaijo/rentosrink) | Python / R
I built and deployed Rento’s Rink, a Python and Streamlit [NHL analytics platform](https://rentosrink.streamlit.app/skater_free_agents) used by more than 1,000 people to explore skater and goalie shot maps, compare player and team performance through xG-based rankings, evaluate free agents, and generate contract scenarios. Behind the interface, I developed multi-season R data pipelines and a leakage-controlled, six-game-state [xG system](https://rentosrink.streamlit.app/expected_goal) that selects between XGBoost and LightGBM models, alongside [contract models](https://rentosrink.streamlit.app/contract_projection) trained on 5,394 historical deals using 337 engineered features and achieving an average held-out error of 0.61 percentage points of the salary cap.

### ⛏️ [bedrocktrader](https://github.com/RentoSaijo/bedrocktrader) | R
Minecraft: Bedrock Edition stores villager trading as nested random-generation rules rather than the concrete offers players see. I created bedrocktrader, an [R package](https://rentosaijo.github.io/bedrocktrader/) that converts Mojang’s pinned source tables into three probability-aware views covering 281 trade combinations, 2,787 item specifications, and 30,592 exact price-and-item offers across 13 professions. I also derived an [analytical engine](https://github.com/RentoSaijo/bedrocktrader/blob/main/other/math.pdf) that accounts for trade selection, repeated source entries, biome and dimension restrictions, emerald prices, and complete enchantment sets without simulation; for example, the package calculates a 2.79% chance that a fully unlocked librarian offers Mending for at most 26 emeralds.

## Competitions

### 🏒 [CMSAC Reproducible Research Competition 2026](https://github.com/RentoSaijo/FFvFF) | R

An NHL icing can trap five tired defenders on the ice while giving the attacking coach a choice: keep the current unit or send out fresh skaters. I reconstructed 19,590 icing situations from public play-by-play, lineup, roster, and shift data, then used matched target-trial emulations to test whether changing personnel creates a shot attempt within 10 seconds. Replacing all five skaters produced an estimated 2.22-percentage-point advantage across 1,124 matched pairs (95% CI: −1.55 to 5.99), while making any change produced a 2.12-point estimate across 3,628 pairs (95% CI: 0.10 to 4.14), although the latter weakened after accounting for team-season dependence.

### 🏒 [HALO Hackathon 2026](https://github.com/RentoSaijo/HALO2026) | R
I built an end-to-end R pipeline combining AHL player-tracking data with XGBoost and LightGBM models to analyze established 5-on-4 offensive-zone play. I developed Attempted Exploitable Mismatch per State (AEM/state), a coaching-focused metric that measures whether power-play units recognize and attack high-value openings. Across 32 teams, AEM/state correlated with scoring at r = 0.442 and increased team-level explanatory R² from 0.281 to 0.346 beyond xG alone, while revealing actionable puck-movement patterns associated with creating mismatches.

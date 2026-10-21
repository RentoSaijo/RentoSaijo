## About

### ✉️ [Email](mailto:rentosaijo0527@gmail.com) | [LinkedIn](https://www.linkedin.com/in/rentosaijo/) | [X](https://x.com/RentoSaijo) | [YouTube](https://www.youtube.com/@RentoSaijo)
I build hockey analytics from the data layer up. I created nhlscraper, a CRAN R package with 5,000+ downloads covering 125+ NHL/ESPN endpoints. During my NHL Stats R&D internship, I helped refine a 71-value puck-touch taxonomy and built an R Shiny/JavaScript tracking system with 100+ validation rules; across 5 NHL games, it tripled tracking throughput and prevented roughly 500 detectable data-entry errors per game. I study Statistics & Data Science and Computer Science at Connecticut College and am joining Clear Sight Analytics as a 2026–27 Analytics Engineer.

## Experience

### 🏒 Analytics Engineer @ [Clear Sight Analytics](https://www.csahockey.com) | R / SQL / Power BI
To be added.

### 🏒 Intern, Stats R&D @ [National Hockey League](https://www.nhl.com) | R / SQL / JavaScript
Co-improved a 71-value puck-touch taxonomy spanning 25 actions, 9 touch types, and 37 outcomes, testing 15 V1-to-V2 revisions and documenting definitions, clarifications, and standards for future trackers and auditors. Engineered an R Shiny/JavaScript tracker app backed by SQLite and Parquet with 100+ row- and sequence-level validation rules, outcome inference, and synchronized visualizers; then, led 3 user training sessions for the app. Deployed the system to complete ground-truth tracking for 5 NHL games, tripling the previous workflow’s throughput and eliminating ~500 detectable human-errors per game.

## Projects

### 🏒 [nhlscraper](https://github.com/RentoSaijo/nhlscraper) | R / C / Developer Tools
Created and maintain nhlscraper, an [R package](https://rentosaijo.github.io/nhlscraper/) that makes NHL and ESPN data more accessible by scraping, cleaning, and analyzing data from 125+ API endpoints. Since publishing it on [CRAN](https://cran.r-project.org/package=nhlscraper), the package has surpassed 5,000 downloads, been added to the [SportsAnalytics CRAN Task View](https://cran.r-project.org/view=SportsAnalytics), and appeared in academic papers and course materials. Reverse-engineered more than 50 undocumented NHL EDGE endpoints and built native C routines that accelerate play-by-play and shift-processing workflows by up to 167× while preserving reliable R fallbacks.

### ⛏️ [bedrocktrader](https://github.com/RentoSaijo/bedrocktrader) | R
Created bedrocktrader, an [R package](https://rentosaijo.github.io/bedrocktrader/) for analyzing villager trading in Minecraft: Bedrock Edition, where nested random-generation rules determine which items and prices players are offered. Translated Mojang’s pinned source tables into three probability-aware views covering 281 trade combinations, 2,787 item specifications, and 30,592 exact price-and-item offers across 13 professions. Derived an [analytical engine](https://github.com/RentoSaijo/bedrocktrader/blob/main/other/math.pdf) that accounts for trade selection, repeated source entries, biome and dimension restrictions, emerald prices, and complete enchantment sets without simulation; for example, the package calculates a 2.79% chance that a fully unlocked librarian offers Mending for at most 26 emeralds.

## Conferences

### 🏒 [CSAS 2027: NHL Screen Assists](https://github.com/RentoSaijo/NHL_ScreenAssists) | R
Developed an R pipeline to estimate NHL screen assists from public goal-replay tracking, crediting teammates who obstruct the goalie’s view on scoring plays. Achieved 92.60% precision and 73.21% recall for conservative player attribution against independent Clear Sight Analytics annotations on the reserved 2025–26 evaluation set. Built an [interactive explorer](https://rentosaijo.github.io/NHL_ScreenAssists/) with player rankings, playing-time rates, and animated replays for every credited goal. The [full paper](https://rentosaijo.github.io/NHL_ScreenAssists/reports/paper.pdf) also examines screening’s association with scoring through a separate mixed-effects analysis.

### 🏒 [CMSAC Reproducible Research Competition 2026](https://github.com/RentoSaijo/CSAx) | R
Co-developed calibrated size above expected (CSAx), a frame-relative measure of how “big” NHL forwards play, using 10 contact and interior-shot features across 1,763 forward-seasons. Among forwards in comparable roles, one standard deviation higher CSAx was associated with 22% higher adjusted odds of logging at least 300 NHL minutes the following season. The [full paper](https://github.com/RentoSaijo/CSAx/blob/main/reports/paper_cmsacrrc/paper_cmsacrrc.pdf) also examines scouting reports, contracts, and playoff availability.

### 🏒 [HALO Hackathon 2026](https://github.com/RentoSaijo/HALO2026) | R
Built an end-to-end R pipeline combining AHL player-tracking data with XGBoost and LightGBM models to analyze established 5-on-4 offensive-zone play. Developed Attempted Exploitable Mismatch per State (AEM/state), a coaching-focused metric that measures whether power-play units recognize and attack high-value openings. Across 32 teams, AEM/state correlated with scoring at r = 0.442 and increased team-level explanatory R² from 0.281 to 0.346 beyond xG alone. The [full paper](https://github.com/RentoSaijo/HALO2026/blob/main/RentoSaijo_HALO_Hackathon_2026_Report.pdf) also identifies actionable puck-movement patterns associated with creating mismatches.

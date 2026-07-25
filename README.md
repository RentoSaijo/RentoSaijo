## About

### ✉️ [Email](mailto:rentosaijo0527@gmail.com) | [LinkedIn](https://www.linkedin.com/in/rentosaijo/) | [X](https://x.com/RentoSaijo) | [YouTube](https://www.youtube.com/@RentoSaijo)
I’m a Statistics & Data Science and Computer Science student at Connecticut College and a sports analytics builder focused on turning raw data into tools teams can actually use. My work combines statistical modeling, software engineering, and on-ice perspective: I’m the author/maintainer of nhlscraper, an R package for collecting, cleaning, modeling, and visualizing NHL/ESPN data; I’ve built expected-goals models, interactive dashboards, and D3 visualizations to study shot quality, player value, and tactical decision-making; and I’ve applied that toolkit professionally as a Stats R&D Intern at NHL. I’m especially interested in hockey data infrastructure, probabilistic modeling, player evaluation, and decision tools that help move analysis from “what happened?” to “what should we do next?”

## Projects

### 🏒 [nhlscraper](https://github.com/RentoSaijo/nhlscraper) | R / C / Developer Tools
I created and maintain nhlscraper, an [R package](https://rentosaijo.github.io/nhlscraper/) that makes NHL and ESPN data more accessible by scraping, cleaning, and analyzing data from 125+ API endpoints. Since publishing it on [CRAN](https://cran.r-project.org/package=nhlscraper), the package has surpassed 5,000 downloads, been added to the [SportsAnalytics CRAN Task View](https://cran.r-project.org/view=SportsAnalytics), and appeared in academic papers and course materials. I also reverse-engineered more than 50 undocumented NHL EDGE endpoints and built native C routines that accelerate play-by-play and shift-processing workflows by up to 167× while preserving reliable R fallbacks.

### 🏒 [rentosrink](https://github.com/RentoSaijo/rentosrink) | Python / R
I built and deployed Rento’s Rink, a Python and Streamlit [NHL analytics platform](https://rentosrink.streamlit.app/skater_free_agents) used by more than 1,000 people to explore skater and goalie shot maps, compare player and team performance through xG-based rankings, evaluate free agents, and generate contract scenarios. Behind the interface, I developed multi-season R data pipelines and a leakage-controlled, six-game-state [xG system](https://rentosrink.streamlit.app/expected_goal) that selects between XGBoost and LightGBM models, alongside [contract models](https://rentosrink.streamlit.app/contract_projection) trained on 5,394 historical deals using 337 engineered features and achieving an average held-out error of 0.61 percentage points of the salary cap.

### 🏀 [NBAxP](https://github.com/RentoSaijo/rentosrink) | JavaScript / R
NBAxP is a project where I turned raw NBA shot data into an interactive “shot value map” for each team. I scraped and cleaned ~700,000 shots, built an [expected-points model](https://rentosaijo.github.io/NBAxP/README.html) using shot context, and visualized results by court region in a D3-powered [dashboard](https://rentosaijo.github.io/NBAxP/) with interactive filters and hover tooltips for team-to-team comparisons.

## Competitions

### 🏒 [CMSAC Reproducible Research Competition](https://github.com/RentoSaijo/FFvFF) | R

I built a fully reproducible R pipeline to study whether attacking line changes after an opponent icing create immediate offense. Using public play-by-play, event-lineup, roster, and shift data, I reconstructed 19,590 eligible NHL icings and emulated target trials with propensity-score matching. Among 1,124 matched wholesale-change pairs, replacing all five skaters produced an estimated 2.22-percentage-point increase in 10-second attacking-attempt probability (95% CI: −1.55 to 5.99); a separate 3,628-pair analysis of any change estimated a 2.12-point increase (95% CI: 0.10 to 4.14), though that evidence weakened under team-season dependence.

### 🏒 [HALO Hackathon 2026](https://github.com/RentoSaijo/HALO2026) | R
I built an end-to-end R pipeline combining AHL player-tracking data with XGBoost and LightGBM models to analyze established 5-on-4 offensive-zone play. I developed Attempted Exploitable Mismatch per State (AEM/state), a coaching-focused metric that measures whether power-play units recognize and attack high-value openings. Across 32 teams, AEM/state correlated with scoring at r = 0.442 and increased team-level explanatory R² from 0.281 to 0.346 beyond xG alone, while revealing actionable puck-movement patterns associated with creating mismatches.

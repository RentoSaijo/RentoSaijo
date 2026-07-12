## About

### ✉️ [Email](mailto:rentosaijo0527@gmail.com) | [LinkedIn](https://www.linkedin.com/in/rentosaijo/) | [X](https://x.com/RentoSaijo) | [YouTube](https://www.youtube.com/@RentoSaijo)
I’m a Statistics & Data Science and Computer Science student at Connecticut College and a sports analytics builder focused on turning raw data into tools teams can actually use. My work combines statistical modeling, software engineering, and on-ice perspective: I’m the author/maintainer of nhlscraper, an R package for collecting, cleaning, modeling, and visualizing NHL/ESPN data; I’ve built expected-goals models, interactive dashboards, and D3 visualizations to study shot quality, player value, and tactical decision-making; and I’ve applied that toolkit professionally as a Stats R&D Intern at NHL. I’m especially interested in hockey data infrastructure, probabilistic modeling, player evaluation, and decision tools that help move analysis from “what happened?” to “what should we do next?”

## Projects

### 🏒 [nhlscraper](https://github.com/RentoSaijo/nhlscraper) | R / C / Developer Tools
I created and maintain nhlscraper, an [R package](https://rentosaijo.github.io/nhlscraper/) that makes NHL and ESPN data more accessible by scraping, cleaning, and analyzing data from 125+ API endpoints. Since publishing it on [CRAN](https://cran.r-project.org/package=nhlscraper), the package has surpassed 5,000 downloads, been added to the [SportsAnalytics CRAN Task View](https://cran.r-project.org/view=SportsAnalytics), and appeared in academic papers and course materials. I also reverse-engineered more than 50 undocumented NHL EDGE endpoints and built native C routines that accelerate play-by-play and shift-processing workflows by up to 167× while preserving reliable R fallbacks.

### 🏒 [rentosrink](https://github.com/RentoSaijo/rentosrink) | Python / R
I built and deployed Rento’s Rink, a multi-page [NHL analytics platform](https://rentosrink.streamlit.app/skater_free_agents) in Python and Streamlit that has attracted more than 1,000 users. The app transforms complex hockey data into interactive shot analyses, player and team expected-goals rankings, and contract projections. Its contract models use XGBoost and LightGBM with 337 leakage-safe features engineered from 5,394 historical contracts, predicting held-out contract values within an average of 0.61 percentage points of the salary cap.

### 🏀 [NBAxP](https://github.com/RentoSaijo/rentosrink) | JavaScript / R
NBAxP is a project where I turned raw NBA shot data into an interactive “shot value map” for each team. I scraped and cleaned ~700,000 shots, built an [expected-points model](https://rentosaijo.github.io/NBAxP/README.html) using shot context, and visualized results by court region in a D3-powered [dashboard](https://rentosaijo.github.io/NBAxP/) with interactive filters and hover tooltips for team-to-team comparisons.

## Competitions

### 🏒 [HALO Hackathon 2026](https://github.com/RentoSaijo/HALO2026) | R
This submission focuses on a coaching-facing question in established 5v4 offensive-zone power-play play: how can we quantify quality beyond xG by measuring whether a unit creates and actually attacks exploitable mismatches? To answer that, I engineered Attempted Exploited Mismatch per State (AEM/state), a metric that combines threat modeling for puck-carriers and non-carriers with coverage geometry and a 1.5-second decision window. I then validated the metric against team outcomes, showing that AEM/state remained positively associated with PP goals/60 and added explanatory value beyond xG/60 alone. The project also examined how those mismatches are created by analyzing short puck-movement progressions, finding that most lift came from concise 2–3 event chains rather than long, harmless circulation.

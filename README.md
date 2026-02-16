# T20-World-Cup-Match-Preview-Playing-XI-Analytics
This project is an end-to-end cricket analytics dashboard designed to generate pre-match insights for T20 World Cup matches. It dynamically selects the optimal Playing XI for each team, compares Team A vs Team B across match phases (Powerplay, Middle, Death), incorporates venue conditions, and estimates win probability using data-driven models built in Python and Power BI.

🚀 Key Features

Automated Playing XI Selection:
Generates the best squad for each team using player roles, batting position, bowling role, and team composition rules (captain, wicketkeeper, bowling depth).

Phase-wise Team Comparison:
Compares teams across Powerplay, Middle, and Death overs using batting and bowling strength metrics derived from scaled player statistics.

📊 Dashboard Capabilities

Team A vs Team B match comparison (interactive slicers)

Optimized Playing XI visualization for both teams

Phase-wise batting & bowling strength charts

Venue impact insights (average scores, death runs, chasing %)

Dynamic team strength cards (strike rate, economy, averages)

Data-driven win probability visualization

🧠 Methodology

Player stats (batting & bowling) are min-max scaled for fairness

Role-based scoring (Opener, Middle Order, Finisher, Bowler)

Team strength computed from aggregated batting and bowling metrics

Logistic function applied on strength difference to estimate win probability

Disconnected slicers in Power BI used for true Team A vs Team B comparison logic

🗂️ Data Tables Used

player_data – Player roles, batting position, team structure

batting_stats – Strike rate, averages, phase strike rates, boundary %

bowling_stats – Economy, wickets, dot ball %, phase economy

venue_stats – Venue scoring patterns and match conditions

team_stats – Aggregated team strength metrics

🛠️ Tech Stack

Python (Pandas, NumPy) – Data processing & feature engineering

Power BI – Interactive dashboard & DAX modeling

DAX – Dynamic measures for comparison

Data Modeling – Disconnected slicers, comparison tables, dynamic measures

📈 Use Case

This system acts as a match preview analytics engine for T20 cricket, enabling analysts, fans, and strategists to simulate matchups, evaluate team strengths, and make data-driven predictions before a game.

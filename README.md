

2025 Fantasy PPR-Breakout Notebook
A data-first tool for finding rising-volume producers in your upcoming PPR drafts. Every cell is 100 % reproducible and free to reuse.

🏗 What it does
Scrapes ESPN free-agents → projected 2025 PPR points per ADP.

Backfills 3 years of PPR history from Pro-Football-Reference.

Flag every player who is climbing in PPR:

2-year streak → 23 → 24 rise
3-year streak → 22 → 23 → 24 climb

Returns rankable, position-agnostic tables ready for cheat-sheet export.

📁 File Map

File / Folder	Purpose
PPR-Gainers.ipynb	Full run-and-tell Jupyter notebook
FantasyData*.csv	2022–2024 raw PFR stat files
requirements.txt	Python deps (pandas, espn-api)
README.md	You are here
🖥 Quick Start
Clone

bash
git clone https://github.com/YOU/Rising-PPR-Draft-Guide.git
cd Rising-PPR-Draft-Guide
Install deps

bash
pip install -r requirements.txt
Add credentials
Optional: replace espn_s2 / swid in the notebook with your private ESPN API cookie.

Run

bash
jupyter notebook PPR-Gainers.ipynb
# Execute all cells → export CSV for your cheat-sheet.
📈 Key Outputs
Inside the notebook you’ll find:

Top 3-Year PPR Gainers: players who improved every season.
Top 2-Year Risers: players who jumped only last year (rookies welcome).
Export-ready CSVs for WR/RB/TE tables ranked by ∆ PPR 24 vs 23.
Example extract:


Player	Pos	PPR-22	PPR-23	PPR-24	∆23-24
Jameson Williams	WR	—	78.8	201.3	+122.5
David Montgomery	RB	178.0	210.5	254.7	+44.2
Jaylen Warren	RB	89.9	154.4	191.6	+37.2
🎯 How to use for 2025 drafts
Filter position → copy CSV → import into your sleeper/dynasty sheet.
Target 3-year risers late; their trend rarely reverses.
Use 2-year streaks for upside fliers in rookie/FA drafts.
🤝 Contributions & Issues
PRs welcome for new stats/target data sources.
Open a GitHub issue for bugs or feature requests.
⚖ License
MIT — use, fork, remix. Just keep the attribution link.


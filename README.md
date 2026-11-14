🗳️ Lok Sabha Election 2024 – Power BI Dashboard

An interactive Power BI dashboard analysing the 2024 Indian General (Lok Sabha) Election results – seats won, vote share, voting mode (EVM vs Postal), NOTA votes and constituency-level winners, with state-wise map exploration.

Author: Anant Singh

📸 Preview

Add screenshots of your dashboard pages here, e.g.

Main Dashboard Map View

✨ Features
KPI cards – Total Constituencies, Total Votes, BJP Seats Won, Congress (INC) Seats Won, Others, % EVM Votes, % Postal Votes, Total NOTA Votes
Top 5 Parties by Seats – column chart
Total Votes by Party – donut chart
Constituency table – Winner MP, Winner Party, Winning Margin %, Trailing Party, with party colour coding
Interactive maps – state and constituency boundary maps (custom TopoJSON/GeoJSON shape maps of India)
Slicers – filter by State and Constituency
Tooltip pages – hover to see party vote share (donut) and NOTA vote % trend (line chart)
Custom visuals styling with Election Commission of India branding
📑 Report Pages
Page	Description
Page 1	Main dashboard – KPIs, top parties, vote share, winners table
Page 2	Tooltip – party-wise vote donut (hidden)
Page 3	Map view – state-wise selection with KPIs
Page 4	Map view – constituency-level exploration
Page 5	Tooltip – NOTA vote % line chart (hidden)
Page 6	Decorative / background page
🧮 Data Model
Fact table: sheet1 – constituency-wise election results (state, constituency, constituency type, party, candidate, votes, EVM/postal votes, margin)
Measures table: Key Measures – DAX measures such as:
Total Constituencies, Total Votes
BJP Seats Won, Congress Seats Won, Others seat, Seats Won
% EVM Votes, % Postal Votes
Total Votes for NOTA, NOTA Vote %
Winner Party, Winner MP, Trailing Party, Winning Margin %
Total Votes by Party, PartyColor

⚠️ Update this section with your exact data source (e.g. Election Commission of India / Kaggle dataset) and any DAX you want to showcase.

🛠️ Tools Used
Power BI Desktop (data modelling, DAX, visuals)
DAX for measures
Power Query for data cleaning
Custom shape maps (India states & constituencies)
🚀 How to Use
Clone or download this repository
bash
git clone https://github.com/<your-username>/<repo-name>.git
Install Power BI Desktop (free, Windows only)
Open election_dashboard_by_Anant_singh.pbix
Use the slicers and click on the map to explore results
📂 Repository Structure
├── election_dashboard_by_Anant_singh.pbix   # Power BI report
├── screenshots/                             # Dashboard images
└── README.md
📊 Key Insights

Add your findings here, for example:

Which party won the most seats
States with highest NOTA votes
Closest and biggest winning margins
EVM vs postal vote share
📬 Contact

Anant Singh

GitHub: @your-username
LinkedIn: your-link

⭐ If you found this useful, give the repo a star!

# � 2025 Fantasy Football Player Performance Analysis  
**Identify PPR Breakouts Using Historical Trends and ADP**  

---

## 🧩 About This Project  
This repository contains a **Jupyter Notebook** for analyzing fantasy football player performance from 2022–2024 and identifying **players gaining PPR share** to target in 2025 drafts. All data is sourced from **Pro Football Reference** and the **ESPN API**.  

---

## 🚀 Key Features  
- **Identifies 2024 breakouts** using 2022–2024 PPR history.  
- Highlights **3-year PPR risers** (improved every season) and **2-year streakers**.  
- **ADP Value Filter** to find players over/underdrafted relative to 2024 performance.  
- Export-ready player rankings for WR, RB, and TE categories.  

---

## 🧭 File Structure  

| File/Folder | Description |  
|--------------|-------------|  
| `PPR-Gainers.ipynb` | Core notebook with analysis pipeline |  
| `FantasyData2022_clean.csv`<br>`FantasyData2023_clean.csv`<br>`FantasyData2024_clean.csv` | Historical PPR stat data (2022–2024) |  
| `requirements.txt` | Python dependencies (`pandas`, `espn-api`, etc.) |  
| `README.md` | This file |  

---

## 🛠️ Setup Instructions  

1. **Clone the repo**:  
   ```bash
   git clone https://github.com/andrew-shimshock/Fantasy-Football-Player-Performance-Analysis-Notebook.git
   cd Fantasy-Football-Player-Performance-Analysis-Notebook

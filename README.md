# Global Olympic Sports Performance Analysis

A Tableau project that analyzes Olympic athlete data to show medal distribution, participation by country, and participation across sports. The dashboard is also shown on a small Flask website.

## Objective
To understand how medals are distributed, which countries take part the most, and which sports are the most popular.

## Tools Used
Tableau (Desktop / Public), Python (Flask), HTML, GitHub

## Visualizations
1. **Medal Analysis**: Gold, Silver and Bronze medal records
2. **Olympic Participation by Country**: participation by NOC code (top 10)
3. **Sports Participation**: participation in each sport (top 10)

## Key Findings
- **Medals:** Gold has 13,372 records, Bronze 13,295 and Silver 13,116, so the three are very close.
- **Countries:** USA has the highest participation, followed by FRA and GBR.
- **Sports:** Athletics leads with 35,624 entries, then Gymnastics (26,707) and Swimming (23,195).

## Dashboard and Story
The dashboard combines all three charts on one screen and is published on Tableau Public. The Tableau Story presents the dashboard with a short caption.

## Website (Flask)
A simple Flask website shows the project description and the embedded Tableau Public dashboard (`app.py` and `templates/index.html`).

To run it:
```
python -m pip install flask
python app.py
```
Then open `http://127.0.0.1:5000` in your browser. An internet connection is needed to load the dashboard.

## Project Files
| File | Description |
|---|---|
| `README.md` | Project description and instructions |
| `Global_Olympic_Sports_Performance_Analysis.twbx` | Packaged Tableau workbook |
| `Project_Documentation_Global_Olympic_Sports_Performance_Analysis.pdf` | Step-by-step project documentation |
| `Brainstorm_and_Idea_Prioritization.pdf` | Ideation phase document |
| `Web_integration_output.pdf` | Output of the Flask website |
| `app.py` | Flask application |
| `templates/index.html` | Website page with the embedded dashboard |
| `screenshots/` | Dashboard and story screenshots |
| `demo-link.txt` | Demo video / Tableau Public link |

## How to Open the Tableau Workbook
1. Download the `.twbx` file from this repository.
2. Open it in Tableau Desktop or Tableau Public.
3. Open the dashboard and story tabs.

## Demo
- Demo video: https://drive.google.com/file/d/1DZn4FMMIDcMB70IDuICN4RwdANzRmoKO/view?usp=sharing

## Notes
- The charts count records (athlete-event entries), not unique athletes.
- NOC means National Olympic Committee code.

## Author
Yashvi Agrawal, Medicaps University

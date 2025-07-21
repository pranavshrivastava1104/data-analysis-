# data-analysis-

<h1 align="center">🍿 Netflix Data Visualizations</h1>

<p align="center">
  <img src="C:\Users\Pranav\Downloads\data-analysis--main\data-analysis--main\netfix pic 4 .png" />
  <img src="C:\Users\Pranav\Downloads\data-analysis--main\data-analysis--main\netflix pic 2.png" />
  <img src="C:\Users\Pranav\Downloads\data-analysis--main\data-analysis--main\netflix pic 3.png" />
  <img src="C:\Users\Pranav\Downloads\data-analysis--main\data-analysis--main\netflix pic 5.png" />
</p>

> A story‑driven exploratory analysis of **Netflix Movies & TV Shows**  
> (34 k+ titles → cleaned, crunched & visualized).

---

## ✨ Quick Glance

| Sneak Peek | Insight |
|------------|---------|
| <img src="C:\Users\Pranav\Downloads\data-analysis--main\data-analysis--main\netfix pic 4 .png" height="120"/> | **Director** column is blank 1⁄3 of the time − data cleaning is a must! |
| <img src="images/country_split.png" height="120"/> | 🇺🇸 USA rules in raw count, 🇮🇳 India is #2 & UK #3 |
| <img src="images/ratings_dist.png" height="120"/> | TV‑MA dominates – Netflix isn’t just kids’ stuff 😉 |
| <img src="images/additions_over_time.gif" height="120"/> | Explosive catalogue growth after 2015, despite a 2020 dip |



---

## 🗂️ Repository Structure

## 🔧 Setup & Run

```bash
# 1. Clone repo & enter
git clone https://github.com/<you>/netflix-viz.git
cd netflix-viz

# 2. Create env (conda or venv)
conda env create -f env.yml
# OR
python -m venv .venv && source .venv/bin/activate
pip install -r requirements.txt

# 3. Launch the notebook
jupyter lab notebooks/netflix-data-visualization.ipynb


## 📈 Key Takeaways

- **Content Boom:** Catalogue size more than **tripled** between *2015 – 2020*, but growth cooled in **2021**.

- **Global Shift:** Non‑US share rises every year; **India** & **South Korea** spike thanks to local originals.

- **Rating Trends:** **TV‑MA** titles lead, reflecting Netflix’s shift toward mature audiences.

- **Genre Mix:** **Drama** & **Comedy** still rule, but **Documentaries** punch above their count in view‑hours.

- **Release Lag:** Median lag is ≈ **2 years**, yet **15 %** of titles hit Netflix within **3 months** of release.



## 🛠️ Tech Stack

| Layer            | Tools                                                       |
|------------------|-------------------------------------------------------------|
| **Data Wrangling** | `pandas`, `numpy`                                           |
| **Visuals**        | `seaborn`, `matplotlib`, `plotly`, `missingno`, `wordcloud` |
| **Notebook**       | JupyterLab (Python 3.9)                                     |



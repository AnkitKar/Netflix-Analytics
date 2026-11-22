# Netflix Content Evolution Analysis — Assignment Package

## Selected challenge
**Challenge 3: The Evolution of Netflix Content**

Business question: **How has Netflix's content library changed over time?**

## Group members and responsibilities
- **Ankit Kar:** project coordination, exploratory data analysis, visualisations, interpretation, and final report integration.
- **Dhruv Joshi:** dataset inspection, data cleaning, notebook execution checks, and version-control support.
- **Joint responsibilities:** confirm project scope, review business insights, perform quality assurance, and approve the final submission.

## Package contents
- `Netflix_Content_Evolution_Analysis.ipynb` — structured notebook for data loading, cleaning, EDA, visualisations, business insights, recommendations, and conclusions.
- `agile/Netflix_Agile_Project_Plan.docx` — Agile project plan, sprint goal, task ownership, Kanban board, risks, and provisional retrospective.
- `download_dataset.py` — downloads the cited CSV into `data/`.
- `requirements.txt` — Python dependencies.
- `data/` — put `netflix_titles.csv` here.

## Dataset provenance and limitation
The dataset is the Netflix Movies and TV Shows catalog dataset credited to Shivam Bansal on Kaggle and mirrored in the TidyTuesday project dated 20 April 2021. The TidyTuesday README says it was collected from Flixable, a third-party Netflix search engine. It is a historical third-party catalog snapshot, not Netflix's live catalog. It does not include viewing hours, popularity, retention, or revenue; do not interpret counts as viewership or success.

Sources:
- Dataset documentation: https://github.com/rfordatascience/tidytuesday/blob/main/data/2021/2021-04-20/readme.md
- CSV: https://raw.githubusercontent.com/rfordatascience/tidytuesday/main/data/2021/2021-04-20/netflix_titles.csv
- Kaggle dataset: https://www.kaggle.com/datasets/shivamb/netflix-shows

## Run on macOS / Windows / Linux
1. Open Terminal in this project folder.
2. Create and activate a virtual environment (optional but recommended):
   ```bash
   python3 -m venv .venv
   source .venv/bin/activate
   ```
   On Windows PowerShell use `.venv\Scripts\Activate.ps1`.
3. Install dependencies: `pip install -r requirements.txt`
4. Download the CSV: `python download_dataset.py`
   - If download is blocked, download the CSV from the source link above and save it as `data/netflix_titles.csv`.
5. Start Jupyter: `jupyter notebook`
6. Open `Netflix_Content_Evolution_Analysis.ipynb` and choose **Run All**.
7. Save the notebook after all cells finish; capture a screenshot of the last successful outputs.

## Git version control
Initialise a repository and commit the working files:
```bash
git init
git add README.md requirements.txt download_dataset.py Netflix_Content_Evolution_Analysis.ipynb agile/
git commit -m "Add Netflix content evolution analysis project"
```
Add the dataset separately only if its terms of use permit redistribution. Otherwise keep it local and add `data/netflix_titles.csv` to `.gitignore`. Then create a GitHub repository and push the project. Add the actual repository URL to your assignment before submission; no repository has been created by this package.

## Submission status
The notebook structure and code are prepared, but it has **not yet been executed against the CSV in this workspace** because the dataset file was not included in the uploaded materials and network download is unavailable in this execution environment. The data-dependent tables, charts, and insights are produced when you run it with the CSV. Do not submit it as an executed notebook until you have run all cells and checked the outputs.

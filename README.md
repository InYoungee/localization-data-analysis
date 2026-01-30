 🔗 **[View the notebook with interactive visualizations](https://nbviewer.org/github/InYoungee/localization-data-analysis/blob/main/2025_Localization_Data_Analysis.ipynb)**

*Note: Plotly visualizations may not render correctly in GitHub’s notebook preview.*
*Please use the nbviewer link above for full interactivity.*

# Localization Data Analysis with Python

This project analyzes localization project data from 2025 to explore workload distribution, project volume, and translation quality activities across games and teams.

To ensure confidentiality, the original dataset was duplicated and anonymized prior to analysis. Low-volume projects were excluded to focus on representative workloads, all game titles and linguist names were replaced with anonymized labels, and unused fields (such as project titles) were removed.

Data processing and analysis were performed using **pandas**, with visualizations created using **matplotlib**, **Seaborn**, and **Plotly**. The cleaned dataset was programmatically exported to Google Sheets via the **Google Sheets API**.

Initial exploration was conducted through **Google Sheets**–**Colab integration**, followed by automated data ingestion using an exported **CSV** snapshot for security and reproducibility.

- ### Total number of projects in in 2025.
My team coducted 2,530 projects in 2025.
<img src="https://github.com/InYoungee/localization-data-analysis/blob/main/images/total%20projects%20in%202025.png">

- ## Tne number of project by game
Game T has the highest LQA intensity compared to the total Projects, 28%.
<img src="https://github.com/InYoungee/localization-data-analysis/blob/main/images/projects%20by%20game.png">

- ## Game O has the largest volume of Translation.
<img src="https://github.com/InYoungee/localization-data-analysis/blob/main/images/total%20wc%20by%20game.png">

- ## Monthly Translation volume trend by Game
<img src="https://github.com/InYoungee/localization-data-analysis/blob/main/images/monthly%20project%20volume.png">

- ## Quarterly Translation volume
<img src="https://github.com/InYoungee/localization-data-analysis/blob/main/images/quaterly%20wc.png">

- ## Translation task distribution
<img src="https://github.com/InYoungee/localization-data-analysis/blob/main/images/trans%20distribution.png">

- ## Average Word Count per Project by Game
![Average wc by game](https://github.com/InYoungee/localization-data-analysis/blob/main/images/avg%20wc%20by%20game.gif)

- ## Monthly & Yearly Average Workload per In-house Translator
<img src="https://github.com/InYoungee/localization-data-analysis/blob/main/images/avg%20trans%20workload%20.png">



  

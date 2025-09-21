# An-Assessment-of-the-Role-of-University-Hostels-in-Student-Well-Being-and-Academic-Performance
# An Assessment of the Role of University Hostels in Student Well-Being and Academic Performance

📄 Full Report: [View Analysis](analysis.html)

## Overview
This project investigates the role of university hostel environments at KNUST in shaping student well-being and academic performance, addressing three objectives: analyzing the impact of hostel living conditions on well-being, assessing their influence on academic performance, and identifying key challenges faced by students. Utilizing a mixed-methods approach, data from 301 students (147 female, 154 male) were analyzed through Likert-scale ratings (1 = Strongly Disagree/Poor to 4 = Strongly Agree/Excellent) and qualitative responses, with Hostel Conditions, Well-Being, and Academic Performance Indices constructed (Cronbach’s Alpha: 0.89, 0.95, 0.92). Findings reveal that hostel conditions significantly predict well-being (R²=0.882) and academic performance (R²=0.865), with well-being mediating 74% of the effect on academics. Key challenges include unreliable WiFi (55.8% poor), inadequate study areas (44.9%), and noise (44.5%), which correlate with stress (40.9% low), poor study habits (41.5%), and academic performance (43.9%). Males report higher well-being and performance than females, with infrastructure issues (80.7% prevalence) dominating qualitative concerns. Recommendations include prioritizing WiFi upgrades, study spaces, and noise control to enhance student outcomes. This study underscores the critical link between hostel environments and student success, advocating for targeted interventions to improve university living.

## Objectives
- Analyze the impact of hostel living conditions on the well-being of students.
- Assess the influence of hostel environments on academic performance .
- Identify challenges faced by students in university hostels .

## Dataset Summary
- **Source**: Primary survey data from KNUST undergraduate students residing in university hostels (2025).
- **Sample Size**: 301 respondents (147 female, 154 male).
- **Key Variables**: Demographics (gender, age, academic year, college); hostel conditions (8 items: WiFi, maintenance, noise, etc.); well-being (10 items: comfort, stress, belonging); academic performance (7 items: concentration, motivation, habits); qualitative challenges/suggestions.
- **Note**: Raw data is not included due to confidentiality. Please contact the author for collaboration requests.

## Methods
- Descriptive statistics (means, percentages) and visualizations (bar plots, heatmaps, scatterplots) for profiling satisfaction and distributions.
- Reliability testing (Cronbach’s α=0.89–0.95); correlation analysis (Pearson's r=0.90 for conditions vs. performance).
- Hierarchical linear regression for predictors (e.g., conditions β=0.93 on performance, R²=0.865); mediation analysis (74% via well-being, ACME=0.67).
- Qualitative coding for challenges (e.g., infrastructure 80.7%, 242 mentions).

## Key Findings
- Demographics: Balanced gender (51.2% male), mid-level undergrads (90.1% 2nd/4th year), arts/humanities dominant (94.3%).
- Hostel conditions: Moderate (mean=2.6/4); strengths: water/electricity (76.7% positive); challenges: WiFi (55.8% poor), study areas (44.9%), noise (44.5%).
- Well-being: Moderate (mean=2.6/4); strengths: comfort/privacy (76.7–77.1%); weaknesses: stress (40.9% low), psych state (45.2% low); conditions predict well-being (β=1.01, R²=0.882); males higher (e.g., belonging 2.86 vs. 2.12).
- Academic performance: Moderate (mean=2.6/4); strengths: concentration (82.1%); weaknesses: habits/performance (41.5–43.9% challenged); conditions predict performance (β=0.93, R²=0.865); well-being mediates 74% (ACME=0.67); males higher (motivation 3.06 vs. 2.22).
- Challenges: Infrastructure (80.7%, 242 mentions: WiFi 38, study rooms 51, maintenance 36); security (13.7%), environmental (11.7%); suggestions: study rooms (16.9%), roads (12.6%), maintenance (12.0%).



## How to Reproduce the Analysis
### Requirements
- R (version 4.0 or higher)
- RStudio
- R packages: tidyverse, ggplot2, dplyr, psych (correlations, α), lmtest (robust SE), mediation

### Steps
1. Clone this repository.
2. Open `analysis.Rmd` in RStudio.
3. Install required packages if not already installed (e.g., `install.packages(c("tidyverse", "psych", "mediation"))`).
4. Knit the R Markdown file to generate the HTML report.
Data not included due to confidentiality. Please contact me for collaboration requests.

## Repository Structure
├── analysis.Rmd         # R Markdown source file  
├── analysis.html        # Knitted HTML report  
├── figures/             # Plots and visualizations  
├── README.md            # Project description  

## License / Citation
This project is for academic and research purposes. Please cite appropriately if referenced, e.g., Sei, Lawrence. (2025). An Assessment of the Role of University Hostels in Student Well-Being and Academic Performance.

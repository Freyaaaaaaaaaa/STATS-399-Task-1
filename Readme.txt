# STATS-399-Task-1

## Overview
This repository contains materials for Task 1 of STATS 399. The task involves cleaning a sentiment survey dataset, analyzing it, and producing a well-documented HTML report with visualizations.

## Files
- `sentiment-survey-data.csv`: Original raw data file.
- `cleaned_sentiment_data.csv`: Cleaned and processed data ready for analysis.
- `stats_399_task_1.Rmd`: R Markdown source file for analysis and report generation.
- `stats_399_task_1.html`: Output HTML report generated from the R Markdown file.
- 'Hihi-H-Graphic.pdf':Visual graphic
## Requirements
Ensure that the following R packages are installed before running the code:
- `tidyr`
- `dplyr`
- `stringr`
- `ggplot2` *(if using visualizations)*
- `knitr` *(for generating the HTML report)*

You can install them in R with:
```R
install.packages(c("tidyr", "dplyr", "stringr", "ggplot2", "knitr"))

##Running the Analysis
Open stats_399_task_1.Rmd in RStudio

Click "Knit" to execute the entire pipeline:

- Data cleaning
- Sentiment analysis
- Visualization generation
- Report creation

##Technical Notes
- Emoji handling uses Unicode range \U0001F600-\U0001F6FF
- Sentiment analysis uses the NRC Emotion Lexicon
- Manual corrections applied for multi-word responses
- All visualizations use ColorBrewer palettes for accessibility

##Figures 
The composite visualization "Sentiment Summary of the Course" integrates three complementary analyses of student sentiment data:

-Top 6 Students Feelings (Top Panel - Left)
Shows the most frequently reported emotional responses to the course

Sentiment coloring reveals emotional valence:
Red: Negative emotions (nervous, anxious, worried)
Green: Positive emotions (excited, interested)
Blue: Neutral/ambiguous feelings (curious, unsure)

- Overall Sentiment Distribution (Top Panel - Right)
Illustrates the proportional distribution of sentiment polarity

- Perception Comparison (Bottom Panel)
Contrasts students perceptions of classmates vs. instructor emotions

-Acknowledgements
This project was made possible through the collaborative efforts of our research team. We extend our sincere gratitude to:
Freya Wang，Noah Newby，Wenji He of University of Auckland

 # 🐻 Bear Attack Analysis and Visualization 

## Interactive Visualization

https://mkenton.shinyapps.io/homework2/

## Overview

As someone who frequently hikes and camps in backcountry areas, I’ve often been warned to “watch out for bears.” This led me to wonder: how common are bear attacks, really? This project explores patterns in bear attacks across North America, with a focus on geography, victim demographics, and bear species involved. The goal is to provide an interactive tool that helps visualize where, when, and how bear attacks occur.

## Essential Questions

- Where are bear attacks happening?
- Who is getting attacked (age, gender)?
- Which bear species are most likely to attack?
- How has the frequency of bear attacks changed over time?

## Project Goals

- Build an interactive Shiny app to visualize and explore bear attack data.
- Provide multiple views (map, scatterplot, and data table) for different dimensions of the data.
- Enable filtering by year and bear species to explore specific trends.

## Design Choices

- **Map Visualization:** A map of North America was used to show where attacks occurred. Each point is colored by bear species and includes a tooltip showing the year and location.
- **Victim Demographics Scatterplot:** Plots victim gender vs. year of attack, with point size scaled to age of the victim.
- **User Inputs:**
  - Year range slider
  - Bear species checkboxes
- **Data Table:** Summarizes filtered data with relevant columns only.
- **Incremental Development:** The Shiny app was developed step-by-step, beginning with a simple interface and evolving into a reactive, user-driven application.

## Key Findings

- **Geographic Patterns:** As predicted, bear attacks are most frequent in the northern and western regions, but the northeast had more attacks than expected.
- **Victim Demographics:**
  - A much larger proportion of victims were male.
  - The age range was surprisingly broad, from less than a year old to 93 years old.
- **Bear Species:**
  - Black bears were responsible for the most attacks.
- **Temporal Trends:**
  - Contrary to expectations, bear attacks have not significantly declined since 1980.
  - Data ends in 2018, so recent trends (post-2018) are unknown.

## Tools & Technologies

- R
- Shiny
- tidyverse (dplyr, ggplot2, tidyr)

## Dataset

- Source: Publicly available bear attack data compiled from various records.
- Includes information on:
  - Date and location of attack
  - Bear species
  - Victim demographics (gender, age)
  - Outcome and notes
 
## Limitations

- No data available after 2018.
- Some entries are missing complete demographic information.
- Attack frequency may be influenced by reporting rates and data availability.

## Conclusion

This project offers a clearer picture of bear attack patterns in North America. It reinforces that while attacks are relatively rare, they span a wide range of contexts and affect people of all ages. Interactive visualizations help users engage with the data and understand the nuances behind bear-human interactions.

## ⚠️ Disclaimer

**This project is for educational and exploratory purposes only.**  
The data should not be used as a risk assessment tool or for making decisions in backcountry travel. Always follow local wildlife guidelines and safety precautions when recreating in bear country.

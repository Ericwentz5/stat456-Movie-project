# Quantifying Cult Classics
### By Natalia Morales Flores, Eric Wentz, and Sebastian Stefanowicz

## Eric Wentz FP4
- All relevent info is in the QMD or HTML under the Folder Wentz_viz_capstone


## Research Question(s)
- What are the measurable characteristics of cult classic films? Is there a recipe or is it largely intangible?
- Can we tease out subcategories of cult classic based on director fame or time horizon?
- Can we predict future cult status for recent films?

## Data Sources
- The Movie Database: contains general information for the 10,000 highest rated movies based on user scores including title, release date, budget, revenue, average score, runtime, and the unique identifier linking each movie to the IDMB database. Combined with an LLM generated binary outcome variable.
- Internet Movie Database: utilize datasets containing user votes over time and information on directors and other people associated with each film.
  
## QMD Guide/Contributions So Far
Sebastian
- Load_TMDB_Data.qmd contains script to experiment with and query the TMDB API to create one of our core datasets and explore manually classifying cults with the resulting data.
- LLM_Classification.qmd contains script to query the OpenAI API to create a binary cult classifier that we used as our outcome variable and visualize the characteristics of the resulting groups.

## Plan
- Awards or lack of awards as a predictor. (Sebastian)
- Investigate impact of gender of director. (Eric)
- Pick a year and aggregate+visualize volume of votes over time for cults and non-cults. If this is interesting, further investigate glide path subcategories. (Natalia)
- Refine classification models and start predicting! (Everyone)

## Ethical Considerations
- 

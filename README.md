# What Makes a Cult Classic?

## AI USAGE STATEMENT 
Generative AI (GPT-5.1 was used for syntax, brainstorming, and bullet point creation in the slides part. No full paragraph or code chunk generating was used and all queries were heavily revised if used



This project explores what makes a movie a cult classic using a combination of
movie metadata, keyword and genre analysis, large language model (LLM) labeling,
and human-in-the-loop validation. Cult classics are subjective, culturally
dependent, and difficult to define, making them a compelling case study for
applying data science and AI to unstructured concepts.

## Team
- Eric Wentz
- Natalia [Last Name]
- Sebastian [Last Name]

---

## Repository Structure

The repository is organized to reflect the full data science workflow and to
make the analysis easy to follow and reproduce.


---

## Data Dependencies

This project uses movie metadata and ratings data from public sources:

- TMDB movie metadata (genres, keywords, overviews, release dates)
- IMDB ratings data
- LLM-generated cult classic labels

If file sizes allow, the raw data are included in the `data/raw` folder.  
If not, instructions for downloading the data are provided in the corresponding
notebook or Markdown file.

**Important:**  
To run the analyses locally, you may need to download the data from the `data`
folder to your local machine and adjust file paths depending on which QMD
notebook you are running. File paths are clearly labeled at the top of each
notebook for easy modification.

---

## Code Dependencies

Analyses are primarily conducted in R. The following packages are required:

- tidyverse
- jsonlite
- tidyr
- purrr
- ggplot2
- umap
- janitor
- ggraph
- igraph
- wordcloud (for select visualizations)

Package installation instructions are included at the top of each QMD notebook.
Session information and package versions are documented in the `environment`
folder when applicable.

---

## Reproducibility

To reproduce this project:

1. Clone the GitHub repository.
2. Download or verify all required data in the `data/raw` folder.
3. Update file paths in each QMD notebook as needed for your local environment.
4. Run notebooks in numerical order, starting with data cleaning and ending
   with clustering and visualization.

Each notebook is self-contained and documents its inputs and outputs.

---

## Human-in-the-Loop Validation

Because cult classic status is subjective, LLM-generated labels are validated
by a human reviewer. A subset of labeled movies is manually reviewed to ensure
alignment between model predictions and human judgment. This validation process
is documented in the `03_human_validation.qmd` notebook.

---

## Acknowledgments

We consulted with an industry professional who provided guidance on feature
selection and project direction. Based on this feedback, we avoided actor and
director-based features and focused on thematic and textual signals instead.


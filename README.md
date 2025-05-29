# Film Genre Analysis Project

## Overview
This project analyzes the evolution of film genres across different continents over time. 
Using data visualization techniques, it explores how movie production and genre preferences have changed globally from the early 1900s to present day.

## Features
- Interactive data visualization of film genres by continent
- Temporal analysis of genre popularity
- Comparative analysis between continents
- Top 10 genre distribution analysis
- Animated visualizations showing genre evolution

## Technologies Used
- R
- R Markdown
- xaringan (for presentation)
- tidyverse
- plotly
- scales

## Data Sources
1. FilmTV Movies Dataset
   - Source: [Kaggle - FilmTV Movies Dataset](https://www.kaggle.com/datasets/stefanoleone992/filmtv-movies-dataset/data)
   - Contains 41,399 rows and 19 columns
   - Includes movie information from various years

2. Countries by Continent Dataset
   - Source: [Kaggle - Countries by Continent](https://www.kaggle.com/datasets/hserdaraltan/countries-by-continent)
   - Contains 196 rows and 2 columns
   - Maps countries to their respective continents

## Project outline and grading criteria
> **Présentation du projet**
> - Trouver un dataset 
> - Tenter de répondre à une question à l'aide de visualisation 
>
> **Données** 
>- Vous identifiez une source de données publique ouverte(data.gouv.fr, johns hopkins, etc)
>- Il faudra justifier le choix du dataset(source, contenu, provenance, etc)
>
> **Objectifs**
>- Produire des visualisations
>- Répondant à la question
>- En choisissant un des buts suivants de la communication : enregistrer l'information, analyser, communiquer
>- Essayer de deviner ma hypothèse : ***expliciter***
>  
> **Conditions**
> - Production d'au moins deux visualisations différentes
> 	- Dont au moins une statique et **une interactive**
> 	- répartition spatiale : prévalence des malaldies
> - Produire une présentation de 10 min présentant vos visualisations
> - Justifier vos choix : de dataset, de design, de représentation, etc
>  
>  **Presentation 10 mins + 5 mins de question**
>  - Cheminement intellectuel
>  - Commencer par defaut - pour avoir la visualisation finale
>  - Dans les grandes lignes : étape par étape (baseline-couleur-annotations-..., Choix de la palette (importante))
>  - R markdown

## Key Findings
1. **Geographic Distribution**
   - Europe and North America dominate film production
   - Significant gap between top two continents and others

2. **Genre Popularity**
   - Drama and Comedy are the most dominant genres
   - Western films gained popularity in North America from 1914
   - Documentary films show increasing presence in Europe

3. **Temporal Trends**
   - Increased global film production over time
   - Genre diversification in North America during 1930s
   - Recent surge in Action and Drama films in Asia

## Installation
1. Clone the repository
2. Install required R packages:
```R
install.packages(c("xaringan", "tidyverse", "scales", "plotly"))
```
3. Open the R Markdown file in RStudio

## Usage
1. Run the R Markdown file to generate the presentation
2. Interactive visualizations can be viewed in the HTML output
3. Use the animation controls to explore temporal changes

## Contributing
Feel free to submit issues and enhancement requests!

## Authors
- Minji NAM
- Mylène LACOMBE

## License
This project is licensed under the MIT License - see the LICENSE file for details

## Acknowledgments
- Data providers on Kaggle
- R community for visualization packages
- University of Paris for educational support

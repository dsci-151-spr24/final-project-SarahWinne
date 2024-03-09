# data

Place data file(s) in this folder.

Then, include codebooks (variables, and their descriptions) for your data file(s)
using the following format.

There are 13493 observations and 25 variables.

## ProjectGutenbergMetadata

- `Work_ID`: Project Gutenberg ID of the work in question for reference

- `Biodiversity_Richness`: Biodiversity richness (number of unique taxon labels, i.e., terms for organisms, per work normalized to 10,000 tokens) as determined in Langer et al. (2021)
- `Lexical_Richness`: Lexical richness (size of vocabulary per work normalised to 10,000 tokens) as determined in Langer et al. (2021)
- `Age_Publication`: Age of the Author at the time of the work’s publication
- `Year_Publication`: Year of the work’s publication (or conception, if earlier)
- `Literature_Form`: Literature form of the work, e.g., drama, novel, short story
- `Gender`: Gender of the Author (f for female, m for male)
- `Parenthood`: Whether or not the author had children
- `Highest_Education`: Whether the author had a higher academic, university or school education
- `Biodiversity_Background`: Whether the authors’ occupation was somewhat connected to biodiversity / biology, e.g., biologist, medical doctor or even teacher
- `Main_Region`: The region where authors were located for the most part of their lives
- `Migrating`: Count of different regions reached by authors within their life span
- `Main_Residence`: Characterization of the settlement size of the author’s main residence as village, town or city
- `genre_satire`: Whether the genre was marked satire (Boolean)
- `genre_historical`: Whether the genre was marked historical (Boolean)
- `genre_social`: Whether the genre was marked social (Boolean)
- `genre_children`: Whether the genre was marked children (Boolean)
- `genre_adventure`: Whether the genre was marked adventure (Boolean)
- `genre_mystery`: Whether the genre was marked mystery (Boolean)
- `genre_crime`: Whether the genre was marked crime (Boolean)
- `genre_sf`: Whether the genre was marked sci-fi (Boolean)
- `genre_romance`: Whether the genre was marked romance (Boolean)
- `genre_fantasy`: Whether the genre was marked fantasy (Boolean)
- `genre_biography`: Whether the genre was marked biography (Boolean)
- `genre_travellogue`: Whether the genre was marked travellogue (Boolean)

Vignette Title: Analyzing Spotify Track Data with Tidyverse

Vignette Purpose:
This vignette is designed to demonstrate how to use various Tidyverse functions for manipulating, visualizing, and summarizing a dataset of Spotify tracks. The primary goal is to provide clear examples of how these functions can be used to uncover insights within music data, particularly focusing on track features such as danceability, energy, and loudness, and how they vary with track popularity and genres.

Tidyverse Functions Used:
read_csv from readr to load the dataset.
filter and select from dplyr to manipulate the dataset.
mutate from dplyr to create new categorized variables.
sample_n from dplyr to work with a manageable sample size.
ggplot, geom_point, facet_wrap, labs, and theme_minimal from ggplot2 to create visualizations.
group_by and summarize from dplyr to summarize the data.
ggsave to save the created plots.

Instructions to Run the Vignette:
Ensure that you have R and the Tidyverse package installed.
Download the R Markdown file from the provided link.
Open the R Markdown file in an R environment (such as RStudio).
Install any missing packages using install.packages("package_name").
Run the R Markdown file to execute the code chunks. The vignette is self-contained and includes comments explaining each step.
Optionally, modify the read_csv path to point to your local dataset if not using the provided online source.

Vignette Links:
R Markdown Source: https://github.com/Doumgit/Sentiment-Analysis-Project/blob/main/Souleymane_Tidyverse_Create.Rmd on GitHub
Rendered Vignette: https://github.com/Doumgit/Sentiment-Analysis-Project/blob/main/Souleymane_Tidyverse_Create.html on GitHub

Data File:
Spotify Data CSV: https://raw.githubusercontent.com/Doumgit/Sentiment-Analysis-Project/main/spotify_songs.csv on GitHub

By following through this vignette, users will be able to understand how to employ Tidyverse functions effectively to analyze a music dataset, which can be further generalized to other types of data analysis workflows.

# Souleymane Doumbia


Initial Description and Link: 

Revision/Addition Description and Link:
* Modified ggplot/forcats example to demonstrate sorting, other category
* https://github.com/acatlin/FALL2023TIDYVERSE/blob/main/ggplot_forcats.rmd

* Demonstrates how to flip ggplot axes

# Chun Shing Leung
* https://github.com/acatlin/FALL2023TIDYVERSE/blob/main/Chun Shing Leung TidyVerse.Rmd
### drop_na(), distinct(), pipe, select(), mutate(), filter(), relocate(), group_by(), summarise()

# carolc
sample .csv file posted
code forthcoming!!!

#Fomba
Loaded Bright Spots

# Kristin Lussi
ggplot2 Capabilities
* Demonstrates capabilities of ggplot2
* https://github.com/acatlin/FALL2023TIDYVERSE/blob/main/lussi_ggplot2.rmd

# Julia Ferris 
### ggplot2, geom_violin(), geom_density_2d(), and geom_rug()
Initial Description and Link: 
* Demonstrates how to use geom_violin(), geom_density_2d(), and geom_rug() when visualizing data with examples
* https://github.com/acatlin/FALL2023TIDYVERSE/blob/main/tidyverse.Rmd
* https://github.com/acatlin/FALL2023TIDYVERSE/blob/main/tidyverse.pdf

Data File:
* https://github.com/acatlin/FALL2023TIDYVERSE/blob/main/guns-polls.csv

Kristin Lussi's Extension:
* Demostrates how to use geom_density() and geom_bar()

# Marley Myrianthopoulos
### dplyr, select, filter, arrange
Initial Description and Link:
* Demonstrates how to use select, filter, and arrange to display a subset of data from a data frame.
* https://github.com/acatlin/FALL2023TIDYVERSE/blob/main/marley_myrianthopoulos_tidyverse_create.Rmd


# Sean Amato
### mutate() and across()
Initial Description and Link: 
* Demonstrate how to use mutate() and across() to perform a calculation over multiple columns without a for loop.
* https://github.com/acatlin/FALL2023TIDYVERSE/blob/main/sean_amato_tidyverse_create.rmd

Data Source:
* https://www.kaggle.com/datasets/iamsouravbanerjee/years-of-schooling-worldwide/

# Molly Siebecker
### str_to_lower, str_length, str_sort, str_detect, str_count
Initial Description and Link:
* Demonstrates how to use str_to_lower, str_length, str_sort, str_detect, and str_count to manipulate character strings.
* https://github.com/mollysiebecker/FALL2023TIDYVERSE/blob/main/molly_siebecker_tidyverse_create.Rmd
* Data Source: "babynames" data set in base r

# Shaya Engelman
### stringr and dplyr functions
Initial description and link:
* Demonstrate differnt stringr functions and manipulate data with dplyr functions
* https://github.com/Shayaeng/FALL2023TIDYVERSE/blob/main/ShayaEngTidyVerseCreate.Rmd

* Data source: https://ourworldindata.org/life-expectancy
* The csv files are loaded in my GitHub repository


=======
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

# Chun Shing Leung
* Updated DaveGreerTidyVerse.rmd under Chun_Shing_Leung_Extend_TidyVerse.rmd
* Added a scatterplot

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

# klussi
ggplot2 Capabilities
* Demonstrates capabilities of ggplot2
* https://github.com/acatlin/FALL2023TIDYVERSE/blob/main/lussi_ggplot2.rmd
* Update to TidyVerse Vignette: ggplot2 and Student Stress Factors
Date: 12/04/2023
I've extended the existing ggplot2 vignette, originally focusing on the "Student Stress Factors" dataset. My contribution includes:

New Section on Scatter Plot Analysis: Added an exploratory section that demonstrates how to create a scatter plot using ggplot2. This plot investigates the relationship between 'Sleep Quality' and 'Stress Level' in students, providing deeper insights into the dataset.

Enhanced Conclusion: Updated the final conclusion to encapsulate both the original content and the new scatter plot analysis, highlighting the importance of visual data exploration in revealing trends and relationships.

This update aims to enrich the existing vignette by offering a more comprehensive view of the dataset through ggplot2 visualizations.

This is my R makdown (Rmd file which include my extension at the bottom of KLussi): https://github.com/Doumgit/TidyVerse_Extend/blob/main/Souleymane_Tidyverse_Extend.Rmd

# Julia Ferris 
### ggplot2, geom_violin(), geom_density_2d(), and geom_rug()
Initial Description and Link: 
* Demonstrates how to use geom_violin(), geom_density_2d(), and geom_rug() when visualizing data with examples
* https://github.com/acatlin/FALL2023TIDYVERSE/blob/main/tidyverse.Rmd
* https://github.com/acatlin/FALL2023TIDYVERSE/blob/main/tidyverse.pdf

Data File:
* https://github.com/acatlin/FALL2023TIDYVERSE/blob/main/guns-polls.csv


# Marley Myrianthopoulos
### dplyr, select, filter, arrange
Initial Description and Link:
* Demonstrates how to use select, filter, and arrange to display a subset of data from a data frame.
* https://github.com/acatlin/FALL2023TIDYVERSE/blob/main/marley_myrianthopoulos_tidyverse_create.Rmd

### Extend Assigment:
* Adds to Michael Robinson's work by explaining how the piping operator can be used to perform multiple data transforms, demonstrating alternative methods, and showing that the results are the same.

# Sean Amato
### mutate() and across()
Initial Description and Link: 
* Demonstrate how to use mutate() and across() to perform a calculation over multiple columns without a for loop.
* https://github.com/acatlin/FALL2023TIDYVERSE/blob/main/sean_amato_tidyverse_create.rmd

Data Source:
* https://www.kaggle.com/datasets/iamsouravbanerjee/years-of-schooling-worldwide/  


=======
Extension:
*https://github.com/acatlin/FALL2023TIDYVERSE/blob/main/molly_siebecker_tidyverse_extend.Rmd
*Demonstrates additional aesthetic features of ggplot2 using Fomba's examples.

# Shaya Engelman
### stringr and dplyr functions
Initial description and link:
* Demonstrate differnt stringr functions and manipulate data with dplyr functions
* https://github.com/Shayaeng/FALL2023TIDYVERSE/blob/main/ShayaEngTidyVerseCreate.Rmd

* Data source: https://ourworldindata.org/life-expectancy
* The csv files are loaded in my GitHub repository


# Fomba Kassoh - Tidyverse Extend Assignment
Extended the the code on dplyr and ggplot2 provided by Souleymane Doumbia. I have added the following extensions to his vignette
https://github.com/hawa1983/FALL2023TIDYVERSE/blob/main/Souleymane_Tidyverse_Create.Rmd
## dplyr vignette
I used various dplyr functions to demonstrated/described their use in summarizing and analysing the spotify data.
* Use of the 'arrange' function to sort data frame on a columns.
* Demostrate the use of the 'count' function to count number of tracks in each genre.
* Filtering tracks that are outliers in terms of duration (using IQR).
* Normalizing audio feature columns (like loudness and tempo) to have a comparison scale. 
* Grouping data and applying a function within each group.
* Using the tidyr function pivot_longer to transform the data frame from the wide format to the long format for visualizations.

## ggplot2
Extended the demonstratration/description of the ggplot2 package for visualizations
* Provided the code and explained the use of Box Plot, Histogram, Density Plot, and Bar Plot in data visualization and analysis.
* Provided an explaination of each of the ggplot functions used.


# Frederick Jones
### ggplot, geom_point(), geom_snooth(), datatable(), mutate(), summarize()
Initial Description and Link: 
* Demonstrate how to use ggplot, geom_point(), geom_snooth(), datatable(), mutate(), summarize()
* Example extended from https://github.com/acatlin/FALL2023TIDYVERSE/blob/main/tidyverse_healthcare.Rmd
# EDA

Netflix is one of the most popular media and video streaming platforms. They have over 8000 movies or tv shows available on their platform, as of mid-2021, they have over 200M Subscribers globally. This tabular dataset consists of listings of all the movies and tv shows available on Netflix, along with details such as - cast, directors, ratings, release year, duration, etc.

## Description of each column in the dataset:

### show_id: A unique identifier for each show or movie.

### type: The type of content, either "Movie" or "TV Show."

### title: The title of the movie or TV show.

### director: The director of the movie or TV show. In the first and third entries, this information is not available (NaN).

### cast: The cast or actors in the movie or TV show. In the first entry, this information is not available (NaN). In the second entry, there is a list of actors from the TV show "Blood & Water."

### country: The country where the movie or TV show was produced or is associated with.

### date_added: The date when the content was added to the streaming platform, in the format "Month Day, Year."

### release_year: The year the movie or TV show was originally released.

### rating: The content's rating, which indicates the recommended audience age or maturity level (e.g., "PG-13" or "TV-MA").

### duration: The duration of the movie or TV show. In the first entry, the duration is given in minutes ("90 min"). In the second and third entries, it's indicated in the number of seasons ("2 Seasons" and "1 Season").

### listed_in: The genre or category of the content, which can help classify it (e.g., "Documentaries," "International TV Shows," "Crime TV Shows").

### description: A brief description or synopsis of the movie or TV show, providing an overview of the plot or subject matter.



###  Questions:



Load the dataset and print the complete information of the dataset and name the columns that has missing values.
Load the dataset and print the top 10 countries contributing to the Content on Netflix
Load the dataset and list the 5 most popular types of genre on the platform
Load the Dataset and categorize into TV shows and Movies and display 2 rows for each.
Load the Dataset and find the Oldest movies
Load the Dataset and get the count of values for duration column.
Load the Dataset and find the measures of central tendency and dispersion of duration column by extracting  numerical part of the duration column.
Load the Dataset and find out to which country the highest duration movie belongs to by extracting the numerical part of the duration column and create a new column. print title and country column.
Load the Dataset and plot the histogram  on Netflix Content Release Year Distribution
Load the Dataset and plot the Distribution of Populartiy of different content categories using countplot

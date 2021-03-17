# Data Overview: Movie Datasets

For these scenarios, you will be working on movie data.

These datasets describe information about various English-language movies and TV shows, such as the name of the movie, its MPAA or FCC rating (e.g. PG-13, R, TV-14), the director of the movie, and ratings of the movie as provided by viewers of the movie.

For these scenarios, imagine you are the data scientist in charge of ensuring the correctness of this data so that it can be utilized in a new movie data querying interface for the masses. 

Your job is to make sure that the data the public interacts with is as error-free as possible, so you want to flag down any errors you find so the data collectors can go back and review their notes and ensure the accuracy of the information in the dataset.

---

## **Attribute Definitions**
NOTE: Depending on which scenario you are working on, you may only be working with a subset of these attributes.
- **listingnumber**: The database's listing number for this movie or TV show.
- **title**: The title of the movie or TV show.
- **year**: The year the movie or TV show was released in.
- **rating**: The content rating of the movie or TV show, as defined by the Movie Picture Association of America (MPAA) or the Federal Communications Commission (FCC), respectively. NOTE: Some listings have not received a rating from the MPAA or FCC. These examples have a rating value of "Not Rated," and an occurrence of "Not Rated" does not necessarily mean the value is an error.
- **director**: The person who directed the movie or TV show. For movies or shows with more than one director but one person that was the lead director, this person is listed as the director in the dataset.
- **genre**: The genre of the movie or TV show, e.g. action, drama, horror, comedy, etc.

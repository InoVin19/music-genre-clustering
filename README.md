# Music Genre Clustering #

## Description: 
This project makes use of a Jupyter Notebook to clean data from the "Spotify - All Time Top 2000s Mega Dataset"
containing the following columns:

- **Index** \- the ID of the song
- **Title** \- The title of the song
- **Artist** \- Name of the artist of the song
- **Top Genre** \- Genre of the track
- **Year** \- Release Year of the Track
- **Beats Per Minute** \- The overall tempo of the song
- **Energy** \- The higher the value, the more energetic the song is
- **Danceability** \- The higher the value, the easier it is to dance to the song
- **Loudness** \- The higher the value, the louder the song
- **Valence** \- The higher the value, the more positive the mood for the song is
- **Length** \- The duration of the track
- **Acoustic** \- The higher the value, the more acoustic the song is
- **Speechiness** \- The higher the value, the more spoken words the song contains
- **Popularity** \- The higher the value, the more popular the song is
- what it does, technology and tools used

### Data Cleaning 
Before proceeding with the data modelling, the data cleaning was performed to check for and resolve the following:

- Multiple representations of the same categorical value
- Correctness of the datatype of the variable
- Set default values of the variable
- Missing data
- Duplicate data; and
- Inconsistent formatting of values.

### Exploratory Data Analysis 

Various Questions were explored before coming up with the data model, as delineated below:

1. <span style='font-size:medium'>What is the distribution of song popularity in the dataset? Are there any extreme outliers in terms of popularity?</span>
2. <span style='font-size:medium'>What is the correlation between the song's popularity and the following audio features: beats per minute, energy, danceability, acousticness, loudness, valence, length, speechiness?</span>
3. <span style='font-size:medium'>What is the correlation between the song's danceability and the following audio features: beats per minute, energy, loudness, valence, speechiness?</span>
4. <span style='font-size:medium'>What is the correlation between a song's accousticness and the following features: energy, loudness, valence, speechiness, and beats per minute \(BPM\)?</span>
5. <span style='font-size:medium'>Which genre produced the most number of popular songs and are there variations in popularity over the years for this genre?</span>
6. <span style='font-size:medium'>How popular were danceable songs throughout the years? At which year did high\-danceability songs peak in popularity?</span>
7. <span style='font-size:medium'>What percentage of artists are more than just one hit wonders? Out of all the artists out there how many are able to produce more than just one hit?</span>  

### Data Modelling 
The research question "How can we use music attributes such as danceability, valence, energy, and loudness in providing personalized music recommendations?" was formulated
and was answered through utilizing the k-means algorithm to cluster songs based on their danceability and energy levels.

## How to install and Run the Project 
- fork the repository and pull it to local machine
- ensure your machine has python 3.11 installed
- Open repository in code editor and set python environment
- Run each cell sequentially

## Credits
This project was developed by four developers:
- @inoVin19
- @nicoleUY
- @xLelouch03
- @merepixel

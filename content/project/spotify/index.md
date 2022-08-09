---
title: Analyzing Spotify Data in Python
summary: A deep dive in musical data using Pandas
tags:
- Python
date: "2021-07-01T12:00:00-05:00"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: ""
  focal_point: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---

## Analyzing a Spotify dataset using Pandas in Python
<br>
For this project, I will be analyzing a Spotify dataset (which can be found in my Github repository for this project) that carries various information on artists’ songs from 1920-2021. The whole file has multiple datasets, but I have chosen three datasets to analyze — “data_by_year”, “data_by_genre”, and “data_by_artist”. So, how exactly have songs changed over the years? What's the most popular genre on Spotify? Let’s find all of this out and more.
<br>

### <b>Analyzing the “data_by_year” dataset</b>

#### Import and Clean Data
<br>

First, I will import the libraries that will be needed in the whole data analysis process. In addition to Pandas, I will use the Seaborn library for data visualization.

<img src="IMG1.png" width="600" height="800"/>
<br>


No cleaning needed for this dataset, we import and the fun begins.

#### Exploration and Data Visualization
<br>

We can start off our analysis by finding the correlation between the different music features.

<img src="IMG2.png" width="600" height="200"/>
<img src="IMG3.png" width="500" height="500"/>
<br>

As you can see above, some of the more correlated features are: loudness and energy, acousticness and instrumentalness, and energy and danceability. Loudness/energy and energy/danceability are self explanatory, but it's interesting to note that the more acoustic a song tends to be, the more instrumentalness (amount of vocals) it has. Definitely need the vocals to shine more when there's less instruments to hide them behind!
<br>

So how has music been changing over time? We can answer this by observing the changes in the music features over the years.

<img src="IMG4.png" width="600" height="200"/>
<img src="IMG5.png" width="500" height="500"/>


### <b>Analyzing the “data_by_genre” dataset</b>

### <b>Analyzing the “data_by_artist” dataset</b>

### <b>Summary</b>
















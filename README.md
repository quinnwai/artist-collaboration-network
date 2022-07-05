# Artist Collaboration Network
Investigating the diversification of musical artist collaborations across genres using Spotify API data

## About
Our goal was to answer the question: "How have artists collaborations diversified over time?" With the rise of streaming service through the 2010s, we conduct an qualitative and quantitative analysis to see the trends in a network of artist collaborations over time. This repo is a running record of the data analyses we did. We did so by choosing the top 10 artists from a given genre (Chicago rap), then connecting artist nodes to other artists for a given year. Below is more information about navigating the repository.

## Navigation
Generally, the report of all the information can be seen in the `Artist_Genre_Diversification_Report.pdf` file. In the main folder is also the five notebooks used for collecting, processing, and analyzing the data. As for the other folders...

- `artists` and `tracks` store the raw data pulled from Spotify
- `data` stores the organized dataframes consisting of tracks info and artist info separately
- `gephis` and `gexf_files` are the related network graphs used for analysis and visualization
- `figures` has all of the plots of quantitative network measure, including degree distribution, assortativity, and average clustering coefficient

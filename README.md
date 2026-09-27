# Netflix Movies EDA — 1990s Deep Dive

A small exploratory data analysis project built while learning pandas on DataCamp's DataLab platform.

## Overview
A production company wants to explore Netflix's catalog to understand movies from the 1990s — 
a decade of interest for a "nostalgic styles" theme. This project filters and analyzes the dataset 
to answer a few specific questions about that decade's movie durations and genres.

## Dataset
`netflix_data.csv` — a Netflix catalog dataset (show ID, type, title, director, cast, country, 
date added, release year, duration, description, genre), provided as part of a DataCamp guided project.

## What I did
- Filtered the dataset to isolate movies released between 1990–1999
- Identified the most frequent movie duration in that decade using `.mode()` and `.value_counts()`
- Counted short-duration (<90 min) Action movies within the filtered set using row-wise iteration

## Tools
Python, pandas, NumPy

## Result
The most common movie duration in the 1990s dataset was **94 minutes**, and there were 
**7 Action movies under 90 minutes** in that period.

## Notes
This was a guided/practice project (starter code and question framing provided by DataCamp) — 
I wrote the analysis logic myself. Included here as an early example of my pandas work while 
transitioning toward data science.

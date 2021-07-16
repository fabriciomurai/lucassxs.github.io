---
date: "2021-07-15T00:00:00Z"
external_link: ""
image: 
  caption: Photo by rawpixel on Unsplash
  focal_point: Smart

summary: An example of using the in-built project page.
tags:
- R
title: Interactive Maps with Leaflet in R
url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""
---

I recently decided to develop API execution in R. I was interested in getting information on when the International Space Station (ISS) is scheduled to pass by the Brazilian state capitals and how I mapped it using `Leaflet`, for that I used Open Notify. The distributed pass times API for a given location when it establishes a corresponding latitude and longitude.

## Brazilian Capitals Information


```r
library(tidyverse)
library(httr)     ## for working with the API
library(jsonlite) ## to work with the JSON data

# Get the long & lats of all the Brazilian state capitals
capitals <- read.table("https://simplemaps.com/data/br-cities", col.names = c("state","latitude","longitude"))

# Get the state capital names
capital_names <- read.table

```

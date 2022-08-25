
<!-- README.md is generated from README.Rmd. Please edit that file -->

## Geocomputation and Data Analysis with R

Geocomputation and Data Analysis with R is a 2 day course to be held on
the 23<sup>rd</sup> and 24<sup>th</sup> April 2020 in the Leeds
Institute for Data Analytics (LIDA).

## Aim

The aim of the course is to get you up-to-speed with high performance
geographic processing, analysis and visualisation capabilities from the
command-line. The course will be delivered in R, a statistical
programming language popular in academia, industry and, increasing, the
public sector. It will teach a range of techniques using recently
developments in the package [**sf**](https://github.com/r-spatial/sf)
and the ‘metapackage’ [**tidyverse**](https://www.tidyverse.org/), based
on the open source book [Geocomputation with
R](https://geocompr.robinlovelace.net/) (Lovelace, Nowosad, and Meunchow
2019).

## Learning objectives

By then end of the course participants should:

  - Be able to use R and RStudio as a powerful Geographic Information
    System (GIS)
    <!-- What the different panels within RStudio are and how to use the view panel interactively -->
  - Know how R’s spatial capabilities fit within the landscape of open
    source GIS software <!-- What are the alternatives to R? -->
    <!-- What are it's strengths/weaknesses? -->
    <!-- How can R interface to dedicated GIS software like QGIS? -->
  - Be confident with using R’s command-line interface (CLI) and
    scripting capabilities for geographic data processing
    <!-- autocompletion --> <!-- using help -->
    <!-- knowing where to search and create a reproducible example to ask questions on a community forum -->
    <!-- source vs console editor --> <!-- projects and scripts -->
    <!-- functions / algorithms -->
  - Understand how to import a range of data sources into R
    <!-- read-in a shapefile --> <!-- write-out a geojson -->
    <!-- 7.2 Retrieving open data -->
    <!-- 7.3 Geographic data packages -->
    <!-- 7.4 Geographic web services --> <!-- 7.5 File formats -->
    <!-- 7.6 Data Input (I) --> <!-- 7.7 Data output (O) -->
  - Be able to perform a range of attribute operations such as
    subsetting and joining <!-- 3.2.1 Vector attribute subsetting -->
    <!-- 3.2.2 Vector attribute aggregation -->
    <!-- 3.2.3 Vector attribute joining -->
    <!-- 3.2.4 Creating attributes and removing spatial information -->
  - Understand how to implement a range of spatial data operations
    including spatial subsetting and spatial aggregation
    <!-- 4.2.1 Spatial subsetting -->
    <!-- 4.2.2 Topological relations --> <!-- 4.2.3 Spatial joining -->
    <!-- 4.2.4 Non-overlapping joins -->
    <!-- 4.2.5 Spatial data aggregation -->
  - Have the confidence to output the results of geographic research in
    the form of static and interactive maps
    <!--     8.2.1 tmap basics --> <!--     8.2.2 Map objects -->
    <!--     8.2.3 Aesthetics --> <!--     8.2.4 Color settings -->
    <!--     8.2.5 Layouts --> <!--     8.2.6 Faceted maps -->
    <!-- 8.4 Interactive maps -->

## Location

Leeds Institute for Data Analytics, 40 University Road, LS2 9JT. It can
be seen on
<!-- [OpenStreetMap](https://www.openstreetmap.org/way/84749920) -->
[OpenStreetMap](https://www.openstreetmap.org/way/445317959), on the
[LIDA website](https://lida.leeds.ac.uk/about-lida/contact/) and
highlighted in red below (it’s a 20 minute walk from Leeds train
station):

![](2-day-course_files/figure-gfm/unnamed-chunk-3-1.png)<!-- -->

## Online home

The course is part of the Geocomputation with R book project.

See the overview slides here:
<https://geocompr.github.io/presentations/2day.html#1>

See an overview of the course here:
<https://git.io/geocompr-2-day-course>

## Course contents

### Day 1: Foundations

09:00-09:30 Arrival and set-up

09:30-11:00 Introduction to the course and
software

<!-- - Introduction to R -->

<!-- - R installation questions/debugging -->

<!-- - How to use RStudio (practical in groups of 2) -->

<!-- - R classes and working with data frames in the **tidyverse** -->

<!-- Idea: get people to say where they are from, how many cups of coffee they drink per week their favourite animal -->

11:15-12:30: R’s spatial
ecosystem

<!-- - Live demo: using R as a GIS -->

<!-- - Spatial data in R -->

<!-- - R's spatial ecosystem (see section [1.4 of Geocomputation with R - package ecosystem](https://geocompr.robinlovelace.net/intro.html#rs-spatial-ecosystem)) -->

<!-- - Practical: [Work through the exercise 1:3 in Chapter 2](https://geocompr.robinlovelace.net/spatial-class.html#ex2) -->

<!--     - Advanced: complete exercises in Chapter 2 -->

<!--     - Bonus: reproduce the results in the `sf` vignette `sf1` -->

<!-- And example from the PCT -->

**Lunch**

13:30-15:00 The structure of vector geographic data in R and working
with attribute
data

<!-- - Vector attribute subsetting -->

<!-- - Vector attribute aggregation -->

<!-- - Vector attribute joining -->

<!-- - Creating attributes and removing spatial information -->

<!-- - Exercises: Chapter [3](https://geocompr.robinlovelace.net/attr.html#exercises-1) -->

<!--     - Core: Questions 1:3 and question 9 -->

<!--     - Bonus: complete as many exercises as possible in Chapter 3 -->

15:15-16:30 Spatial data operations

<!-- - Spatial subsetting -->

<!-- - Topological relations -->

<!-- - Spatial joining -->

<!-- - Non-overlapping joins -->

<!-- - Spatial data aggregation -->

<!-- - Exercises: Chapter 4 -->

### Day 2 GIS, visualisation, modelling

09:30-11:00 Reading and writing geographic data

11:15-12:30: Geometric operations

<!-- And example from the PCT -->

**Lunch**

13:30-15:00 Visualisation

15:15-16:30 Working on your own data

## Prerequisites

### Prior experience

**Attendees should already have experience with R.** In addition to
being able to complete introductory course such as DataCamp’s
[introduction to
R](https://www.datacamp.com/courses/free-introduction-to-r) free course
or equivalent, attendees should **already be using R** for their work.
This is not an introductory R course but a course for R users wanting to
develop their geospatial analysis skills. If you do not have R
experience but already use GIS software and have a strong understanding
for geographic data types, and some programming experience, the course
may also be appropriate.

In preparation for the course we recommend reading and running the code
in these free online resources:

  - The introductory chapter of [R for Data
    Science](https://r4ds.had.co.nz/introduction.html)
  - Chapter 2 on [setting-up
    R](https://csgillespie.github.io/efficientR/set-up.html) and section
    4.4 on [package
    selection](https://csgillespie.github.io/efficientR/workflow.html#package-selection)
    in the book *Efficient R Programming*

### Computing requirements

**Attendees are expected to bring their own laptop with the following
packages installed and working.** You can check these are all installed,
and install those that are not installed, as follows (you can also just
type `install.packages("sf")` etc):

``` r
install.packages("osmdata")   # for working with open street map data
install.packages("sf")        # a package for working with spatial data
install.packages("spData")    # provides example data
install.packages("stplanr")   # a transport data package
install.packages("tidyverse") # metapackage for data science
install.packages("tmap")      # a mapping package

# Make sure your packages are up-to-date with:
update.packages()
```

## Reproducible example

The code in the following example checks you have the necessary packages
installed. It results in a map that will guide you to the location of
the course.

**Please ensure the following commands work on your laptop before
attending:**

Attach the packages:

``` r
library(sf)
library(tmap)
library(osmdata)
library(stplanr)
library(tidyverse)
```

The route to get there from Leeds rail station can be generated with the
following commands, if you get the map below, congratulations your
computer has the necessary packages for the course\!

``` r
location = opq("leeds") %>% 
  add_osm_feature(key = "name", value = "Worsley Building") %>% 
  osmdata_sf()
```

``` r
route = sf::read_sf("https://git.io/fhnAr")
tm_shape(route) +
  tm_lines(col = "blue", lwd = 7, alpha = 0.4) +
  tm_shape(location$osm_polygons) +
  tm_polygons(col = "red") +
  tm_view(basemaps = leaflet::providers$OpenStreetMap) +
  tm_minimap(server = leaflet::providers$OpenTopoMap, zoomLevelOffset = -10) +
  tm_scale_bar()
```

![](2-day-course_files/figure-gfm/simplemap-1.png)<!-- -->

## Course tutor

Robin Lovelace is a researcher at the Leeds Institute for Transport
Studies ([ITS](https://environment.leeds.ac.uk/transport)) and the Leeds
Institute for Data Analytics ([LIDA](https://lida.leeds.ac.uk/)). Robin
has over a decade of experiendce using R for academic research and has
taught numerous R courses at all levels. He has developed popular R
resources including the book Efficient R Programming (Gillespie and
Lovelace [2016](http://shop.oreilly.com/product/0636920047995.do)),
Introduction to Visualising Spatial Data in R and Spatial
Microsimulation with R (Lovelace and Dumont
[2016](https://github.com/Robinlovelace/spatial-microsim-book)). These
skills have been applied on a number of projects with real-world
applications, including the Propensity to Cycle Tool
([PCT](http://www.pct.bike/)), a nationally scalable interactive online
mapping application, and the
[stplanr](https://github.com/ropensci/stplanr) package.

## References

<div id="refs" class="references">

<div id="ref-lovelace_geocomputation_2019">

Lovelace, Robin, Jakub Nowosad, and Jannes Meunchow. 2019.
*Geocomputation with R*. CRC Press.

</div>

</div>

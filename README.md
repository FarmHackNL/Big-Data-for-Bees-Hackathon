# Big Data for Bees Hackathon

![](https://forum.farmhack.nl/uploads/default/original/1X/0b80356d1becfc73f48e015a915a08d2a4dc300b.png)

**Date**: 14 & 15 December

**Location**: JADS Mariënburg Campus, Den Bosch

**Sign Up**: https://www.farmhack.nl/activiteiten/big-data-for-bees/

**Forum**: https://forum.farmhack.nl/t/about-the-big-data-for-bees-hackathon/77


On the 14th and 15th of December, at the Campus of the Jheronimus Academy of Data Science, we will be delving into Big Data and Bees with teams committed to building data driven solutions using big data technologies to help save the bees. The 30 hour hackathon is part of the [National Bee Strategy](https://www.rijksoverheid.nl/onderwerpen/natuur-en-biodiversiteit/bijenstrategie).

# Data

## Naturalis

### Modeled prediction of butterflies in The Netherlands

Maxent modelled binary (0 or 1/presen or absence) predictions for Dutch butterfly species at the scale of the Netherlands. 

Each column represents a butterfly species in the Netherlands and each row a 100 x 100 m grid cell in the Netherlands. A 1 indicates
that a species is predicted by the model to occur in that grid cell and a 0 indicatesthat a species is not predicted by the model to 
occur in that grid cell. 

The x and y coordiantes correspond to the centroids of the polygons in grid_100m_NL_rd.shp file.

![](https://raw.githubusercontent.com/FarmHackNL/Big-Data-for-Bees-Hackathon/master/images/butterflies.png)

#### Purpose
To show the predicted distribtuion of butterfly species across the Netherlands in unsampled areas.

#### Modelling protocol

The modeling is conducted using a species distribution modeling approach. Species distribution models create 
a mathematical representation of a known species' distribution within the environmental space. We used the software,  MaxEnt (version 3.4.0).
For each species we run five models with linear and quadratic terms allowed.

#### Metadata

**Filetype**: CSV, [GeoPackage](https://www.geopackage.org)

**Dimensions**: 91 Columns 3999220 Rows

**Butterfly Species**: 89  
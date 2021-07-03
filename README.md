# Surfs Up Analysis

## Overview

The goal of this analysis was to provide the client with insight into the weather patterns for a specific location in Oahu where a future shop location is being evaluated.


## Results

-The average temperature during the month of June is ~75 Degrees F

![June.png](https://github.com/crabrandoom/surfs_up/blob/main/June.PNG)

-The average temperature during the month of December is ~71 Degrees F

![December.png](https://github.com/crabrandoom/surfs_up/blob/main/December.PNG)

-The minimum temperature in December is marginally lower than in June by 8 Degrees F


## Summary


-Based on the results the temperature data for the months of June and December seem to indicate that the surf and ice cream shop business would in fact be sustainable year - round.

-Two queries that could be used to find more out about weather during the months of December and June are listed below

-session.query(Measurement.date, Measurement.prcp).filter(extract('month', Measurement.date)==6).all()

-session.query(Measurement.date, Measurement.prcp).filter(extract('month', Measurement.date)==6).all()

-These queries could be used to determine how much rainfall there is during these months which would provide useful insights for the feasibility of this shop location

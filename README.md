# Surfs Up

## Overview of the Analysis

The purpose of this statistical analysis was to evaluate temperature trends in the months of June and December in Oahu.  The analysis will aid in determining the viability of opening a surf and ice cream shop business year-round.  Python, Pandas, and SQLAlchemy were used for this analysis.

## Results

### Key Differences

- June's mean temperature was 74.94 degrees and December's mean temperature was 71.04, for a difference of 3.9 degrees
- December's minimum temperature was 8 degrees colder than June's at 56 and 64 degrees, respectively
- The 25th percentile was 73 degrees for June and 69 degrees for December, for a difference of 4 degrees

### June Temperature Summary


### December Temperature Summary


## Summary

The mean temperatures for both December and June were above 70 degrees.  Although the minimum temperature for December was 8 degrees lower than June, a majority of the days in December were above 70 degrees with the 50th percentile returning 71 degrees.  The 25th percentile for December was 69 degrees.  The maximum temperatures were only 2 degrees different with 85 degrees for June and 83 degrees for December.

### Further Analysis

Since the 25th percentile for December was 69 degrees and the low temperature was 56 degrees, I would suggest performing another query evaluating the number of days the temperatures were between 56 and 64 degrees in December since these temperatures may hamper ice cream sales.

Once we evaluate those results, I would suggest running a query for June temperatures between 64 and 69 degrees.  64 degrees was June's minimum temperature and 69 degrees was December's 25th percentile.  By determining the number of days in this temperature range for June, we can compare the results to the remainder of December's 25th percentile and evaluate if these temperatures could have any potential bearing on ice cream sales and walk-in surfing customer traffic.
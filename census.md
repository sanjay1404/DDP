==============================================================
 Developing  Data Products - Course Project

Author :Sanjay Pratap

Date: 11/04/2016


=======================================================
US census

The dataset in counties.rds contains

The name of each county in the United States

The total population of the county

The percent of residents in the county who are white, black, hispanic, or asian


=======================================================

Data

counties.rds is a dataset of demographic data for each county in the United States,

collected with the UScensus2010 R package.

========================================================
Slide With Code

counties <- readRDS("c:/census-app/data/counties.rds")

head(counties)

========================================================

Slide With Data


```r
counties <- readRDS("c:/census-app/data/counties.rds")
head(counties)
```

```
             name total.pop white black hispanic asian
1 alabama,autauga     54571  77.2  19.3      2.4   0.9
2 alabama,baldwin    182265  83.5  10.9      4.4   0.7
3 alabama,barbour     27457  46.8  47.8      5.1   0.4
4    alabama,bibb     22915  75.0  22.9      1.8   0.1
5  alabama,blount     57322  88.9   2.5      8.1   0.2
6 alabama,bullock     10914  21.9  71.0      7.1   0.2
```

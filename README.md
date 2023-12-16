# Investigating the impact of the February 2021 winter storms and power crisis on Houston, TX
A workflow investigating the impact of power outages across Houston due to three severe winter storms in February 2021

## Objectives

- estimate the number of homes in Houston that lost power as a result of the first two storms
- investigate if socioeconomic factors are predictors of communities recovery from a power outage

## What's in this repo?
```
.
|
├── Outputs/                        # visualizations and tables that the workflow should output if working correctly
|  └── income_blackout_map.png      # map of Houston indicating the median income of each census tract and whether they were impacted by blackouts
|  └── income_distributions.png     # side-by-side plots on median income distribution for impacted and non-impacted tracts
|
├── R/                                   # folder for code used in workflow
|  └── houst-freeze-impact.rmd    # a R markdown containing background and workflow
|  └── houston-freeze-impact.html    # R markdown knitted to html
|
├── README.md
├── .gitignore
└── houston-tx-freeze.Rproj
```
## Data Access

All data was stored locally and added to the .gitignore. References and links to each dataset can be found in the .rmd.

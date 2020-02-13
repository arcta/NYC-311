# DS: Exploration & Modeling
( [Data-Source](https://nycopendata.socrata.com/Social-Services/311-Service-Requests-from-2010-to-Present/erm2-nwe9) )

Intention of this exercise is to explore potential for predictive analytics using NYC-311 data.

Here we have categorical, temporal, and spatial features -- we may be interested and would expect to be able to predict:
* [the type of the complaint on its arrival given the origin](Classification.ipynb)
* [the volume of the complaints of the specific type given the time-frame and the region](Timeseries.ipynb)
* [the region with the highest expected volume of the complaints of the specific type given the time-frame](Localization.ipynb)

We also have some textual data here: it can be used for diagnostics and improvement of the process, mainly the [complaint type categorization](Taxonomy.ipynb).

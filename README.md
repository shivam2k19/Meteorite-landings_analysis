# Meteorite-landings_analysis


In this project I analyse and visualize the NASA Meteorite Landings dataset, which can be found here. The Meteoritical Society collects data on meteorites that have fallen to Earth from outer space.

## Aim of this project
This dataset offers a great opportunity to visually investigate where the chances of finding a meteorite are highest. Meteorites have fascinated me for a long time. When they enter our atmosphere as shooting stars they have often travelled for millions of kilometers. Many of the meteorites that reach our planet are very old, dating from the early days of our solar system, so they are older than the rocks from Earth.

## About the data
This dataset includes the location, mass, composition, and fall year for over 45,000 meteorites that have struck our planet. There are a few notes on Kaggle on missing or incorrect data points in this dataset, which I'll take into account during data cleaning:

a few entries here contain date information that was incorrectly parsed into the NASA database. As a spot check: any date that is before 860 CE or after 2016 are incorrect; these should actually be BCE years. There may be other errors and we are looking for a way to identify them.
a few entries have latitude and longitude of 0N/0E (off the western coast of Africa, where it would be quite difficult to recover meteorites). Many of these were actually discovered in Antarctica, but exact coordinates were not given. 0N/0E locations should probably be treated as NA.

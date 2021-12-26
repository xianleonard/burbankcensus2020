# burbankcensus2020
A breakdown of 2010 and 2020 Census data for census tracts in Burbank, CA.

This analysis was conducted via R for two Burbank Leader articles [Census Data Shows a Growing, Slightly More Diverse Burbank](https://outlooknewspapers.com/blog/2021/09/01/census-data-shows-a-growing-slightly-more-diverse-burbank) and [Area Near Airport Is the City’s Fastest Growing](https://outlooknewspapers.com/blog/2021/09/08/area-near-airport-is-the-citys-fastest-growing)).

Data was obtained through R's [Tidycensus](https://github.com/walkerke/tidycensus) package.

Output folder contains selected Burbank Census variables for 2010, 2020 and both. These variables are:
- Total population
- Population of residents who identified with a single race
- Population of residents who identified with two or more races
- Population of residents who identified only as white/Black/American Indian or Alaska Native/Asian/Native Hawaiian or Pacific Islander/another race
- Population of residents who identified as Hispanic (note that this category, being separate from how the Census categorizes racial groups, includes all such groups)
- Number of housing units

Note that the map linked in the above story (and in the Outputs) folder includes a census tract that was split into two tracts in 2020. The map shows the tract as it was, pre-split, in 2010 for easier comparison between the decades' data.

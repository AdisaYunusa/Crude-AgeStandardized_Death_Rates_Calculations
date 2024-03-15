# Crude and Age-standardized Death Rates Calculations
A Python script that calculates both the crude death rate and the age-standardized death rate for COPD for all ages in both the United States and Uganda for 2019.

Resources were throughly reviewed and key parameters required for the calculation were identified. These parameters included the total population of each country, the period of the population data to be used, the number of deaths in each country, and the age-group population proportion. The resources used for this exercise includes the following:
  i. UN World Population Prospects (2022) — Population Estimates 1950-2021
  ii. WHO Standard Population — Table 1 in 'Ahmad OB, Boschi-Pinto C, Lopez AD, Murray CJ, Lozano R, Inoue M (2001). Age standardization of rates: a new WHO standard.'

Assumptions made included choosing the WHO World Standard for age-standardization as it facilitates international comparisons and adopts a standard based on the average age structure of populations. Additionally, I used the mid-2019 population figures for both countries, as this is considered a more accurate representation of the population size over the entire year. Finally, I sourced the total number of deaths in the US and Uganda in 2019 from the UN World Population Prospects (2022) database.

After implementing the necessary calculations, the results indicate notable differences between the crude and age-standardized death rates for both countries. Specifically, the crude death rate for the US is calculated at 830.9 per 100,000 people, while the age-standardized death rate is 28.4 per 100,000 people. Conversely, for Uganda, the crude death rate stands at 582.1 per 100,000 people, with an age-standardized death rate of 28.7 per 100,000 people.

The differences between the death rates can be attributed to variations in the age distributions of the populations. Crude death rates provide a straightforward measure of mortality within a population but do not account for differences in age structures between populations. In contrast, age-standardized death rates adjust for variations in age distributions, allowing for a more accurate comparison of mortality rates between populations with different age structures. Also, the disparities in the total population sizes and number of deaths in the United States and Uganda contribute to differences in crude death rates. Age-standardized death rates mitigate this factor by standardizing mortality rates to a common population structure, facilitating meaningful comparisons.
"""

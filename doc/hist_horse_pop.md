## Aim

This project explores the historical population of horses in Canada
between 1906 and 1972 for each Province.

## Data

Horse population data were sourced from the [Government of Canada’s Open
Data website](http://open.canada.ca/en/open-data). Specifically, these
two sources were used:

-   [Horses, number on farms at June 1 and at December
    1](http://open.canada.ca/data/en/dataset/43b3a9b3-3842-45e7-8bc8-c4c27b9462ab)
-   [Horses, number on farms at June 1, farm value per head and total
    farm
    value](http://open.canada.ca/data/en/dataset/b374f60b-9580-44dc-83f6-c0a850c15f30)

## Methods

The R programming language and the following R packages were used to
perform the analysis: knitr and tidyverse. The code used to perform the
analysis and create this report can be found here:
<https://github.com/ttimbers/equine_numbers_value_canada_rmd>.

## Results

<img src="hist_horse_pop_files/figure-markdown_strict/plot horses-1.png" alt="Figure Number of horses per province between 1906 and 1972" width="80%" height="80%" />
<p class="caption">
Figure Number of horses per province between 1906 and 1972
</p>

We can see from the visualisation above that Ontario, Saskatchewan and
Alberta have had the highest horse populations in Canada. All provinces
have had a decline in horse populations since 1940. This is likely due
to the rebound of the Canadian automotive industry after the Great
Depression and the Second World War. An interesting follow-up
visualization would be car sales per year for each Province over the
time period visualised above to further support this hypothesis.

Next we look at the range of the number horses for each provinces at any
time point between 1940 - 1972:

<table>
<caption>Table 1. Range of the number horses for each provinces at any
time point between 1940 - 1972</caption>
<thead>
<tr class="header">
<th style="text-align: left;">Province</th>
<th style="text-align: right;">Maximum</th>
<th style="text-align: right;">Minimum</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="text-align: left;">Alberta</td>
<td style="text-align: right;">806200</td>
<td style="text-align: right;">87000</td>
</tr>
<tr class="even">
<td style="text-align: left;">British Columbia</td>
<td style="text-align: right;">65200</td>
<td style="text-align: right;">22500</td>
</tr>
<tr class="odd">
<td style="text-align: left;">Manitoba</td>
<td style="text-align: right;">370800</td>
<td style="text-align: right;">31000</td>
</tr>
<tr class="even">
<td style="text-align: left;">New Brunswick</td>
<td style="text-align: right;">71000</td>
<td style="text-align: right;">3200</td>
</tr>
<tr class="odd">
<td style="text-align: left;">Nova Scotia</td>
<td style="text-align: right;">64500</td>
<td style="text-align: right;">3600</td>
</tr>
<tr class="even">
<td style="text-align: left;">Ontario</td>
<td style="text-align: right;">822300</td>
<td style="text-align: right;">75400</td>
</tr>
<tr class="odd">
<td style="text-align: left;">Prince Edward Island</td>
<td style="text-align: right;">36700</td>
<td style="text-align: right;">2200</td>
</tr>
<tr class="even">
<td style="text-align: left;">Quebec</td>
<td style="text-align: right;">378800</td>
<td style="text-align: right;">39000</td>
</tr>
<tr class="odd">
<td style="text-align: left;">Saskatchewan</td>
<td style="text-align: right;">1104300</td>
<td style="text-align: right;">58000</td>
</tr>
</tbody>
</table>

Table 1. Range of the number horses for each provinces at any time point
between 1940 - 1972

Below we zoom in and look at the province of Quebec:

Figure 2. Historical number of horses in Quebec
<img src="hist_horse_pop_files/figure-markdown_strict/plot province-1.png" width="80%" height="80%" />

# References

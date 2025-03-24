# License
This data was generated using data from the Redistricting Data Hub.  Any use of this project shall also comply with restrictions on use of data and attribution requirements set forth in the Redistricting Data Hub terms and conditions found at: [https://redistrictingdatahub.org/terms-and-conditions/](https://redistrictingdatahub.org/terms-and-conditions/).

Use of this project is further governed by the terms of the [Creative Commons Attribution Noncommercial 4.0 International](https://creativecommons.org/licenses/by-nc/4.0/legalcode.en)

# Delaware Json and Shapefile

This shapefile was processed by Professor Ellen Veomett and her student Arbie Hsu using the corresponding jupyter notebook.  As part of the cleaning process, small rook adjacencies (under 30.5 m) were changed to queen adjacencies.  Note that wee were *not* able to successfully nest precincts within counties for this state.

# **Sources**

The following obtained from [Redistricting Data Hub](https://redistrictingdatahub.org/) on June, 2024:

[Population data](https://redistrictingdatahub.org/dataset/delaware-block-pl-94171-2020-by-table/): based on the decennial census at the Census Block level on 2020 Census Redistricting Data

[County data](https://redistrictingdatahub.org/dataset/delaware-county-pl-94171-2020/): from 2020 Census Redistricting Data (P.L. 94-171) Shapefiles (Nesting within counties did not work for us, so this data is not used in the notebook)

[State House District data](https://redistrictingdatahub.org/dataset/2021-delaware-state-house-adopted-plan/): 2022 State House Approved Interim Plan

[State Senate District data](https://redistrictingdatahub.org/dataset/2021-delaware-state-senate-adopted-plan/): 2022 State Senate Districts Interim Plan from

[2020 election data](https://redistrictingdatahub.org/dataset/vest-2020-delaware-precinct-and-election-results/): VEST 2020 precinct and election results

[2018 election data](https://redistrictingdatahub.org/dataset/vest-2018-delaware-precinct-and-election-results/): VEST 2018 precinct and election results

[2016 election data](https://redistrictingdatahub.org/dataset/vest-2016-delaware-precinct-and-election-results/): VEST 2016 precinct and election results

# **Processing**

Demographic data were aggregated from the census block level and precincts were assigned to districts using [maup](https://github.com/mggg/maup).

# **Metadata**

Below is a brief description of each of the listed variables in the attribute table of the VTD shapefile:

- `PRECINCT20`: Precinct identifier based on precinct of 2020
- `SEND`: State Senate district for 2022 State Senate Adopted Plan
- `HDIST`: State House district for 2022 State House of Representatives Districts Plan
- `TOTPOP`: Total population in 2020 Census
- `NH_WHITE`: White, non-hispanic, population in 2020 Census
- `NH_BLACK`: Black, non-hispanic, population in 2020 Census
- `NH_AMIN`: American Indian and Alaska Native, non-hispanic, population in 2020 Census
- `NH_ASIAN`: Asian, non-hispanic, population in 2020 Census
- `NH_NHPI`: Native Hawaiian and Pacific Islander, non-hispanic, population in 2020 Census
- `NH_OTHER`: Other race, non-hispanic, population in 2020 Census
- `NH_2MORE`: Two or more races, non-hispanic, population in 2020 Census
- `HISP`: Hispanic population in 2020 Census
- `H_WHITE`: White, hispanic, population in 2020 Census
- `H_BLACK`: Black, hispanic, population in 2020 Census
- `H_AMIN`: American Indian and Alaska Native, hispanic, population in 2020 Census
- `H_ASIAN`: Asian, hispanic, population in 2020 Census
- `H_NHPI`: Native Hawaiian and Pacific Islander, hispanic, population in 2020 Census
- `H_OTHER`: Other race, hispanic, population in 2020 Census
- `H_2MORE`: Two or more races, hispanic, population in 2020 Census
- `VAP`: Total voting age population in 2020 Census
- `HVAP`: Hispanic voting age population in 2020 Census
- `WVAP`: White, non-hispanic, voting age population in 2020 Census
- `BVAP`: Black, non-hispanic, voting age population in 2020 Census
- `AMINVAP`: American Indian and Alaska Native, non-hispanic, voting age population in 2020 Census
- `ASIANVAP`: Asian, non-hispanic, voting age population in 2020 Census
- `NHPIVAP`: Native Hawaiian and Pacific Islander, non-hispanic, voting age population in 2020 Census
- `OTHERVAP`: Other race, non-hispanic, voting age population in 2020 Census
- `2MOREVAP`: Two or more races, non-hispanic, voting age population in 2020 Census
- `AGR18D`:  Number of votes for 2018 Democratic Commissioner of Agriculture
- `AGR18R`:  Number of votes for 2018 Republican Commissioner of Agriculture
- `AUD18D`: Number of votes for 2018 Democratic Auditor
- `AUD18R`: Number of votes for 2018 Republican Auditor
- `GOV16R`: Number of votes for 2016 Republican gubernatorial candidate
- `GOV16D`: Number of votes for 2016 Democratic gubernatorial candidate
- `GOV16O`: Number of votes for 2016 other party's gubernatorial candidate
- `GOV20R`: Number of votes for 2020 Republican gubernatorial candidate
- `GOV20D`: Number of votes for 2020 Democratic gubernatorial candidate
- `GOV20O`: Number of votes for 2020 other party's gubernatorial candidate
- `HAL16D`: Number of votes for 2016 Democratic of U.S. House where district number is at large
- `HAL16O`: Number of votes for 2018 other party's of U.S. House where district number is at large
- `HAL16R`: Number of votes for 2018 Republican of U.S. House where district number is at large
- `HAL18D`: Number of votes for 2018 Democratic of U.S. House where district number is at large
- `HAL18R`: Number of votes for 2018 Republican of U.S. House where district number is at large
- `HAL20D`: Number of votes for 2020 Democratic of U.S. House where district number is at large
- `HAL20R`: Number of votes for 2020 other party's of U.S. House where district number is at large
- `HAL20R`: Number of votes for 2020 Republican of U.S. House where district number is at large
- `INS16D`: Number of votes for 2016 Democratic Commissioner of Insurance
- `INS16R`: Number of votes for 2016 Republican Commissioner of Insurance
- `INS20D`: Number of votes for 2020 Democratic Commissioner of Insurance
- `INS20R`: Number of votes for 2020 Republican Commissioner of Insurance
- `LTG16D`: Number of votes for 2016 Democratic Lieutenant Governor
- `LTG16R`: Number of votes for 2016 Republican Lieutenant Governor
- `LTG20D`: Number of votes for 2020 Democratic Lieutenant Governor
- `LTG20R`: Number of votes for 2020 Republican Lieutenant Governor
- `PRE16D`: Number of votes for 2016 Democratic President
- `PRE16O`: Number of votes for 2016 other party's President
- `PRE16R`: Number of votes for 2016 Republican President
- `PRE20D`: Number of votes for 2020 Democratic President
- `PRE20R`: Number of votes for 2020 Republican President
- `PRE20O`: Number of votes for 2020 other party's President
- `TRE18D`: Number of votes for 2018 Democratic Treasurer
- `TRE18O`: Number of votes for 2018 Republican Treasurer
- `TRE18R`: Number of votes for 2018 other party's Treasurer
- `USS18D`: Number of votes for 2018 Democratic senate candidate
- `USS18R`: Number of votes for 2018 Republican senate candidate
- `USS18O`: Number of votes for 2018 other party's senate candidate
- `USS20D`: Number of votes for 2020 Democratic senate candidate
- `USS20R`: Number of votes for 2020 Republican senate candidate
- `USS20O`: Number of votes for 2020 other party's senate candidate

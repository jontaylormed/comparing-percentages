# Sources and verified data: Comparing Percentages (Lesson 02)

**Date checked for every figure in this file: 2026-11-25.**

Every number in the data table below was read from the Census table itself, opened on data.census.gov during this check. Nothing comes from memory.

**Labels used in this file**

- **Published** means a number the Census table prints, exactly as printed.
- **Calculated** means a number worked out from published numbers, for the lesson or its quiz. Each calculation is shown.
- **MOE** means margin of error. The Census prints it at the 90% confidence level. A published estimate of 57.2 with MOE ±2.0 means the true value is likely between 55.2 and 59.2.

---

## Source

| ID | Organization and document | Direct URL | Student search |
|---|---|---|---|
| S1 | U.S. Census Bureau, American Community Survey (ACS) 5-Year Estimates, 2021 (survey years 2017-2021), Table **S0502**, *Selected Characteristics of the Foreign-Born Population by Period of Entry into the United States* | https://data.census.gov/table/ACSST5Y2021.S0502?g=060XX00US5303392928 | On data.census.gov, type **S0502 Seattle CCD, King County, Washington** in the search box, then choose the 2021 ACS 5-Year table. |
| S2 | U.S. Citizenship and Immigration Services (USCIS), *I am a Lawful Permanent Resident of 5 Years* | https://www.uscis.gov/citizenship/learn-about-citizenship/citizenship-and-naturalization/i-am-a-lawful-permanent-resident-of-5-years | "USCIS lawful permanent resident of 5 years naturalization" |
| S3 | USCIS, *I am Married to a U.S. Citizen* | https://www.uscis.gov/citizenship/learn-about-citizenship/citizenship-and-naturalization/i-am-married-to-a-us-citizen | "USCIS naturalization married to a U.S. citizen" |

**Geography.** Seattle CCD, King County, Washington. A CCD (census county division) is an area the Census Bureau draws for statistics. GEOID 5303392928. The Census Geocoder places downtown Seattle in this CCD. The lesson calls it "the Seattle CCD (a Census area that includes the city of Seattle)." It is not the same as the city limits or the metro area.

**The three groups** are the table's own columns: entered the U.S. 2010 or later (Group A), 2000 to 2009 (Group B), and before 2000 (Group C). "Foreign-born" means anyone who was not a U.S. citizen at birth. That includes naturalized citizens, permanent residents, refugees, students and other temporary residents, and people without legal status.

The same numbers are available from the Census Data API: `https://api.census.gov/data/2021/acs/acs5/subject?get=group(S0502)&ucgid=0600000US5303392928`. The API now asks for a free key.

---

## Published figures used in the lesson (S1)

Percentages are shares of the row's universe, which is the group named in the Universe column. MOE is shown in parentheses.

| Line | Row (Census label) | Universe | Total | Group A (2010 or later) | Group B (2000-2009) | Group C (before 2000) |
|---|---|---|---|---|---|---|
| 001 | Foreign-born population | people | 254,278 (±4,554) | 91,815 (±3,653) | 61,921 (±3,011) | 100,542 (±2,824) |
| 002 | Citizenship: Naturalized citizen | % of people | 48.8 (±1.0) | 11.6 (±1.1) | 54.8 (±2.1) | 79.0 (±1.4) |
| 003 | Citizenship: Not a citizen | % of people | 51.2 (±1.0) | 88.4 (±1.1) | 45.2 (±2.1) | 21.0 (±1.4) |
| 005 | World region of birth: Europe | % of people | 11.4 (±0.8) | 9.9 (±1.5) | 10.3 (±1.6) | 13.4 (±1.1) |
| 006 | World region of birth: Asia | % of people | 53.2 (±1.0) | 57.2 (±2.0) | 41.1 (±2.1) | 56.9 (±1.4) |
| 007 | World region of birth: Africa | % of people | 12.2 (±0.6) | 15.5 (±1.6) | 16.5 (±1.5) | 6.5 (±0.8) |
| 008 | World region of birth: Oceania | % of people | 1.8 (±0.3) | 1.8 (±0.6) | 2.2 (±0.6) | 1.7 (±0.4) |
| 009 | World region of birth: Latin America | % of people | 17.7 (±0.7) | 12.6 (±1.2) | 26.3 (±2.0) | 17.1 (±1.0) |
| 010 | World region of birth: Northern America | % of people | 3.7 (±0.3) | 2.9 (±0.5) | 3.5 (±0.8) | 4.4 (±0.5) |
| 013 | Age: Under 5 years | % of people | 0.7 (±0.2) | 2.0 (±0.5) | N/A | N/A |
| 014 | Age: 5 to 17 years | % of people | 4.6 (±0.5) | 10.1 (±1.1) | 4.1 (±0.7) | 0.0 (±0.1) |
| 015 | Age: 18 to 24 years | % of people | 8.3 (±0.4) | 14.7 (±1.0) | 9.8 (±1.1) | 1.5 (±0.3) |
| 016 | Age: 25 to 44 years | % of people | 45.0 (±0.7) | 59.3 (±1.5) | 53.3 (±2.1) | 26.9 (±1.2) |
| 017 | Age: 45 to 54 years | % of people | 16.4 (±0.6) | 6.6 (±0.8) | 18.7 (±1.4) | 24.0 (±1.1) |
| 018 | Age: 55 to 64 years | % of people | 11.9 (±0.5) | 4.2 (±0.8) | 7.9 (±1.0) | 21.4 (±1.0) |
| 019 | Age: 65 to 74 years | % of people | 7.6 (±0.4) | 2.3 (±0.5) | 3.5 (±0.8) | 15.0 (±0.8) |
| 020 | Age: 75 to 84 years | % of people | 3.7 (±0.3) | 0.8 (±0.2) | 1.8 (±0.5) | 7.6 (±0.8) |
| 021 | Age: 85 years and over | % of people | 1.6 (±0.2) | 0.1 (±0.1) | 0.9 (±0.3) | 3.5 (±0.5) |
| 022 | Median age (years) | people | 40.5 (±0.5) | 30.0 (±0.3) | 38.9 (±0.6) | 53.9 (±0.6) |
| 042 | Population 3 years and over enrolled in school | people | 37,265 (±1,942) | 24,793 (±1,566) | 8,507 (±813) | 3,965 (±547) |
| 048 | Education: Less than high school graduate | % of people 25+ | 18.8 (±0.8) | 13.1 (±1.4) | 22.8 (±1.7) | 20.4 (±1.3) |
| 049 | Education: High school graduate (includes equivalency) | % of people 25+ | 17.0 (±0.8) | 15.1 (±1.6) | 18.1 (±1.4) | 17.8 (±1.1) |
| 050 | Education: Some college or associate's degree | % of people 25+ | 19.0 (±0.8) | 12.5 (±1.2) | 19.8 (±1.6) | 23.0 (±1.2) |
| 051 | Education: Bachelor's degree | % of people 25+ | 22.9 (±0.9) | 24.5 (±1.9) | 21.1 (±1.4) | 22.9 (±1.3) |
| 052 | Education: Graduate or professional degree | % of people 25+ | 22.3 (±0.7) | 34.8 (±1.8) | 18.3 (±1.5) | 15.9 (±1.1) |
| 055 | Language other than English at home | % of people 5+ | 82.3 (±0.7) | 87.6 (±1.3) | 85.0 (±1.4) | 75.9 (±1.2) |
| 058 | In labor force (working or looking for work) | % of people 16+ | 72.3 (±0.7) | 73.4 (±1.3) | 79.2 (±1.6) | 67.2 (±1.2) |
| 060 | Civilian labor force: Employed | % of people 16+ | 69.2 (±0.8) | 69.4 (±1.5) | 75.8 (±1.8) | 65.1 (±1.2) |
| 095 | Full-time, year-round workers' earnings: $75,000 or more | % of people 16+ with earnings | 43.2 (±1.3) | 54.2 (±2.4) | 33.2 (±2.5) | 41.2 (±2.3) |
| 098 | Households | households | 112,833 (±2,293) | 33,946 (±1,512) | 26,383 (±1,437) | 52,504 (±1,715) |
| 110 | Median household income (dollars) | households | 85,893 (±3,083) | 95,809 (±11,184) | 75,355 (±4,708) | 86,085 (±3,852) |
| 113 | Poverty: Below 100 percent of the poverty level | % of people (poverty universe) | 14.1 (±0.8) | 18.4 (±1.7) | 13.7 (±1.3) | 10.6 (±1.0) |
| 114 | Poverty: 100 to 199 percent of the poverty level | % of people (poverty universe) | 14.2 (±0.9) | 15.0 (±1.4) | 16.6 (±1.9) | 11.9 (±1.2) |
| 115 | Poverty: At or above 200 percent of the poverty level | % of people (poverty universe) | 71.7 (±1.1) | 66.6 (±2.1) | 69.7 (±2.2) | 77.5 (±1.4) |
| 126 | Housing tenure: Owner-occupied housing units | % of households | 43.6 (±1.1) | 22.2 (±2.1) | 37.2 (±2.5) | 60.7 (±1.6) |
| 127 | Housing tenure: Renter-occupied housing units | % of households | 56.4 (±1.1) | 77.8 (±2.1) | 62.8 (±2.5) | 39.3 (±1.6) |
| 141 | Owner-occupied housing units | households | 49,212 (±1,385) | 7,540 (±809) | 9,827 (±825) | 31,845 (±1,226) |

N/A: the table prints no estimate for children under 5 in Groups B and C (the Census marks it "not applicable"). In the lesson's age chart, "Under 18" is lines 013 + 014. For Group A that is 2.0 + 10.1 = 12.1; for Group B, 4.1; for Group C, 0.0.

---

## Calculated figures in the lesson (from the published figures above)

| Figure in the lesson | Calculation | Where it appears |
|---|---|---|
| 52,518 Asian-born people in Group A | 91,815 × 0.572 = 52,518.2 | Part 1 worked example; chart |
| About 5,000 more Asian-born people in Group C than in Group A | 100,542 × 0.569 = 57,208.4; 57,208 − 52,518 = 4,690 | Part 1 |
| 18.9 percentage points | 34.8 − 15.9 | Part 2, Mistake 2, summary |
| 2.2× | 34.8 ÷ 15.9 = 2.19 | Part 2, Mistake 2, summary |
| 7.8 percentage points | 18.4 − 10.6 | Compare: poverty |
| 38.5 percentage points; about 2.7× | 60.7 − 22.2; 60.7 ÷ 22.2 = 2.73 | Compare: home ownership |
| 6.8× | 79.0 ÷ 11.6 = 6.81 | Compare: citizenship |
| About half; less than half | 12.6 ÷ 26.3 = 0.48; 6.5 ÷ 15.5 = 0.42 | Compare: region |
| Africa's share more than doubled | 15.5 ÷ 6.5 = 2.38 | Step 1 |
| About 12 to 21 years; more than 21 years in the U.S. | Group B, counted at 2021: 2021 − 2009 = 12 and 2021 − 2000 = 21. Group C entered in 1999 or earlier: 2021 − 1999 = 22, so more than 21. (Survey answers span 2017-2021, so some are a few years fewer.) | Step 1 |
| Quiz 1: 67.4 percentage points (wrong choices 109.4, 4.2, 21.0) | 88.4 − 21.0 = 67.4; 88.4 + 21.0 = 109.4; 88.4 ÷ 21.0 = 4.2 | Quiz |
| Quiz 2: about 2.1× (wrong choice 13.7 points) | 26.3 ÷ 12.6 = 2.09; 26.3 − 12.6 = 13.7 | Quiz |
| Quiz 3: about 31,900 households (published count 31,845) | 52,504 × 0.607 = 31,869.9 | Quiz; feedback |
| Quiz 3 wrong choices: 11,700; 20,600; 61,000 | 52,504 × 0.222 = 11,656 (Group A's rate); 52,504 × 0.393 = 20,634 (renters); 100,542 × 0.607 = 61,029 (people instead of households) | Quiz |
| 7,536 and 31,870 homeowner households; about 4 times as many | 33,946 × 0.222 = 7,536; 52,504 × 0.607 = 31,870; published 31,845 ÷ 7,540 = 4.22 | Reveal card; Quiz 4 |
| About 1.1 times as many people | 100,542 ÷ 91,815 = 1.10 | Reveal card |
| $95.8k, $75.4k, $86.1k | 95,809, 75,355, 86,085 ÷ 1,000, rounded | "Highest income and highest poverty" chart |

---

## Corrections made on 2026-11-25 (the lesson was first built without a sources file)

1. **Homeownership used the wrong whole.** The rates (22.2%, 60.7%) are shares of *households*, not of people. The lesson multiplied them by the number of *people* ("100,542 × 0.607 ≈ 61,029 homeowners"; "Group A ≈ 20,383"; "3× as many homeowners"). Quiz 3, Quiz 4 and a reveal card now use households: 52,504 × 0.607 ≈ 31,870 (published count 31,845), and Group C has about 4 times as many homeowner households as Group A (31,845 vs 7,540).
2. **Quiz 4's premise was false.** It said Group A "has the most people." Group C does (100,542). The question now compares Groups A and C, which are close in size.
3. **"More than half of each group was born in Asia" was false** for Group B (41.1%). It now says Asia is the most common region in every group.
4. **Years in the U.S. were wrong.** Group B "been here 15-25 years" is now about 12 to 21 years by 2021. Group C "25+ years" is now more than 21 years.
5. **The data was described as a count.** "The U.S. Census counted every immigrant living in the Seattle area in 2021" now says the ACS *estimates* this for the Seattle CCD during 2017-2021.
6. **"Most workers" was the labor force rate** (working or looking for work). It now says so.
7. **"About 82% of all groups"** was the overall figure (82.3%), not each group's. The group figures run from 75.9% to 87.6%.
8. **The citizenship rule** now matches USCIS (S2, S3): most people must be a permanent resident for at least 5 years, or 3 if married to a U.S. citizen.
9. **Claims the table can't support were replaced with its own numbers.** Statements about tech workers, refugees and why people came became figures from the table: the share of full-time workers earning $75,000 or more, and school enrollment.
10. **A margin-of-error note was added.** Group A's median household income ($95,809 ± $11,184) and Group C's ($86,085 ± $3,852) overlap within their margins, so the table can't show that Group A's median is truly higher. The lesson now says so.
11. **Fixed in the page code:** right answers no longer show two check marks, and a wrong answer now highlights the right one.

## How this was counted and who may be missing

- **It's a survey.** The ACS samples households over five years (2017-2021) and weights the answers to estimate the whole population. Every figure has a margin of error.
- **Period of entry is self-reported.** It's the year a person says they came to live in the U.S., which may differ from when they first arrived.
- **Groups differ in age.** Group C is much older (median 53.9 vs 30.0), and age affects income, homeownership and citizenship. Comparing groups doesn't control for age.
- **Medians and rates describe groups, not individuals.** A group's rate can't say anything about any one person.

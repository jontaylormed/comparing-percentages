# Comparing Percentages

Compare percentages across groups with real Census data, and learn when to subtract and when to divide.

**Live site:** <https://jontaylormed.github.io/comparing-percentages/>

**Source:** <https://github.com/jontaylormed/comparing-percentages>

**Site created by Claude and Jon Taylor.**

[![License: CC BY-NC-SA 4.0](https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by-nc-sa/4.0/)

---

## What it does

The data describes 254,278 people born outside the U.S. who live in the Seattle CCD, a Census area that includes the city of Seattle. They are in three groups by when they came to live in the U.S. The source is the U.S. Census Bureau, American Community Survey 2017–2021, Table S0502.

| Section | What the student does |
|---|---|
| Meet the Data | Meets the three groups and sees where each group's people were born |
| Explore the Data | Looks at age, education, housing, income, citizenship and language before any math, and opens three "surprising fact" cards |
| What Is a Percentage? | Turns a percentage into a count of people (91,815 × 0.572 ≈ 52,518) |
| Comparing Percentages | Picks a topic, reads the chart, and compares groups three ways: which is bigger, the gap in percentage points (subtract), and the ratio (divide) |
| Common Mistakes | Sees three traps: same percentage but different counts, points vs. ratios, and one number hiding a split group |
| Quiz | Answers five questions with feedback on each |
| Reflection | Picks one of four questions, writes an answer and downloads it as a text file to hand in |

## Who it's for

Grades 7–10.

Common Core State Standards for Mathematics:

| Standard | What it asks |
|---|---|
| 6.RP.A.3c | Find a percent of a quantity as a rate per 100 |
| 7.RP.A.3 | Use proportional relationships to solve multistep ratio and percent problems |
| HSS.ID.B.5 | Summarize categorical data in two-way frequency tables and interpret relative frequencies in context, including conditional ones |
| MP3 | Construct viable arguments and critique the reasoning of others |

## How it teaches

- **See it first.** Students look at the data, with no math, before they compare anything. Every comparison has a chart beside it.
- **Structure before numbers.** Before calculating, students decide what kind of comparison a question needs: subtract for a gap in percentage points, or divide for "how many times bigger."
- **Check every claim.** Every figure comes from one Census table, and the lesson shows its fine print. Homeownership is a share of households, not people. Group A's median income has a margin of error of ±$11,184, so it may not truly be higher than Group C's.
- **Students draw the conclusions.** The lesson shows what the table says and what it can't say, such as why people came. The reflection questions are about the data and the math, never about students' own circumstances.

## How the math was checked

- **Sources:** [`sources.md`](sources.md) lists every published figure the lesson uses (37 rows of Table S0502, with margins of error), every calculated figure with its arithmetic, the geography and the table link. Each figure was read from the table on data.census.gov on November 25, 2026. The citizenship rule comes from USCIS.
- **Checks page:** [`checks.html`](https://jontaylormed.github.io/comparing-percentages/checks.html) runs 86 checks in the browser. All 86 pass. It compares:
  - every chart value with its row in `sources.md`;
  - every number in the lesson's text and feedback: each one must be a published figure or a listed calculation;
  - each calculation and quiz answer key;
  - keyboard use, contrast and chart descriptions;
  - the page itself, for outside requests, stored data and email addresses.
- **Fixed after checking.** The lesson was first built without a sources file. Checking it against the table found these errors, all now fixed (`sources.md` lists each change):
  - homeowner counts multiplied a share of households by a number of people;
  - Quiz 4 was built on a false premise (Group C, not A, has the most people);
  - "more than half of each group was born in Asia" was false for Group B;
  - the years each group had lived in the U.S. were wrong;
  - the data was described as a count of everyone rather than a survey estimate.
- **Known limits:**
  - ACS figures are estimates from a survey, each with a margin of error.
  - Groups differ in age, which affects income, homeownership and citizenship.
  - Group rates say nothing about any one person.

## Accessibility

- **Keyboard:** everything works with the keyboard, and focus outlines are visible.
  - The step dots, "surprising fact" cards and reflection questions work with Tab, then Enter or Space.
  - Moving to a new step puts focus on its heading.
- **Contrast:** text meets the WCAG 2.1 AA target of 4.5:1. Body text is 15:1, grey helper text 6:1 or better, and button text 7:1.
- **Screen readers:**
  - Every chart has a text description that includes its numbers.
  - Quiz feedback and each topic's "what this means" note are read aloud.
  - The name and answer boxes are labeled.
- **Motion:** when the device asks for reduced motion, the charts, transitions and scrolling stop animating.
- **Text size:** there is no separate setting; the page follows browser zoom.

## Privacy

- No accounts, no tracking, no cookies and no stored data. Nothing a student types is sent anywhere.
- A student's name is used only on screen and inside the reflection file they download. That file stays on their own device until they hand it in.
- The page makes no network requests. Chart.js and both typefaces are built into the file, and `checks.html` confirms nothing loads from outside.

## Running it

Open `index.html` in any modern browser.

`checks.html` reads `sources.md`, so open it from the live site or any local web server, not as a file.

**Publishing:** GitHub Pages, deployed from the `main` branch at the repository root. There is no build step.

## License

[CC BY-NC-SA 4.0](LICENSE). Free to share and adapt for non-commercial use, with credit, under the same license. The data comes from the U.S. Census Bureau.

Bundled code and typefaces keep their own licenses:

| Component | Used for | Author | License |
|---|---|---|---|
| Chart.js 4.4.1 | Charts | Chart.js Contributors | [MIT](LICENSE-chartjs.md) |
| Syne | Headings | The Syne Project Authors | [SIL Open Font License 1.1](fonts/OFL-syne.txt) |
| IBM Plex Sans | Body text | IBM Corp. | [SIL Open Font License 1.1](fonts/OFL-ibmplexsans.txt) |

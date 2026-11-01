# Real Estate Math: November 1, 2026 verification

## November 1 weekly refresh

Review interval: October 25–November 1. The [Freddie Mac](https://www.freddiemac.com/pmms) 30-year mortgage benchmark is 7.24% dated October 29, versus 7.32% October 22, down 8 basis points. The calculator RATE changed to 7.24. A hypothetical $300,000, 30-year loan has monthly principal and interest of $2,044.49 versus $2,060.79, saving $16.30 monthly. Taxes, insurance, PMI, HOA and fees are excluded; this is a benchmark illustration, not a lender quote.

Finance receipt: `macro_snapshot_mortgage__United_States_d79677.csv`, row `USA3YMR`, latest_value_date `2026-10-29`, latest_value `7.24`, previous_value `7.32`. Metadata: `web/direct-files/777bba1d82f723c4a17e27a546b4a5a5/166bebd3-6181-428b-a20f-cc1462056851/csv/882494ba_macro_snapshot_mortgage__United_States_d79677.csv.metadata.json`.

Fresh checks of the [NC REALTORS index](https://www.ncrealtors.org/resources/news-data/market-data/) and [September report](https://www.ncrealtors.org/wp-content/uploads/September-2026-Housing-Report.pdf) still show September as latest: median $370,000 (+0.7% YoY), 11,429 sales (-11% YoY), 5.93 months inventory. [Realtor.com/FRED listing DOM](https://fred.stlouisfed.org/series/MEDDAYONMARNC) remains 69 for September versus 66 August, last updated October 1; next release listed November 5. These are unchanged published monthly observations.

All ten county pages were verified in a rendered browser after fresh fetch failures. Exact medians, price YoY, DOM and September sales match the October 25 snapshot. No October reporting period was observed. Redfin describes prices as three-month rolling medians ending September; homes sold are September totals stated in the page narrative. City labels represent countywide data. No weekly listings, pendings or closings dataset was retrieved; unchanged published data do not establish unchanged weekly market activity.

| County / source | Median | Price YoY | DOM | September sold | Change vs October 25 snapshot |
|---|---:|---:|---:|---:|---|
| [Forsyth](https://www.redfin.com/county/2040/NC/Forsyth-County/housing-market) | $309,308 | -1.8% | 51 | 378 | None |
| [Guilford](https://www.redfin.com/county/2047/NC/Guilford-County/housing-market) | $304,568 | -1.8% | 40 | 479 | None |
| [Davie](https://www.redfin.com/county/2036/NC/Davie-County/housing-market) | $322,421 | -7.9% | 61 | 63 | None |
| [Rockingham](https://www.redfin.com/county/2085/NC/Rockingham-County/housing-market) | $240,050 | +3.7% | 56 | 97 | None |
| [Wilkes](https://www.redfin.com/county/2103/NC/Wilkes-County/housing-market) | $258,921 | +4.2% | 79 | 33 | None |
| [Watauga](https://www.redfin.com/county/2101/NC/Watauga-County/housing-market) | $583,694 | -6.2% | 97 | 100 | None |
| [Avery](https://www.redfin.com/county/2012/NC/Avery-County/housing-market) | $476,434 | +36.1% | 115 | 56 | None |
| [Ashe](https://www.redfin.com/county/2011/NC/Ashe-County/housing-market) | $498,834 | +17.4% | 88 | 39 | None |
| [Wake](https://www.redfin.com/county/2098/NC/Wake-County/housing-market) | $463,962 | -0.22% | 47 | 1,342 | None |
| [Surry](https://www.redfin.com/county/2092/NC/Surry-County/housing-market) | $276,880 | +6.5% | 73 | 53 | None |

Header, dashboard and footer check dates updated to November 1; mortgage source date updated to October 29. Mortgage-dependent calculators use the new RATE. County data, design, tax/rent/appreciation assumptions and independent scenario defaults remain unchanged. County supply and buyer/seller classifications remain withheld because matched-period evidence has not been established.

Public Netlify check before release showed October 25, rate 7.32% dated October 22. Netlify was listed in connected context but had no callable tools; connector discovery returned no connection candidates. GitHub source and private preview are separate from production. Do not report production updated without a fresh public check.

Local QA: all ten rows and four dashboard charts rendered; all four calculator tabs, market selection, range controls, price/rent edits, negative appreciation, zero price, copy feedback, client-link clipboard, client-mode hiding and agent restoration passed. No runtime page errors. Desktop and 375px mobile inspected; a transient chart width during resize settled to a 375px page without overflow. A source-link click opened Redfin, which redirected the sandbox browser to its rate-limit page; county research was separately verified in the cloud browser.

## Historical verification records

The sections below retain prior weekly observations, not new November data.

## October 25 weekly refresh

Review interval: October 18–25. The [Freddie Mac](https://www.freddiemac.com/pmms) 30-year benchmark is 7.32% dated October 22, versus 7.40% October 15: down 8 basis points. The calculator RATE changed to 7.32. A hypothetical $300,000, 30-year mortgage has monthly principal and interest of $2,060.79 versus $2,077.14, saving $16.35; taxes, insurance, PMI, HOA and fees are excluded.

Finance receipt: `macro_snapshot_mortgage__United_States_d79677.csv`, row `USA3YMR`, latest_value_date `2026-10-22`, latest_value `7.32`, previous_value `7.4`. Metadata: `web/direct-files/9149f6e0d4712a96acaa772e8bf0adef/180e886c-9349-42b8-b3bc-3d2a4ad5c473/csv/882494ba_macro_snapshot_mortgage__United_States_d79677.csv.metadata.json`.

The [NC REALTORS index](https://www.ncrealtors.org/resources/news-data/market-data/) and [September report](https://www.ncrealtors.org/wp-content/uploads/September-2026-Housing-Report.pdf) still show September as latest: median $370,000 (+0.7% YoY), 11,429 sales (-11% YoY), 5.93 months inventory. [Realtor.com/FRED listing DOM](https://fred.stlouisfed.org/series/MEDDAYONMARNC) remains 69 for September versus 66 August, last updated October 1. These are unchanged published figures, not weekly metrics.

All ten county prices, YoY, DOM and sold counts match the October 18 saved values. Avery was verified by fresh fetch; the other nine by rendered Redfin pages after fresh fetch failures. County reporting remains September; no October reporting period was observed. Prices are three-month rolling medians, while sales are the September counts in source narratives. Do not infer an absence of actual weekly market activity from unchanged published data.

| County / source | Median | Price YoY | DOM | September sold | Change vs October 18 snapshot |
|---|---:|---:|---:|---:|---|
| [Forsyth](https://www.redfin.com/county/2040/NC/Forsyth-County/housing-market) | $309,308 | -1.8% | 51 | 378 | None |
| [Guilford](https://www.redfin.com/county/2047/NC/Guilford-County/housing-market) | $304,568 | -1.8% | 40 | 479 | None |
| [Davie](https://www.redfin.com/county/2036/NC/Davie-County/housing-market) | $322,421 | -7.9% | 61 | 63 | None |
| [Rockingham](https://www.redfin.com/county/2085/NC/Rockingham-County/housing-market) | $240,050 | +3.7% | 56 | 97 | None |
| [Wilkes](https://www.redfin.com/county/2103/NC/Wilkes-County/housing-market) | $258,921 | +4.2% | 79 | 33 | None |
| [Watauga](https://www.redfin.com/county/2101/NC/Watauga-County/housing-market) | $583,694 | -6.2% | 97 | 100 | None |
| [Avery](https://www.redfin.com/county/2012/NC/Avery-County/housing-market) | $476,434 | +36.1% | 115 | 56 | None |
| [Ashe](https://www.redfin.com/county/2011/NC/Ashe-County/housing-market) | $498,834 | +17.4% | 88 | 39 | None |
| [Wake](https://www.redfin.com/county/2098/NC/Wake-County/housing-market) | $463,962 | -0.22% | 47 | 1,342 | None |
| [Surry](https://www.redfin.com/county/2092/NC/Surry-County/housing-market) | $276,880 | +6.5% | 73 | 53 | None |

Dates updated in header, dashboard and footer; all mortgage-dependent calculator formulas use the new RATE. County arrays, appreciation/rent/tax assumptions, design and functionality remain unchanged. County supply and market-type classifications remain withheld. The public Netlify site is a separate deployment from the preview and GitHub source.

## Historical verification records

Everything below describes earlier checks and is retained for audit history.

## October 18 weekly refresh

Review interval: October 11–18, 2026. The weekly mortgage benchmark is unchanged; all ten county pages have advanced from the August reporting period stored on October 11 to September. County differences below are report-to-report changes, not seven-day market movements. The actual publication date within the review interval was not established.

[Freddie Mac PMMS](https://www.freddiemac.com/pmms): 7.40% for October 15, versus 7.40% for the previous week, 0 basis points change. Finance provider row `USA3YMR`, latest_value_date `2026-10-15`, latest_value `7.4`, previous_value `7.4`. Receipt `macro_snapshot_mortgage__United_States_d79677.csv`; provenance `web/direct-files/69c0365a5f0575fc8819648a07999392/72462257-e72c-4f76-a03a-b8b86b2dc663/csv/882494ba_macro_snapshot_mortgage__United_States_d79677.csv.metadata.json`. A hypothetical $300,000, 30-year loan still has $2,077.14 monthly principal and interest at this benchmark, excluding tax, insurance, PMI, HOA and fees.

The [NC REALTORS report index](https://www.ncrealtors.org/resources/news-data/market-data/) still lists September as latest. Its [September report](https://www.ncrealtors.org/wp-content/uploads/September-2026-Housing-Report.pdf) is unchanged: $370,000 median (+0.7% YoY), 11,429 sales (-11% YoY), 5.93 months inventory. The [Realtor.com/FRED NC listing DOM](https://fred.stlouisfed.org/series/MEDDAYONMARNC) remains 69 for September versus 66 in August, updated October 1. Neither state metric is a new weekly change.

## County comparison: October 11 saved August values → October 18 September values

Redfin describes prices as the three months ending September 2026. Homes sold are the September counts stated in page narratives. DOM uses the displayed headline number; some pages call it median in cards and average in prose. Do not mix these sales counts with active-listing snapshots to calculate supply. City labels in the tool represent county-wide data.

| County and evidence | Median, August → September | Price YoY, August → September | DOM, August → September | Sold, August → September |
|---|---:|---:|---:|---:|
| [Forsyth](https://www.redfin.com/county/2040/NC/Forsyth-County/housing-market) | $305,000 → $309,308 | -5.6% → -1.8% | 45 → 51 | 419 → 378 |
| [Guilford](https://www.redfin.com/county/2047/NC/Guilford-County/housing-market) | $300,000 → $304,568 | -12.7% → -1.8% | 46 → 40 | 542 → 479 |
| [Davie](https://www.redfin.com/county/2036/NC/Davie-County/housing-market) | $375,475 → $322,421 | +19.2% → -7.9% | 51 → 61 | 54 → 63 |
| [Rockingham](https://www.redfin.com/county/2085/NC/Rockingham-County/housing-market) | $230,000 → $240,050 | -13.8% → +3.7% | 49 → 56 | 85 → 97 |
| [Wilkes](https://www.redfin.com/county/2103/NC/Wilkes-County/housing-market) | $257,000 → $258,921 | -27.3% → +4.2% | 55 → 79 | 38 → 33 |
| [Watauga](https://www.redfin.com/county/2101/NC/Watauga-County/housing-market) | $557,000 → $583,694 | -7.0% → -6.2% | 78 → 97 | 97 → 100 |
| [Avery](https://www.redfin.com/county/2012/NC/Avery-County/housing-market) | $417,500 → $476,434 | -24.2% → +36.1% | 95 → 115 | 51 → 56 |
| [Ashe](https://www.redfin.com/county/2011/NC/Ashe-County/housing-market) | $405,000 → $498,834 | -0.49% → +17.4% | 98 → 88 | 31 → 39 |
| [Wake](https://www.redfin.com/county/2098/NC/Wake-County/housing-market) | $460,000 → $463,962 | -6.1% → -0.22% | 47 → 47 | 1,437 → 1,342 |
| [Surry](https://www.redfin.com/county/2092/NC/Surry-County/housing-market) | $265,000 → $276,880 | -1.9% → +6.5% | 51 → 73 | 47 → 53 |

Fresh fetches verified Forsyth, Guilford, Davie, Rockingham and Surry. Fetch failures for Wilkes, Watauga, Avery, Ashe and Wake were resolved using their rendered browser pages. All current medians are exact published values without smoothing. Large swings in medians/YoY are not individual-property appreciation or recommended price adjustments; their causes were not established.

Calculator rate stays unchanged. Market-linked price defaults update with the county medians. Appreciation, rent, tax and independent scenario defaults are carried forward, not newly verified forecasts. County supply and buyer/seller classifications remain withheld.

QA scope: date/source labels, all ten exact county rows, all four calculator tabs, market selection, negative appreciation and zero purchase price, client-mode script hiding, and desktop/mobile rendering. Public Netlify deployment must be independently checked; GitHub push and preview deployment alone do not establish live production.

## Prior verification history

The following sections preserve older observations, not the October 18 current dataset.

## October 11 weekly refresh

The [Freddie Mac PMMS](https://www.freddiemac.com/pmms) 30-year benchmark is 7.40% dated October 8, versus 7.28% the previous week, an increase of 12 basis points. Finance provider receipt: `macro_snapshot_mortgage__United_States_d79677.csv`, row `USA3YMR`, latest_value 7.4, latest_value_date 2026-10-08, previous_value 7.28. Provenance metadata: `web/direct-files/90f83e88ba6a2d2ba1225a55f5e12dd5/38c57c77-6219-49f0-bc35-285082afc7c3/csv/882494ba_macro_snapshot_mortgage__United_States_d79677.csv.metadata.json`.

The [September NC REALTORS report](https://www.ncrealtors.org/wp-content/uploads/September-2026-Housing-Report.pdf) is now published: median $370,000 (+0.7% YoY), 11,429 sales (-11% YoY), inventory 5.93 months. Against the prior [August report](https://www.ncrealtors.org/wp-content/uploads/August-2026-Housing-Report.pdf), median is $5,000 lower (-1.33%) and inventory is 0.12 months higher. These are monthly changes, not weekly.

[NC median listing DOM](https://fred.stlouisfed.org/series/MEDDAYONMARNC) remains 69 days for September, versus 66 in August. No change to this metric from the October 4 tool.

All ten Redfin county pages still label the median as the three months ending August 2026. They now display different values from the October 4 saved snapshot. Report these as changes to the recorded August figures, not measured October 4–11 market activity; no cause of the differences is established. The source narrative calls homes sold August sales. Browser-rendered pages verified nine counties; a fresh complete page fetch verified Avery. Exact-dollar medians below are published values, not manually rounded or smoothed.

| County | Current median | Change vs Oct 4 display | Current YoY (previous) | DOM (previous) | August sold (previous) |
|---|---:|---:|---:|---:|---:|
| [Forsyth](https://www.redfin.com/county/2040/NC/Forsyth-County/housing-market) | $305,000 | +$21 | -5.6% (-5.7%) | 45 (45) | 419 (436) |
| [Guilford](https://www.redfin.com/county/2047/NC/Guilford-County/housing-market) | $300,000 | -$245 | -12.7% (-12.6%) | 46 (46) | 542 (563) |
| [Davie](https://www.redfin.com/county/2036/NC/Davie-County/housing-market) | $375,475 | +$1,252 | +19.2% (+18.6%) | 51 (51) | 54 (57) |
| [Rockingham](https://www.redfin.com/county/2085/NC/Rockingham-County/housing-market) | $230,000 | +$767 | -13.8% (-13.5%) | 49 (49) | 85 (90) |
| [Wilkes](https://www.redfin.com/county/2103/NC/Wilkes-County/housing-market) | $257,000 | +$857 | -27.3% (-27.5%) | 55 (55) | 38 (40) |
| [Watauga](https://www.redfin.com/county/2101/NC/Watauga-County/housing-market) | $557,000 | -$13,092 | -7.0% (-4.8%) | 78 (81) | 97 (99) |
| [Avery](https://www.redfin.com/county/2012/NC/Avery-County/housing-market) | $417,500 | +$1,393 | -24.2% (-24.5%) | 95 (96) | 51 (54) |
| [Ashe](https://www.redfin.com/county/2011/NC/Ashe-County/housing-market) | $405,000 | +$1,351 | -0.49% (-0.82%) | 98 (99) | 31 (33) |
| [Wake](https://www.redfin.com/county/2098/NC/Wake-County/housing-market) | $460,000 | +$1,534 | -6.1% (-6.4%) | 47 (47) | 1,437 (1,484) |
| [Surry](https://www.redfin.com/county/2092/NC/Surry-County/housing-market) | $265,000 | +$884 | -1.9% (-2.5%) | 51 (51) | 47 (50) |

Monthly principal and interest for a hypothetical $300,000, 30-year loan: $2,077.14 at 7.40% versus $2,052.64 at 7.28%, +$24.50. Calculated using payment = principal × monthly rate / (1 − (1 + monthly rate)^−360), from the [PMMS benchmarks](https://www.freddiemac.com/pmms); excludes taxes, insurance, HOA, PMI and fees. Calculator rate changed; appreciation, rent and tax defaults remain scenario assumptions.

County supply and buyer/seller classifications remain withheld. No mismatched inventory/sales calculations were reintroduced.

## Historical snapshots

The sections below preserve prior checks for comparison; they are not the October 11 current values.

## October 4 weekly refresh

The weekly Freddie Mac 30-year rate is 7.28% for October 1, compared with 7.03% in the previous week, a 25-basis-point increase. Retrieved through the finance provider's USA3YMR series, attributed to [Freddie Mac](https://www.freddiemac.com/pmms). Provider receipt: `macro_snapshot_mortgage__United_States_d79677.csv`, row USA3YMR, latest_value 7.28, latest_value_date 2026-10-01, previous_value 7.03.

North Carolina median listing time advanced to September: 69 days, versus 66 in August. The [Realtor.com series via FRED](https://fred.stlouisfed.org/series/MEDDAYONMARNC) was updated October 1, 2026. This is a monthly listing metric, not a weekly change or county closed-sale DOM.

The [NC REALTORS report index](https://www.ncrealtors.org/resources/news-data/market-data/) still lists August as its latest report. State median and inventory remain $375,000 and 5.81 months, verified against the [August report](https://www.ncrealtors.org/wp-content/uploads/August-2026-Housing-Report.pdf).

All ten county headline datasets below were rechecked on October 4. Published medians, price YoY, DOM, and sales counts match the September 27 verified dataset, with the price reporting window ending August. Older cached versions were rejected: a fresh fetch confirmed Wilkes, and browser-rendered pages confirmed Davie, Avery, Ashe and Surry. Some page titles say “as of September” while the actual headline data still says three months ending August; the data period, not the title, controls the tool's label.

Calculated 30-year principal and interest on a $300,000 loan: $2,052.64 at 7.28%, versus $2,001.96 at 7.03%, an increase of $50.68 per month. Excludes taxes, insurance, HOA, PMI and other costs. Calculator defaults use the new rate; no appreciation, rent or tax defaults were refreshed.

No county supply estimates or buyer/seller classifications were restored. Unchanged monthly data does not mean the market had no activity during the week.

## September 27 verification history

Checked September 27, 2026. The weekly mortgage rate changed; the latest verified county headline reporting period still ends August 2026.

## Weekly benchmark and state data

- Freddie Mac PMMS: 7.03% on September 24, versus 6.95% the prior week and 6.30% a year earlier. Verified from the rendered [Freddie Mac page](https://www.freddiemac.com/pmms) and its fetched content.
- NC REALTORS August report: $375,000 median sale price, +0.2% YoY, 5.81 months of inventory, 11,554 sales, -13.1% sales YoY. These are statewide figures, not county figures. [Official report](https://www.ncrealtors.org/wp-content/uploads/August-2026-Housing-Report.pdf)
- NC median listing days on market: 66 in August, versus 63 in July. This is a listing metric from Realtor.com via FRED, not average closed-sale DOM from NC REALTORS. [FRED series](https://fred.stlouisfed.org/series/MEDDAYONMARNC)
- Independently calculated principal and interest on a $300,000 loan, 30 years: $2,001.96 at 7.03%; $1,985.84 at 6.95%; $1,856.92 at 6.30%. Weekly increase $16.11; year-ago comparison $145.04. Excludes taxes, insurance, HOA, PMI, fees. Rates are the [PMMS benchmarks](https://www.freddiemac.com/pmms), not quotes.

## County evidence

Redfin describes median price as the three months ending August 2026. Days on market and homes-sold values below are the source's headline cards; homes sold is described in page text as August sales. Do not divide current active-listing snapshots by these counts and label the result official monthly supply.

- Forsyth: $304,979 median, -5.7% YoY, 45 DOM, 436 homes sold. [Redfin Forsyth](https://www.redfin.com/county/2040/NC/Forsyth-County/housing-market)
- Guilford: $300,245 median, -12.6% YoY, 46 DOM, 563 homes sold. [Redfin Guilford](https://www.redfin.com/county/2047/NC/Guilford-County/housing-market)
- Davie: $374,223 median, +18.6% YoY, 51 DOM, 57 homes sold. [Redfin Davie](https://www.redfin.com/county/2036/NC/Davie-County/housing-market)
- Rockingham: $229,233 median, -13.5% YoY, 49 DOM, 90 homes sold. [Redfin Rockingham](https://www.redfin.com/county/2085/NC/Rockingham-County/housing-market)
- Wilkes: $256,143 median, -27.5% YoY, 55 DOM, 40 homes sold. [Redfin Wilkes](https://www.redfin.com/county/2103/NC/Wilkes-County/housing-market)
- Watauga: $570,092 median, -4.8% YoY, 81 DOM, 99 homes sold. [Redfin Watauga](https://www.redfin.com/county/2101/NC/Watauga-County/housing-market)
- Avery: $416,107 median, -24.5% YoY, 96 DOM, 54 homes sold. [Redfin Avery](https://www.redfin.com/county/2012/NC/Avery-County/housing-market)
- Ashe: $403,649 median, -0.82% YoY, 99 DOM, 33 homes sold. [Redfin Ashe](https://www.redfin.com/county/2011/NC/Ashe-County/housing-market)
- Wake: $458,466 median, -6.4% YoY, 47 DOM, 1,484 homes sold. [Redfin Wake](https://www.redfin.com/county/2098/NC/Wake-County/housing-market)
- Surry: $264,116 median, -2.5% YoY, 51 DOM, 50 homes sold. [Redfin Surry](https://www.redfin.com/county/2092/NC/Surry-County/housing-market)

Cached pages returned older periods for six counties. Fresh source fetches confirmed Davie and Avery; rendered browser pages confirmed Guilford, Wilkes, Ashe and Surry. Older cached results were not substituted for August data.

## Corrections to the September 20 tool

These are corrections of prior hand-blended display values, not market changes during September 20–27:

| County | Previous displayed median / YoY / DOM | Corrected published median / YoY / DOM |
|---|---|---|
| Davie | $370K / +15.0% / 50 | $374,223 / +18.6% / 51 |
| Rockingham | $245K / -9.0% / 49 | $229,233 / -13.5% / 49 |
| Wilkes | $275K / -8.0% / 50 | $256,143 / -27.5% / 55 |
| Avery | $500K / -10.0% / 85 | $416,107 / -24.5% / 96 |
| Ashe | $420K / +1.0% / 85 | $403,649 / -0.82% / 99 |
| Surry | $270K / +3.0% / 45 | $264,116 / -2.5% / 51 |

Sources for each corrected row are the corresponding county links immediately above. Forsyth, Guilford, Watauga and Wake headline values are unchanged apart from storing exact-dollar medians instead of rounded thousands.

County supply and market-type labels were withdrawn because earlier supply calculations mixed source windows and classifications were inconsistent. No replacement classification is asserted. The former supply chart now displays source-reported sales counts.

The stale NC DOM +23.5% YoY label was removed; the verified comparison is +3 days versus July. The DOM label now says median listing DOM. Positive long-term appreciation defaults remain scenario inputs, not measured current trends or forecasts. Rent and tax defaults were not refreshed.

## QA coverage

- Desktop and mobile dashboard date/rate/source labels and ten rows.
- Four calculators and all five navigation tabs.
- Davie remains in every market dropdown.
- Negative appreciation and zero purchase-price inputs in Appreciation.
- Client mode hides agent scripts.
- Check for runtime errors, non-finite results, and viewport overflow.

## Next-refresh rules

Use published figures without manual smoothing. Preserve the exact reporting period. Do not represent unchanged monthly data as new weekly market activity. Verify matched-period inventory and sales before restoring county supply. Do not translate county median movements into a required percentage price cut for an individual property.

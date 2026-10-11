# Real Estate Math: October 11, 2026 verification

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

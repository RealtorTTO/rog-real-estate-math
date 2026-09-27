# Real Estate Math: September 27, 2026 verification

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

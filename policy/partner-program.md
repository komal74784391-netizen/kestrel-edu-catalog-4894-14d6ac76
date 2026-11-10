# Partner Program Guidelines - FY26-Q3

## 1. Scope

This guideline covers the education reseller partner program for the FY26-Q3
cycle. It applies to all regional list prices published in the education
catalog repository.

## 2. Reference currency

All cross-region sourcing references are reported in HKD.

## 3. Comparison basis

Regional list prices are the published partner prices recorded in
`pricing/regional-list-prices.json`. Convert a local-currency list price to HKD
using the cycle rates in `pricing/fx-rates.json`.

The sourcing reference amount reflects the converted published list price.
Market-specific tax, duty, freight and other landed-cost components are tracked
in separate landed-cost worksheets and are not part of the reference amount.

## 4. Sourcing tiers

- Tier A: reference amount at or below the tier cap published in
  `policy/program-settings.json` (auto-approved for direct PO release).
- Tier B: reference amount above the tier cap (finance review required before
  PO release).

## 5. Catalog card maintenance

Each cycle annotates the catalog cards with a reseller program note. Annotations
are appended at the end of the existing card; the rest of the card is preserved
unchanged.

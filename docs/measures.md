# Measure Inventory

The following measure references were observed in the source PBIX report visual definitions. The descriptions reflect their visual usage, not verified DAX expressions.

| Measure | Observed use |
| --- | --- |
| `CA Dynamique` | Revenue card, monthly revenue, customer ranking and brand analysis |
| `CA P-1 Dynamique` | Previous-period revenue card |
| `CA Année Précédente` | Prior-year series in monthly revenue chart |
| `CA par catégorie` | Revenue by product category chart |
| `Quantité Globale` | Global units sold card |
| `SUM(Fact_Sales[Quantity])` | Units sold card and monthly chart tooltip; visual aggregation rather than a confirmed named measure |

## Validation checklist

- Verify original DAX expressions and date relationship switching.
- Check prior-period versus prior-year definitions; they need not be identical.
- Check the calculation of the growth percentage.
- Verify relationship cardinality and cross-filter direction in the model view.
- Test product-category overlap and slicer interactions.
- Validate partial-month comparisons.
- Recalculate all results on the independently publishable dataset.

No unverified DAX expressions are presented as the original implementation.

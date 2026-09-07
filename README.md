# chart-data

The data behind the charts at [oscarleo.substack.com](https://oscarleo.substack.com).

One folder per chart. Every number is checked by hand against the primary source
before the chart is published; the CSV here is exactly the data the chart renders.

| Chart | Data | Sources |
|---|---|---|
| The butter bubble has burst | [`butter-bubble-burst.csv`](butter-bubble-burst/butter-bubble-burst.csv) | Eurostat, HICP monthly index (prc_hicp_minr, ECOICOP-2), to July 2026 (CP01152, butter and other milk fats) |
| The egg fever moved to Germany | [`egg-fever-migration.csv`](egg-fever-migration/egg-fever-migration.csv) | Eurostat, HICP monthly index (prc_hicp_minr, ECOICOP-2), to July 2026 (CP01148, eggs); US BLS, CPI eggs (CUUR0000SEFH), to July 2026 |
| The 2025 food fevers are over | [`food-fevers-broke.csv`](food-fevers-broke/food-fevers-broke.csv) | Eurostat, HICP monthly index (prc_hicp_minr, ECOICOP-2), to July 2026 (CP01220 coffee, CP01185 chocolate, EU27; CP011513 olive oil, Spain) |
| What six years of food inflation cost, mapped | [`food-inflation-map.csv`](food-inflation-map/food-inflation-map.csv) | Eurostat, HICP monthly index (prc_hicp_minr, ECOICOP-2), food (CP011), to July 2026 (Turkey and Kosovo excluded from the map) |
| Six years of food inflation, country by country | [`food-inflation-table.csv`](food-inflation-table/food-inflation-table.csv) | Eurostat, HICP monthly index (prc_hicp_minr, ECOICOP-2), food (CP011), to July 2026 |
| Frozen fruit is Europe's new food fever | [`frozen-fruit-fever.csv`](frozen-fruit-fever/frozen-fruit-fever.csv) | Eurostat, HICP monthly index (prc_hicp_minr, ECOICOP-2), to July 2026 (CP01166, frozen fruits; available for ~20 countries) |
| Beef is surging in the North | [`northern-beef-surge.csv`](northern-beef-surge/northern-beef-surge.csv) | Eurostat, HICP monthly index (prc_hicp_minr, ECOICOP-2), to July 2026 (CP011221, beef) |
| Swedish groceries are getting cheaper | [`sweden-food-deflation.csv`](sweden-food-deflation/sweden-food-deflation.csv) | Eurostat, HICP monthly index (prc_hicp_minr, ECOICOP-2), to July 2026 (CP011, food) |

Licensing: the underlying data belongs to the cited sources; the compilation is
free to use with attribution to the source and a link to the newsletter.

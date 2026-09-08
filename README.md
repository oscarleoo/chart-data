# chart-data

The data behind the charts at [oscarleo.substack.com](https://oscarleo.substack.com).

One folder per chart. Every number is checked by hand against the primary source
before the chart is published; the CSV here is exactly the data the chart renders.

| Chart | Data | Sources |
|---|---|---|
| The butter bubble has burst | [`butter-bubble-burst.csv`](butter-bubble-burst/butter-bubble-burst.csv) | Eurostat, HICP monthly index (prc_hicp_minr, ECOICOP-2), to July 2026 (CP01152, butter and other milk fats) |
| The North pays the most for its coffee habit | [`coffee-inflation-map.csv`](coffee-inflation-map/coffee-inflation-map.csv) | Eurostat, HICP monthly index (prc_hicp_minr, ECOICOP-2), coffee (CP01220), July 2020 to July 2026 same-month comparison; Norway excluded (item data begins 2026) |
| The egg fever moved to Germany | [`egg-fever-migration.csv`](egg-fever-migration/egg-fever-migration.csv) | Eurostat, HICP monthly index (prc_hicp_minr, ECOICOP-2), to July 2026 (CP01148, eggs); US BLS, CPI eggs (CUUR0000SEFH), to July 2026 |
| What got expensive: six years of EU food inflation by item | [`eu-food-by-item.csv`](eu-food-by-item/eu-food-by-item.csv) | Eurostat, HICP monthly index (prc_hicp_minr, ECOICOP-2), EU27 aggregate, 23 food items, to July 2026 |
| Twenty quiet years, then the fever | [`eu-food-inflation-history.csv`](eu-food-inflation-history/eu-food-inflation-history.csv) | Eurostat, HICP monthly annual rates (prc_hicp_minr, ECOICOP-2), food (CP011), EU27, to July 2026 |
| Every country's fever broke | [`every-countrys-fever-broke.csv`](every-countrys-fever-broke/every-countrys-fever-broke.csv) | Eurostat, HICP monthly annual rates (prc_hicp_minr, ECOICOP-2), food (CP011), EU members, March 2023 and July 2026 |
| A third of the food basket is getting cheaper | [`food-basket-getting-cheaper.csv`](food-basket-getting-cheaper/food-basket-getting-cheaper.csv) | Eurostat, HICP monthly annual rates (prc_hicp_minr, ECOICOP-2), EU aggregate by food category, year to July 2026 |
| What six years of food inflation cost, mapped | [`food-inflation-map.csv`](food-inflation-map/food-inflation-map.csv) | Eurostat, HICP monthly index (prc_hicp_minr, ECOICOP-2), food (CP011), to July 2026 (Turkey and Kosovo excluded from the map) |
| Six years of food inflation, country by country | [`food-inflation-table.csv`](food-inflation-table/food-inflation-table.csv) | Eurostat, HICP monthly index (prc_hicp_minr, ECOICOP-2), food (CP011), to July 2026 |
| Frozen fruit is Europe's new food fever | [`frozen-fruit-fever.csv`](frozen-fruit-fever/frozen-fruit-fever.csv) | Eurostat, HICP monthly index (prc_hicp_minr, ECOICOP-2), to July 2026 (CP01166, frozen fruits; available for ~20 countries) |
| Every country's most-inflated food | [`most-inflated-food-map.csv`](most-inflated-food-map/most-inflated-food-map.csv) | Eurostat, HICP monthly index (prc_hicp_minr, ECOICOP-2), 29 food items, July 2020 to July 2026 (same-month comparison for seasonal fairness) |
| Swedish groceries are getting cheaper | [`sweden-food-deflation.csv`](sweden-food-deflation/sweden-food-deflation.csv) | Eurostat, HICP monthly index (prc_hicp_minr, ECOICOP-2), to July 2026 (CP011, food) |
| Turkey has been here before | [`turkey-second-fever.csv`](turkey-second-fever/turkey-second-fever.csv) | Eurostat, HICP monthly annual rates (prc_hicp_minr, ECOICOP-2), food (CP011), Turkey + EU27, to July 2026 |

Licensing: the underlying data belongs to the cited sources; the compilation is
free to use with attribution to the source and a link to the newsletter.

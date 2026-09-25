# DAMSENTINEL V5
## Asia + Egypt Dam Risk & Flood Emergency Decision-Support Platform

This conference-ready prototype uses a curated set of 30 real dam/barrage facilities across Asia plus Egypt.

### Important data note
This is **not** a complete GDW export. The GDW v1 database contains 41,145 barrier locations and 35,295 associated reservoir polygons. GDW states that its intelligence data can contain missing or uncertain attributes and should be curated and verified before country/basin use.

For V5, the dataset therefore keeps a `data_confidence` field and uses `null` rather than inventing values when a value was not sufficiently established for the prototype.

### Files
- `index.html` — application
- `data/dams.json` — application data
- `data/dams.csv` — spreadsheet-friendly dataset

### Main data sources
- Global Dam Watch: https://www.globaldamwatch.org/database
- Global Dam Watch Intelligence: https://www.globaldamwatch.org/intelligence
- Egypt Ministry of Water Resources and Irrigation — High Dam and Aswan Reservoir: https://www.mwri.gov.eg/mwri2/?lang=en&page_id=33310
- WAPDA — Tarbela Dam: https://wapda.gov.pk/hydro-power-and-water-projects/tarbela-dam/
- China Three Gorges Corporation — Three Gorges project overview: https://tgf.ctg.com.cn/eportal/ui?pageId=720862

### License / attribution
GDW v1 is distributed under a CC BY license. External official/public sources retain their own terms. This prototype should not be presented as an official dam-warning system.

### Safety / scope
DAMSENTINEL is a decision-support and screening prototype. Risk indicators in this version are deliberately not presented as validated probabilities of dam failure. Emergency decisions require validated hydraulic/hydrologic models, current monitoring data, and responsible authorities.

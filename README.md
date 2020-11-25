# gallantry-awards-IN-scaper-2020
Web scraper to extract year of award and service number data about Indian gallantry award recipients, from gallantryawards.gov.in, as of July 2019, for ingestion into Wikidata, using OpenRefine and QuickStatements.

1. [Intial dataset (without award year and service number)](https://github.com/kcvelaga/gallantry-awards-IN-scaper-2020/blob/main/Gallary-Awards-gov2019-India.csv), from https://mix-n-match.toolforge.org/#/catalog/2659.
2. Web scaper to extract award year and service number: [local machine](https://github.com/kcvelaga/gallantry-awards-IN-scaper-2020/blob/main/GA2019%20IN%20Scraper%20(local).ipynb) / [IBM Watson Studio](https://github.com/kcvelaga/gallantry-awards-IN-scaper-2020/blob/main/GA2019%20IN%20Scraper%20(IBMWS).ipynb).
3. [Resultant dataset](https://github.com/kcvelaga/gallantry-awards-IN-scaper-2020/blob/main/GA2019Updated-IN.csv), updated with year of award and service number.
4. [OpenRefine cleanup operations](https://github.com/kcvelaga/gallantry-awards-IN-scaper-2020/blob/main/GA2019%20OpenRefine%20cleanup%20operations.json) for ingestion to Wikidata.
5. Ingestion into Wikidata - [Step 1](https://editgroups.toolforge.org/b/OR/8a56e302a55/), [Step 2](https://editgroups.toolforge.org/b/OR/e33e297e5d1/), [Step 3](https://editgroups.toolforge.org/b/QSv2T/1605863877479/).

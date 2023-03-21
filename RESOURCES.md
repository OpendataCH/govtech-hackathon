Awesome Swiss Data Sources
==========================

This file presents some of the main repositories of data in Switzerland in a brief overview, that we have tailored for participants of the [GovTech Hackathon](https://opendata.ch/events/govtech-hackathon/).
Every source listed on this page has an openly accessible API - which may just require registering for an API key - whose machine-readable endpoint we link to directly.
Earlier versions of this page can be found at [forum.opendata.ch](https://forum.opendata.ch/t/where-to-find-swiss-open-data/20) and [make.opendata.ch](https://make.opendata.ch/wiki/data:ch). Check out [Awesome Open Government Data Switzerland](https://github.com/rnckp/awesome-ogd-switzerland) for a more comprehensive list of Open Government Data (OGD) portals, websites, APIs, tools and other related resources in Switzerland and abroad.

Please open a PR, [write us an issue](issues) or [contact us](info@opendata.ch) with questions, corrections, suggestions 🙇 

# National portals

- [opendata.swiss](http://opendata.swiss) ([API](https://ckan.opendata.swiss/api)) is the main open data portal of the Swiss Federal Government. It has over 8'600 datasets and services from official sources to explore and download, with the [CKAN API](https://docs.ckan.org/en/latest/api/index.html) (see also [Handbook doc](https://handbook.opendata.swiss/de/content/nutzen/api-nutzen.html) in German) for connecting with your [apps](https://opendata.swiss/de/showcase) and [widgets](https://github.com/datalets/ckan-embed).
- [geo.admin.ch](https://www.geo.admin.ch/) the Federal Geoportal with ([API](https://api.geo.admin.ch/services/sdiservices.html)), features live web [maps](https://map.geo.admin.ch) with 854 of geographic overlays (complete [Catalogue](https://www.geo.admin.ch/de/verzeichnis-inspire/) or [List](https://api.geo.admin.ch/api/faq/index.html#which-layers-are-available)),  which can be used via [RESTful services]( https://www.geo.admin.ch/en/portrayal-services/) like WMS WMTS LinkedData, Raw data or RESTful feature API, and diverse endpoints which allow you to extract the data for your applications inkluding [place ZIP search](https://api.geo.admin.ch/services/sdiservices.html#search), [reverse geocoding](https://api.geo.admin.ch/services/sdiservices.html#examples-of-reverse-geocoding) etc. Furthermore there are 21'000 WMS WMTS and rawdatasets from cantons searchable via [GeoHarvester POC](https://davidoesch.github.io/geoservice_harvester_poc/) or  [www.geocat.ch](http://www.geocat.ch)
- [opentransportdata.swiss](https://opentransportdata.swiss) ([API](https://api.opentransportdata.swiss/)) is the customer information platform for Swiss public transport and individual mobility. Visit the [Cookbook](https://opentransportdata.swiss/en/cookbook/verwendung-der-api/) to find out how to use the data in your apps.
 

# Regional portals

In some cases, data from Swiss cantons, municipalities or other geographical regions is being published on opendata.swiss, however some have dedicated portals with extra features or support options:

- [City of Zürich](https://data.stadt-zuerich.ch/) ([API](https://opendatazurich.github.io/))
- [City of Basel](https://data.bs.ch/pages/home/) ([API](https://data.bs.ch/api/v2/console))
- [Canton of Geneva](http://ge.ch/sitg/) ([API](https://geocodage.sitg-lab.ch/api-doc))
- [Canton of Thurgau](https://data.tg.ch/pages/start/) ([API](https://data.tg.ch/api/v2/console))

# Commercial organisations

Here you can find some well supported data sources, which may offer service-level guarantees on their APIs and other features.

- [Wetter API](https://meteotest.ch/wetter-api) ([API](https://mdx.meteotest.ch/api_v1?key=AAAABBBBCCCCDDDDEEEEFFFF00001111&service=prod2data&action=sample_forecast)) from Meteotest is a reliable source of weather, climate, and environmental data.

# Non-profit hubs

These are associations and community projects that offer APIs on a non-commercial, typically limited-support, basis.

- [transport.opendata.ch](https://transport.opendata.ch) ([API](https://transport.opendata.ch/v1/locations?query=Bern)) aims to provide developers with easy programmatic access to public transport data within Switzerland.
 

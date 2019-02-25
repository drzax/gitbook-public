# Data

## Collecting

### Web scraping

To scrape the web, you're going to have to parse the DOM some way.

* If you're dealing with fairly static pages, [Cheerio](https://cheerio.js.org/) is great. It's light-weight and easy to use.
* For more complicated tasks where you either need to interact with the page, or there is dynamic content you need access to, [Puppeteer](https://pptr.dev/) is probably your best bet.
* [Morph.io](https://morph.io/) is a runtime/host for your scrapers which also automatically creates an API for the data.
* [Mercurly Web Parser](https://github.com/postlight/mercury-parser) \(which used to be an API, but is now [open-sourced](https://postlight.com/trackchanges/mercury-goes-open-source)\) is a node app which parses the 'article' text out of a web page.
* For point and click web-scraping, [Import.io](https://www.import.io/) used to be pretty handy, but is now prohibitivly expensive for my usual use cases.

### Databases

* [SQLite](https://sqlite.org/) is consistently useful and probably the simplest relational database to get started with because it doesn't need a server. There are also plenty of well supported language specific packages for working with it like node-sqlite3 for [javascript](https://github.com/mapbox/node-sqlite3) \(or [sqlite](https://www.npmjs.com/package/sqlite) if you like promises\).
* [Google Firebase](https://firebase.google.com/) is a hosted solution that's easy to get started with.
* For hosting, sharing and exploring data sets, [Datasette](https://datasette.readthedocs.io/en/stable/) is well worth a look.
* Graph databases are a thing — give [neo4j](https://neo4j.com/) a go.

### Geolocation

* [Nominatim](https://operations.osmfoundation.org/policies/nominatim/) is a free Open Street Maps based geocoding \(and reverse geocoding\) service with reasonable usage limits for small projects.
* An [IP address based geolocation API](https://ipgeolocation.io/pricing) with a free tier.



## Analysing

There are a million and one tools for analysing data and the right tool depends a lot on the job, and on your own experience.

* [Jupyter](https://jupyter.org/) notebooks are a great tool for analysing data with added analysis and narrative.
* You can author and store Jupyter notebooks in your Google Drive with [Colaboratory](https://colab.research.google.com/).
* Similar to Jupyter notebooks is [Observable](https://beta.observablehq.com/), a javascript based, hosted notebook runtime. It's also open source, so you can [host your own runtime](https://www.npmjs.com/package/@observablehq/runtime).
* [Knime](https://www.knime.com/) is a pretty amazing, if somewhat clunky tool which is great for doing data science type things \(especially [text analytics](https://www.knime.com/knime-text-processing)\) and automating workflows for reproducibility. Just [ask Angus Veitch](https://twitter.com/AngusVeitch/status/1093658731202543616), who did his whole PhD using Knime.

## Visualising

* [d3](https://d3js.org/) is still the leader of the pack for web-based data visualisation. There are also a heap of higher level data visualisation tools and components, many of which use d3 under the hood.
  * [Recharts](http://recharts.org/) and [data-ui](https://williaster.github.io/data-ui/) are collections of React components to build charts with.
* [Vega](https://vega.github.io/vega/) essentialy an effort at a standard data format for describing data visualisations \(a grammar of visualisation\). In theory, it would let you, using a declarative input, create a visualisation on any platform that supported the standard. While the implementation is javascript based, it also has a Python equivalent called [Altair](https://altair-viz.github.io/).


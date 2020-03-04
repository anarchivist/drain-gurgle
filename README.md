# Sounds Collections Database

An attempt to migrate the [RPTF database](https://github.com/RadioPreservationTaskForce/rptf-database) to a static site driven by a JS search engine.

Data is managed as JSON in the \_data directory.

## Building

This repository relies on Jekyll with [pagemaster](https://github.com/mnyrop/pagemaster) and [jekyll-lunr-js-custom-search](https://github.com/dnoneill/jekyll-lunr-js-custom-search/).

Jekyll build commands should be invoked via the `npm` wrapper, as Bootstrap, Popper.js, and JQuery (albeit borked) are vendored: See `npm run` for more details.

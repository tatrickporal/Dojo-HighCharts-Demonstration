MobLab Interview
=============

Your task will be to write a basic dojo app (https://dojotoolkit.org/) in combination with Highcharts. Dojo is a framework that combines many aspects of RequireJS, BackboneJS, AngularJS, along with many other javascript libraries.

---
These will be the dojo requirements:

* Written in Dojo 1.1x (e.g., 1.10 to 1.13 is fine). Do not use Dojo 2.0!
* Build a page with dojo that requests data from https://api.tradingeconomics.com/markets/commodities?c=guest:guest&format=json (hint: use dojo's request package to pull data from APIs and JSON package to parse data).
* Take the requested data and build a page with a graph using high charts. The data shown in the graph should be selectable between daily change, weekly change, monthly change, and yearly change options. As a user, I should be able to select one of the options and have the high charts graph update itself.
* Usage of require syntax is a requirement.
* You can just use the standard dojo/highcharts css and not worry about building your own theme.

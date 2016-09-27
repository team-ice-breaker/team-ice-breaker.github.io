---
layout: page
title: About Project Glacier
---

# Project Synopsis:

The project will be completed by May 18, 2017 and consist of developing Glean and Glance libraries. These libraries will fall under one ‘umbrella’ project called Glacier, that can be utilized by data visualization applications. These libraries will be written in Typescript to handle modeling and data configuration. The model layer and corresponding API is the primary deliverable for the project and will include support for caching data, storing database and other data source credentials, and data sources used in the visualization and formatting for the visualization itself. To support this the client has given us permission to develop supporting libraries and hosting runtimes. These supporting libraries may include, javascript data access libraries, visualization generation libraries, and a javascript frontend library. For an end user this means what we expect to have done would be a javascript-based reference implementation that exercises the model and API provided by Glacier. Development of a complete native GUI is not within the scope of this project however one may be created for testing purposes. It is anticipated that the Glacier library will run in a variety of different Javascript engines with various execution contexts, the deliverable is only required to run and pass tests on a single implementation of the V8 Javascript engine used by Node.js.

# Domain Model:

{% include model.html %}
## sciencesource-wikibase-docker

This repo contains images needed to set up the Wikibase stack for ScienceSource including a query service, using Docker.

Each image contained within this repo has its own README (linked below).

### Issue tracking

For issues relating to the original wikibase-docker stack maintained by WMDE use [Phabricator to track
issues](https://phabricator.wikimedia.org/maniphest/task/edit/form/1/?projects=wikibase-containers). See the [list of current issues](https://phabricator.wikimedia.org/maniphest/?project=wikibase-containers&statuses=open&group=none&order=newest#R).

### Components

Component name               | Description   | README
------------------------ | ------------- | ----------
wikibase | MediaWiki with the Wikibase extension| [README](https://github.com/ContentMine/sciencesource-wikibase-docker/blob/master/wikibase/README.md)
wdqs | Blazegraph SPARQL query service backend | [README](https://github.com/ContentMine/sciencesource-wikibase-docker/blob/master/wdqs/README.md)
wdqs-proxy | Proxy to make the query service READONLY and enforce query timeouts | [README](https://github.com/ContentMine/sciencesource-wikibase-docker/blob/master/wdqs-proxy/README.md)
wdqs-frontend | UI for the SPARQL query service | [README](https://github.com/ContentMine/sciencesource-wikibase-docker/blob/master/wdqs-frontend/README.md)

The stack is intended to be used with ScienceSourceReview UI tool: [README](https://github.com/ContentMine/ScienceSourceReview/blob/master/README.md)



### Docker compose example

This repo contains the docker compose setup for ScienceSource Wikibase.

[README](https://github.com/wmde/wikibase-docker/blob/master/README-compose.md)


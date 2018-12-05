# OAI URI import
[![Build Status](https://travis-ci.org/hirmeos/oai_uri_import.svg?branch=master)](https://travis-ci.org/hirmeos/oai_uri_import)

Query an OAI repository and store found URIs in the identifier translation service

## Run via crontab
```
0 0 * * 1 docker run --rm --name "oai_harvester" --env-file /path/to/config.env openbookpublishers/oai_uri_import
```

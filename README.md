
# Vincenzo Rocks API

This repository describes the Vincenzo Rocks API. The description from the master branch is automatically rendered into [API Documentation](http://docs.vincenzorocks.apiary-staging.tk).

## Overview

### About the format

The API is described in [API Blueprint format](http://apiblueprint.org/), a simple language based on [Markdown](http://daringfireball.net/projects/markdown/syntax). See [the Apiary tutorial](http://apiary.io/blueprint) and [API Blueprint interactive console](http://apiblueprint.org/#examples).

To update the description, go ahead to [apiary.apib](/apiary.apib).

### Editing

Use your favourite editor to edit the blueprint; see [the tooling section](http://apiblueprint.org/#tooling) for available plugins.

[Sublime plugin](https://github.com/apiaryio/api-blueprint-sublime-plugin) is recommended.

### Sychronisation

Documentation is updated whenever you push valid blueprint into the master.


## Developing clients

If you want to develop a client for this API, head [to the documentation](http://docs.vincenzorocks.apiary-staging.tk) to get the address of the mock server (lives on `apiary-mock.com`) generated from this blueprint.


## Developing server

If you want to verify your implementation fulfills the blueprint definition, [use the dredd testing tool](https://github.com/apiaryio/dredd) to plug it into your API.

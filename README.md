# BlaBlaCar Grafonnet-lib plugins

## Content

This repo contains [grafonnet](https://github.com/grafana/grafonnet-lib) plugins we're using at BlaBlaCar.

### Status map panel

Library of [Flant Statusmap](https://grafana.com/grafana/plugins/flant-statusmap-panel) plugin.


## Installation

[grafonnet](https://github.com/grafana/grafonnet-lib) and its dependencies must be installed.

## Usage
Clone this repo in your `$JSONNET_PATH`

```
git clone https://github.com/blablacar/grafonnet-lib-plugins.git
```

 then import the plugin(s) you need in your jsonnet code:

```jsonnet
local statusmap = (import 'grafonnet-lib-plugins/statusmap_panel.libsonnet');
```

## Changelog
Check the [changelog](./CHANGELOG.md) to stay informed on all updates.

## Examples
You can find examples [here](./tests/).

## Contributing
Wanna contribute ? Feel free to submit PR :)

## License
This project is licensed under the terms of the [Apache license](./LICENSE).

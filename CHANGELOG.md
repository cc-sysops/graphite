Graphite  CHANGELOG
===================

This file is used to list changes made in each version of the graphite cookbook.

## 1.0.4
- Syntax and styling updates
- Use full Twisted version number
- Manage graphite nofile ulimit
- Fixes carbon source
- Adds License and Code of Conduct
### Known Issues
- Reordering of Carbon .ini [241](https://github.com/hw-cookbooks/graphite/issues/241)
- Graphite web timeout when restarting [224](https://github.com/hw-cookbooks/graphite/issues/224)

## 1.0.2
- README improvements to address resource usage and removal of Apache
  dependency ([@webframp][], [#187][])
- restart graphite-web in graphite_example sample recipe ([@obazoud][], [#182][])
- remove unused `['graphite']['web_server']` attribute ([@obazoud][], [#181][])

## 1.0.1
- Readme improvements.

## 1.0.0
### Breaking Changes
- Initial release of graphite library style cookbook. Complete rewrite
  of cookbook to provide reusable resources. Breaks backward
  compatibility with cookbook version prior 1.0. ([@webframp][], [@fnichol][],
  [@agoddard][])

<!--- The following link definition list is generated by PimpMyChangelog --->
[#181]: https://github.com/hw-cookbooks/graphite/issues/181
[#182]: https://github.com/hw-cookbooks/graphite/issues/182
[#187]: https://github.com/hw-cookbooks/graphite/issues/187
[@agoddard]: https://github.com/agoddard
[@fnichol]: https://github.com/fnichol
[@obazoud]: https://github.com/obazoud
[@webframp]: https://github.com/webframp
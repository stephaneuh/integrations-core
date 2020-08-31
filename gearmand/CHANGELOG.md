# CHANGELOG - gearmand

## 1.6.0 / 2020-05-17

* [Added] Allow optional dependency installation for all checks. See [#6589](https://github.com/DataDog/integrations-core/pull/6589).

## 1.5.0 / 2020-04-04

* [Added] Collect version metadata. See [#5927](https://github.com/DataDog/integrations-core/pull/5927).
* [Fixed] Update deprecated imports. See [#6088](https://github.com/DataDog/integrations-core/pull/6088).

## 1.4.0 / 2020-01-13

* [Added] Use lazy logging format. See [#5377](https://github.com/DataDog/integrations-core/pull/5377).

## 1.3.1 / 2019-10-11

* [Fixed] Fix misleading gearman.workers metric (#4515). See [#4520](https://github.com/DataDog/integrations-core/pull/4520). Thanks [orgito](https://github.com/orgito).

## 1.3.0 / 2019-05-14

* [Added] Adhere to code style. See [#3508](https://github.com/DataDog/integrations-core/pull/3508).

## 1.2.0 / 2019-01-04

* [Added] Support Python 3. See [#2738][1].

## 1.1.1 / 2018-09-04

* [Fixed] Add data files to the wheel package. See [#1727][2].

## 1.1.0 / 2018-03-23

* [FEATURE] Add custom tag support to service check.

## 1.0.1 / 2017-07-18

* [BUGFIX] Re-use gearman admin connections, fixes connection leak issue. See [#422][3], thanks [@sophaskins][4]

## 1.0.0 / 2017-03-22

* [FEATURE] adds gearmand integration.

<!--- The following link definition list is generated by PimpMyChangelog --->
[1]: https://github.com/DataDog/integrations-core/pull/2738
[2]: https://github.com/DataDog/integrations-core/pull/1727
[3]: https://github.com/DataDog/integrations-core/issues/422
[4]: https://github.com/sophaskins
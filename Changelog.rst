.. _changelog:

Changelog
=========

0.4.4
-----

 * `helpers.bulk_index` renamed to `helpers.bulk` (alias put in place for
   backwards compatibility, to be removed in future versions)
 * Added `helpers.streaming_bulk` to consume an iterator and yield results per
   operation
 * `helpers.bulk` and `helpers.streaming_bulk` are no longer limitted to just
   index operations.

0.4.3
-----

 * Fixes to `helpers.bulk_index`, better error handling
 * More benevolent `hosts` argument parsing for `Elasticsearch`
 * `requests` no longer required (nor recommended) for install

0.4.2
-----
 
 * `ignore` param acceted by all APIs
 * Fixes to `helpers.bulk_index`

0.4.1
-----

Initial release.

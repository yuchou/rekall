---
layout: plugin
title: hivedump
abstract: |
  Prints out a hive

epydoc: rekall.plugins.windows.registry.printkey.HiveDump-class.html
args:
  hive_offsets: 'A list of hive offsets as found by hivelist. If not provided we call hivescan ourselves and list the keys on all hives.'
  hive_regex: 'A regex to filter hive names.If not provided we use all hives.'

---

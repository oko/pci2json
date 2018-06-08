# `pci2json`

Converts [the PCI IDs file](https://pci-ids.ucw.cz/v2.2/pci.ids) from its tab-indented format to JSON. That's it.

## Prerequisites & Install

Requires Python 3.6+ and dependencies from `requirements.txt`:

```
$ pip install -r requirements.txt
```

Simple invocations:

* With downloaded file:
  ```
  $ python3.6 pci2json.py ~/path/to/pci.ids ~/output/file/path.json
  ```

* Straight from curl:
  ```
  $ curl https://pci-ids.ucw.cz/v2.2/pci.ids | python3.6 pci2json.py - ~/output/file/path.json
  ```

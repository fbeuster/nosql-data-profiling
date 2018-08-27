# Schema Extraction and NoSQL Data Profiling
[![MIT License](https://img.shields.io/badge/License-MIT-blue.svg)](https://github.com/fbeuster/nosql-data-profiling/blob/master/LICENSE.md)

This repository contains the paper and test data collections for the master thesis that I wrote in 2018 at the [University of Rostock](https://uni-rostock.de) as part of the [Darwin project](https://www.informatik.uni-rostock.de/en/institut-informatik/staff/homepages/meike-klettke/research/).

The schemata can directly be used in the [JSON Maker](https://json-maker.com) tool to create document collections, and the provided test data can be imported into MongoDB via

```
mongoimport --db master_thesis --collection collectionName --file collectionFile.json --jsonArray
```
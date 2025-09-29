
# CWLGraphList (Schema)

`ogc.cwl.v1_2_1.CWLGraphList` *v1.2.1*

Graph definition that defines *exactly one* CWL application package represented as list. Multiple definitions simultaneously deployed is NOT supported currently.

[*Status*](http://www.opengis.net/def/status): Under development

## Schema

```yaml
description: Graph definition that defines *exactly one* CWL application package represented
  as list. Multiple definitions simultaneously deployed is NOT supported currently.
items:
  $ref: https://ogcincubator.github.io/bblocks-cwl/build/annotated/cwl/v1_2_1/CWLGraphItem/schema.yaml
maxItems: 1
minItems: 1
title: CWLGraphList
type: array

```

Links to the schema:

* YAML version: [schema.yaml](https://ogcincubator.github.io/bblocks-cwl/build/annotated/cwl/v1_2_1/CWLGraphList/schema.json)
* JSON version: [schema.json](https://ogcincubator.github.io/bblocks-cwl/build/annotated/cwl/v1_2_1/CWLGraphList/schema.yaml)


# For developers

The source code for this Building Block can be found in the following repository:

* URL: [https://github.com/ogcincubator/bblocks-cwl](https://github.com/ogcincubator/bblocks-cwl)
* Path: `_sources/v1_2_1/CWLGraphList`


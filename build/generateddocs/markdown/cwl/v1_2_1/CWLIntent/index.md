
# CWLIntent (Schema)

`ogc.cwl.v1_2_1.CWLIntent` *v1.2.1*

CWLIntent

[*Status*](http://www.opengis.net/def/status): Under development

## Schema

```yaml
items:
  description: 'Identifier URL to a concept for the type of computational operation
    accomplished by this process

    (see example operations: http://edamontology.org/operation_0004).

    '
  format: url
  pattern: ^((?:http|ftp)s?://)?(?!.*//.*$)(?:(?:[A-Za-z0-9](?:[A-Za-z0-9-]{0,61}[A-Za-z0-9])?\.)+(?:[A-Za-z]{2,6}\.?|[A-Za-z0-9-]{2,}\.?)|localhost|\[[a-f0-9:]+\]|\d{1,3}\.\d{1,3}\.\d{1,3}\.\d{1,3})(?::\d+)?(?:/?|[/?]\S+)$
  title: item
  type: string
title: CWLIntent
type: array

```

Links to the schema:

* YAML version: [schema.yaml](https://ogcincubator.github.io/bblocks-cwl/build/annotated/cwl/v1_2_1/CWLIntent/schema.json)
* JSON version: [schema.json](https://ogcincubator.github.io/bblocks-cwl/build/annotated/cwl/v1_2_1/CWLIntent/schema.yaml)


# For developers

The source code for this Building Block can be found in the following repository:

* URL: [https://github.com/ogcincubator/bblocks-cwl](https://github.com/ogcincubator/bblocks-cwl)
* Path: `_sources/v1_2_1/CWLIntent`


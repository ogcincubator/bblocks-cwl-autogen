
# CWLIdentifier (Schema)

`ogc.cwl.v1_2_1.CWLIdentifier` *v1.2.1*

Reference to the process identifier.

[*Status*](http://www.opengis.net/def/status): Under development

## Schema

```yaml
anyOf:
- description: Unique identifier.
  format: uuid
  pattern: ^[a-f0-9]{8}(?:-?[a-f0-9]{4}){3}-?[a-f0-9]{12}$
  title: UUID
  type: string
- $ref: https://ogcincubator.github.io/bblocks-cwl/build/annotated/cwl/v1_2_1/CWLTextPatternID/schema.yaml
description: Reference to the process identifier.
title: CWLIdentifier

```

Links to the schema:

* YAML version: [schema.yaml](https://ogcincubator.github.io/bblocks-cwl/build/annotated/cwl/v1_2_1/CWLIdentifier/schema.json)
* JSON version: [schema.json](https://ogcincubator.github.io/bblocks-cwl/build/annotated/cwl/v1_2_1/CWLIdentifier/schema.yaml)


# For developers

The source code for this Building Block can be found in the following repository:

* URL: [https://github.com/ogcincubator/bblocks-cwl](https://github.com/ogcincubator/bblocks-cwl)
* Path: `_sources/v1_2_1/CWLIdentifier`



# CWLTypeEnum (Schema)

`ogc.cwl.v1_2_1.CWLTypeEnum` *v1.2.1*

CWLTypeEnum

[*Status*](http://www.opengis.net/def/status): Under development

## Schema

```yaml
additionalProperties: {}
properties:
  symbols:
    $ref: https://ogcincubator.github.io/bblocks-cwl/build/annotated/cwl/v1_2_1/CWLTypeSymbols/schema.yaml
  type:
    enum:
    - enum
    example: enum
    title: type
    type: string
required:
- type
- symbols
summary: CWL type as enum of values.
title: CWLTypeEnum
type: object

```

Links to the schema:

* YAML version: [schema.yaml](https://ogcincubator.github.io/bblocks-cwl/build/annotated/cwl/v1_2_1/CWLTypeEnum/schema.json)
* JSON version: [schema.json](https://ogcincubator.github.io/bblocks-cwl/build/annotated/cwl/v1_2_1/CWLTypeEnum/schema.yaml)


# For developers

The source code for this Building Block can be found in the following repository:

* URL: [https://github.com/ogcincubator/bblocks-cwl](https://github.com/ogcincubator/bblocks-cwl)
* Path: `_sources/v1_2_1/CWLTypeEnum`


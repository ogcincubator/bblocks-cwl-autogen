
# CWLHintsList (Schema)

`ogc.cwl.v1_2_1.CWLHintsList` *v1.2.1*

CWLHintsList

[*Status*](http://www.opengis.net/def/status): Under development

## Schema

```yaml
items:
  oneOf:
  - allOf:
    - $comment: 'When using the list representation, ''class'' is required to indicate
        which one is being represented.

        When using the mapping representation, ''class'' is optional since it''s the
        key, but it must match by name.

        '
      required:
      - class
    - $ref: https://ogcincubator.github.io/bblocks-cwl/build/annotated/cwl/v1_2_1/CWLHintsItem/schema.yaml
  - $ref: https://ogcincubator.github.io/bblocks-cwl/build/annotated/cwl/v1_2_1/CWLImport/schema.yaml
title: CWLHintsList
type: array

```

Links to the schema:

* YAML version: [schema.yaml](https://ogcincubator.github.io/bblocks-cwl/build/annotated/cwl/v1_2_1/CWLHintsList/schema.json)
* JSON version: [schema.json](https://ogcincubator.github.io/bblocks-cwl/build/annotated/cwl/v1_2_1/CWLHintsList/schema.yaml)


# For developers

The source code for this Building Block can be found in the following repository:

* URL: [https://github.com/ogcincubator/bblocks-cwl](https://github.com/ogcincubator/bblocks-cwl)
* Path: `_sources/v1_2_1/CWLHintsList`


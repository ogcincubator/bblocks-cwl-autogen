
# CWLDirectoryOnlyParametersConditional (Schema)

`ogc.cwl.v1_2_1.CWLDirectoryOnlyParametersConditional` *v1.2.1*

Parameters that are only valid when 'type' or 'items' evaluates to 'Directory'.

[*Status*](http://www.opengis.net/def/status): Under development

## Description

Explicitly disallow these parameters when non-Directory type is detected.
Otherwise, validate their schema definitions according to what is permitted.

## Schema

```yaml
$comment: 'Explicitly disallow these parameters when non-Directory type is detected.

  Otherwise, validate their schema definitions according to what is permitted.

  '
description: Parameters that are only valid when 'type' or 'items' evaluates to 'Directory'.
else:
  not:
    properties:
      loadListing: {}
if:
  oneOf:
  - $comment: Single required or optional 'Directory'.
    properties:
      type:
        enum:
        - Directory
        - Directory?
        - Directory[]
        - Directory[]?
  - $comment: Array of required or optional 'Directory'.
    items:
      oneOf:
      - type: object
        enum:
        - Directory
        - Directory?
      - contains:
          properties:
            type:
              enum:
              - Directory
              - Directory?
        type: array
    type: array
then:
  $ref: https://ogcincubator.github.io/bblocks-cwl/build/annotated/cwl/v1_2_1/CWLDirectoryOnlyParameters/schema.yaml
type: object

```

Links to the schema:

* YAML version: [schema.yaml](https://ogcincubator.github.io/bblocks-cwl/build/annotated/cwl/v1_2_1/CWLDirectoryOnlyParametersConditional/schema.json)
* JSON version: [schema.json](https://ogcincubator.github.io/bblocks-cwl/build/annotated/cwl/v1_2_1/CWLDirectoryOnlyParametersConditional/schema.yaml)


# For developers

The source code for this Building Block can be found in the following repository:

* URL: [https://github.com/ogcincubator/bblocks-cwl](https://github.com/ogcincubator/bblocks-cwl)
* Path: `_sources/v1_2_1/CWLDirectoryOnlyParametersConditional`


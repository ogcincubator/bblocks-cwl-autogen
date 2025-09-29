
# BuiltinRequirement (Schema)

`ogc.cwl.v1_2_1.BuiltinRequirement` *v1.2.1*

Hint indicating that the Application Package corresponds to a
builtin process of this instance. (note: can only be an 'hint'
as it is unofficial CWL specification).


[*Status*](http://www.opengis.net/def/status): Under development

## Schema

```yaml
additionalProperties: false
description: 'Hint indicating that the Application Package corresponds to a

  builtin process of this instance. (note: can only be an ''hint''

  as it is unofficial CWL specification).

  '
properties:
  class:
    enum:
    - BuiltinRequirement
    type: string
  process:
    $comment: Builtin process identifier.
    $ref: https://ogcincubator.github.io/bblocks-cwl/build/annotated/cwl/v1_2_1/CWLTextPatternID/schema.yaml
required:
- process
- class
title: BuiltinRequirement
type: object

```

Links to the schema:

* YAML version: [schema.yaml](https://ogcincubator.github.io/bblocks-cwl/build/annotated/cwl/v1_2_1/BuiltinRequirement/schema.json)
* JSON version: [schema.json](https://ogcincubator.github.io/bblocks-cwl/build/annotated/cwl/v1_2_1/BuiltinRequirement/schema.yaml)


# For developers

The source code for this Building Block can be found in the following repository:

* URL: [https://github.com/ogcincubator/bblocks-cwl](https://github.com/ogcincubator/bblocks-cwl)
* Path: `_sources/v1_2_1/BuiltinRequirement`


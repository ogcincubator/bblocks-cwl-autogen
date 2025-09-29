
# WPS1Requirement (Schema)

`ogc.cwl.v1_2_1.WPS1Requirement` *v1.2.1*

Hint indicating that the Application Package corresponds to a
WPS-1 provider process that should be remotely executed and monitored by this
instance. (note: can only be an ''hint'' as it is unofficial CWL specification).


[*Status*](http://www.opengis.net/def/status): Under development

## Schema

```yaml
additionalProperties: false
description: 'Hint indicating that the Application Package corresponds to a

  WPS-1 provider process that should be remotely executed and monitored by this

  instance. (note: can only be an ''''hint'''' as it is unofficial CWL specification).

  '
properties:
  class:
    enum:
    - WPS1Requirement
    type: string
  process:
    $comment: Process identifier of the remote WPS provider.
    $ref: https://ogcincubator.github.io/bblocks-cwl/build/annotated/cwl/v1_2_1/CWLTextPatternID/schema.yaml
  provider:
    $ref: https://ogcincubator.github.io/bblocks-cwl/build/annotated/cwl/v1_2_1/ReferenceURL/schema.yaml
    description: WPS provider endpoint.
required:
- process
- provider
title: WPS1Requirement
type: object

```

Links to the schema:

* YAML version: [schema.yaml](https://ogcincubator.github.io/bblocks-cwl/build/annotated/cwl/v1_2_1/WPS1Requirement/schema.json)
* JSON version: [schema.json](https://ogcincubator.github.io/bblocks-cwl/build/annotated/cwl/v1_2_1/WPS1Requirement/schema.yaml)


# For developers

The source code for this Building Block can be found in the following repository:

* URL: [https://github.com/ogcincubator/bblocks-cwl](https://github.com/ogcincubator/bblocks-cwl)
* Path: `_sources/v1_2_1/WPS1Requirement`


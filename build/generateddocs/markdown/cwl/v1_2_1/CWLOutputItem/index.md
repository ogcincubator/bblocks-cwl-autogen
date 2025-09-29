
# CWLOutputItem (Schema)

`ogc.cwl.v1_2_1.CWLOutputItem` *v1.2.1*

Output specification. Note that multiple formats are supported
and not all specification variants or parameters are presented here. Please
refer to official CWL documentation for more details (https://www.commonwl.org).


[*Status*](http://www.opengis.net/def/status): Under development

## Schema

```yaml
additionalProperties: {}
description: 'Output specification. Note that multiple formats are supported

  and not all specification variants or parameters are presented here. Please

  refer to official CWL documentation for more details (https://www.commonwl.org).

  '
properties:
  id:
    $ref: https://ogcincubator.github.io/bblocks-cwl/build/annotated/cwl/v1_2_1/CWLIdentifier/schema.yaml
    description: Identifier of the CWL output.
  outputBinding:
    $ref: https://ogcincubator.github.io/bblocks-cwl/build/annotated/cwl/v1_2_1/OutputBinding/schema.yaml
  type:
    oneOf:
    - $ref: https://ogcincubator.github.io/bblocks-cwl/build/annotated/cwl/v1_2_1/CWLType/schema.yaml
    - $ref: https://ogcincubator.github.io/bblocks-cwl/build/annotated/cwl/v1_2_1/CWLOutputStdOut/schema.yaml
    - $ref: https://ogcincubator.github.io/bblocks-cwl/build/annotated/cwl/v1_2_1/CWLOutputStdErr/schema.yaml
required:
- type
- id
title: CWLOutputItem
type: object

```

Links to the schema:

* YAML version: [schema.yaml](https://ogcincubator.github.io/bblocks-cwl/build/annotated/cwl/v1_2_1/CWLOutputItem/schema.json)
* JSON version: [schema.json](https://ogcincubator.github.io/bblocks-cwl/build/annotated/cwl/v1_2_1/CWLOutputItem/schema.yaml)


# For developers

The source code for this Building Block can be found in the following repository:

* URL: [https://github.com/ogcincubator/bblocks-cwl](https://github.com/ogcincubator/bblocks-cwl)
* Path: `_sources/v1_2_1/CWLOutputItem`


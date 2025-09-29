
# InlineJavascriptRequirement (Schema)

`ogc.cwl.v1_2_1.InlineJavascriptRequirement` *v1.2.1*

Indicates that the workflow platform must support inline Javascript expressions.

If this requirement is not present, the workflow platform must not perform expression interpolation
(see also: https://www.commonwl.org/v1.2/CommandLineTool.html#InlineJavascriptRequirement).


[*Status*](http://www.opengis.net/def/status): Under development

## Schema

```yaml
additionalProperties: false
description: 'Indicates that the workflow platform must support inline Javascript
  expressions.


  If this requirement is not present, the workflow platform must not perform expression
  interpolation

  (see also: https://www.commonwl.org/v1.2/CommandLineTool.html#InlineJavascriptRequirement).

  '
properties:
  class:
    enum:
    - InlineJavascriptRequirement
    type: string
  expressionLib:
    $ref: https://ogcincubator.github.io/bblocks-cwl/build/annotated/cwl/v1_2_1/InlineJavascriptLibraries/schema.yaml
required:
- expressionLib
title: InlineJavascriptRequirement
type: object

```

Links to the schema:

* YAML version: [schema.yaml](https://ogcincubator.github.io/bblocks-cwl/build/annotated/cwl/v1_2_1/InlineJavascriptRequirement/schema.json)
* JSON version: [schema.json](https://ogcincubator.github.io/bblocks-cwl/build/annotated/cwl/v1_2_1/InlineJavascriptRequirement/schema.yaml)


# For developers

The source code for this Building Block can be found in the following repository:

* URL: [https://github.com/ogcincubator/bblocks-cwl](https://github.com/ogcincubator/bblocks-cwl)
* Path: `_sources/v1_2_1/InlineJavascriptRequirement`


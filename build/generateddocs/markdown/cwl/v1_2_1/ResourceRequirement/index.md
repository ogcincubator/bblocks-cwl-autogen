
# ResourceRequirement (Schema)

`ogc.cwl.v1_2_1.ResourceRequirement` *v1.2.1*

Specify basic hardware resource requirements
(see also: https://www.commonwl.org/v1.2/CommandLineTool.html#ResourceRequirement).


[*Status*](http://www.opengis.net/def/status): Under development

## Schema

```yaml
additionalProperties: false
description: 'Specify basic hardware resource requirements

  (see also: https://www.commonwl.org/v1.2/CommandLineTool.html#ResourceRequirement).

  '
properties:
  class:
    enum:
    - ResourceRequirement
    type: string
  coresMax:
    $ref: https://ogcincubator.github.io/bblocks-cwl/build/annotated/cwl/v1_2_1/ResourceCoresMaximum/schema.yaml
  coresMin:
    $ref: https://ogcincubator.github.io/bblocks-cwl/build/annotated/cwl/v1_2_1/ResourceCoresMinimum/schema.yaml
  outdirMax:
    $ref: https://ogcincubator.github.io/bblocks-cwl/build/annotated/cwl/v1_2_1/ResourceOutDirMaximum/schema.yaml
  outdirMin:
    $ref: https://ogcincubator.github.io/bblocks-cwl/build/annotated/cwl/v1_2_1/ResourceOutDirMinimum/schema.yaml
  ramMax:
    $ref: https://ogcincubator.github.io/bblocks-cwl/build/annotated/cwl/v1_2_1/ResourceRAMMaximum/schema.yaml
  ramMin:
    $ref: https://ogcincubator.github.io/bblocks-cwl/build/annotated/cwl/v1_2_1/ResourceRAMMinimum/schema.yaml
  tmpdirMax:
    $ref: https://ogcincubator.github.io/bblocks-cwl/build/annotated/cwl/v1_2_1/ResourceTmpDirMaximum/schema.yaml
  tmpdirMin:
    $ref: https://ogcincubator.github.io/bblocks-cwl/build/annotated/cwl/v1_2_1/ResourceTmpDirMinimum/schema.yaml
title: ResourceRequirement
type: object

```

Links to the schema:

* YAML version: [schema.yaml](https://ogcincubator.github.io/bblocks-cwl/build/annotated/cwl/v1_2_1/ResourceRequirement/schema.json)
* JSON version: [schema.json](https://ogcincubator.github.io/bblocks-cwl/build/annotated/cwl/v1_2_1/ResourceRequirement/schema.yaml)


# For developers

The source code for this Building Block can be found in the following repository:

* URL: [https://github.com/ogcincubator/bblocks-cwl](https://github.com/ogcincubator/bblocks-cwl)
* Path: `_sources/v1_2_1/ResourceRequirement`



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
    x-jsonld-id: https://w3id.org/cwl/cwl#ResourceRequirement/coresMax
  coresMin:
    $ref: https://ogcincubator.github.io/bblocks-cwl/build/annotated/cwl/v1_2_1/ResourceCoresMinimum/schema.yaml
    x-jsonld-id: https://w3id.org/cwl/cwl#ResourceRequirement/coresMin
  outdirMax:
    $ref: https://ogcincubator.github.io/bblocks-cwl/build/annotated/cwl/v1_2_1/ResourceOutDirMaximum/schema.yaml
    x-jsonld-id: https://w3id.org/cwl/cwl#ResourceRequirement/outdirMax
  outdirMin:
    $ref: https://ogcincubator.github.io/bblocks-cwl/build/annotated/cwl/v1_2_1/ResourceOutDirMinimum/schema.yaml
    x-jsonld-id: https://w3id.org/cwl/cwl#ResourceRequirement/outdirMin
  ramMax:
    $ref: https://ogcincubator.github.io/bblocks-cwl/build/annotated/cwl/v1_2_1/ResourceRAMMaximum/schema.yaml
    x-jsonld-id: https://w3id.org/cwl/cwl#ResourceRequirement/ramMax
  ramMin:
    $ref: https://ogcincubator.github.io/bblocks-cwl/build/annotated/cwl/v1_2_1/ResourceRAMMinimum/schema.yaml
    x-jsonld-id: https://w3id.org/cwl/cwl#ResourceRequirement/ramMin
  tmpdirMax:
    $ref: https://ogcincubator.github.io/bblocks-cwl/build/annotated/cwl/v1_2_1/ResourceTmpDirMaximum/schema.yaml
    x-jsonld-id: https://w3id.org/cwl/cwl#ResourceRequirement/tmpdirMax
  tmpdirMin:
    $ref: https://ogcincubator.github.io/bblocks-cwl/build/annotated/cwl/v1_2_1/ResourceTmpDirMinimum/schema.yaml
    x-jsonld-id: https://w3id.org/cwl/cwl#ResourceRequirement/tmpdirMin
title: ResourceRequirement
type: object
x-jsonld-prefixes:
  cwl: https://w3id.org/cwl/cwl#

```

Links to the schema:

* YAML version: [schema.yaml](https://ogcincubator.github.io/bblocks-cwl/build/annotated/cwl/v1_2_1/ResourceRequirement/schema.json)
* JSON version: [schema.json](https://ogcincubator.github.io/bblocks-cwl/build/annotated/cwl/v1_2_1/ResourceRequirement/schema.yaml)


# JSON-LD Context

```jsonld
{
  "@context": {
    "coresMax": "cwl:ResourceRequirement/coresMax",
    "coresMin": "cwl:ResourceRequirement/coresMin",
    "outdirMax": "cwl:ResourceRequirement/outdirMax",
    "outdirMin": "cwl:ResourceRequirement/outdirMin",
    "ramMax": "cwl:ResourceRequirement/ramMax",
    "ramMin": "cwl:ResourceRequirement/ramMin",
    "tmpdirMax": "cwl:ResourceRequirement/tmpdirMax",
    "tmpdirMin": "cwl:ResourceRequirement/tmpdirMin",
    "cwl": "https://w3id.org/cwl/cwl#",
    "@version": 1.1
  }
}
```

You can find the full JSON-LD context here:
[context.jsonld](https://ogcincubator.github.io/bblocks-cwl/build/annotated/cwl/v1_2_1/ResourceRequirement/context.jsonld)


# For developers

The source code for this Building Block can be found in the following repository:

* URL: [https://github.com/ogcincubator/bblocks-cwl](https://github.com/ogcincubator/bblocks-cwl)
* Path: `_sources/v1_2_1/ResourceRequirement`


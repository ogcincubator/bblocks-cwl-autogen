
# ResourceOutDirMinimum (Schema)

`ogc.cwl.v1_2_1.ResourceOutDirMinimum` *v1.2.1*

Minimum reserved filesystem based storage for the designated output
directory in mebibytes (2**20).

May be a fractional value. If so, the actual storage request must be rounded
up to the next whole number.

The reported amount of storage reserved for the process, which is available
to expressions on the 'CommandLineTool' as 'runtime.outdirSize', must be a non-zero integer.


[*Status*](http://www.opengis.net/def/status): Under development

## Schema

```yaml
default: 1024
description: 'Minimum reserved filesystem based storage for the designated output

  directory in mebibytes (2**20).


  May be a fractional value. If so, the actual storage request must be rounded

  up to the next whole number.


  The reported amount of storage reserved for the process, which is available

  to expressions on the ''CommandLineTool'' as ''runtime.outdirSize'', must be a non-zero
  integer.

  '
oneOf:
- $ref: https://ogcincubator.github.io/bblocks-cwl/build/annotated/cwl/v1_2_1/ResourceQuantityOrFractional/schema.yaml
- $ref: https://ogcincubator.github.io/bblocks-cwl/build/annotated/cwl/v1_2_1/CWLExpression/schema.yaml
summary: Minimum reserved filesystem based storage for the designated output directory
  in mebibytes.
title: ResourceOutDirMinimum

```

Links to the schema:

* YAML version: [schema.yaml](https://ogcincubator.github.io/bblocks-cwl/build/annotated/cwl/v1_2_1/ResourceOutDirMinimum/schema.json)
* JSON version: [schema.json](https://ogcincubator.github.io/bblocks-cwl/build/annotated/cwl/v1_2_1/ResourceOutDirMinimum/schema.yaml)


# For developers

The source code for this Building Block can be found in the following repository:

* URL: [https://github.com/ogcincubator/bblocks-cwl](https://github.com/ogcincubator/bblocks-cwl)
* Path: `_sources/v1_2_1/ResourceOutDirMinimum`


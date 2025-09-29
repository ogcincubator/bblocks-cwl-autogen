
# ResourceOutDirMaximum (Schema)

`ogc.cwl.v1_2_1.ResourceOutDirMaximum` *v1.2.1*

Maximum reserved filesystem based storage for the designated output
directory in mebibytes (2**20).
See 'outdirMin' for discussion about fractional storage requests.


[*Status*](http://www.opengis.net/def/status): Under development

## Schema

```yaml
default: 1
description: 'Maximum reserved filesystem based storage for the designated output

  directory in mebibytes (2**20).

  See ''outdirMin'' for discussion about fractional storage requests.

  '
oneOf:
- $ref: https://ogcincubator.github.io/bblocks-cwl/build/annotated/cwl/v1_2_1/ResourceQuantityOrFractional/schema.yaml
- $ref: https://ogcincubator.github.io/bblocks-cwl/build/annotated/cwl/v1_2_1/CWLExpression/schema.yaml
summary: Maximum reserved filesystem based storage for the designated output directory
  in mebibytes.
title: ResourceOutDirMaximum

```

Links to the schema:

* YAML version: [schema.yaml](https://ogcincubator.github.io/bblocks-cwl/build/annotated/cwl/v1_2_1/ResourceOutDirMaximum/schema.json)
* JSON version: [schema.json](https://ogcincubator.github.io/bblocks-cwl/build/annotated/cwl/v1_2_1/ResourceOutDirMaximum/schema.yaml)


# For developers

The source code for this Building Block can be found in the following repository:

* URL: [https://github.com/ogcincubator/bblocks-cwl](https://github.com/ogcincubator/bblocks-cwl)
* Path: `_sources/v1_2_1/ResourceOutDirMaximum`


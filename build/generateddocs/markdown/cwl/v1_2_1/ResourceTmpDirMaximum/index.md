
# ResourceTmpDirMaximum (Schema)

`ogc.cwl.v1_2_1.ResourceTmpDirMaximum` *v1.2.1*

Maximum reserved filesystem based storage for the designated temporary directory in mebibytes (2**20).
See 'tmpdirMin' for discussion about fractional storage requests.


[*Status*](http://www.opengis.net/def/status): Under development

## Schema

```yaml
description: 'Maximum reserved filesystem based storage for the designated temporary
  directory in mebibytes (2**20).

  See ''tmpdirMin'' for discussion about fractional storage requests.

  '
oneOf:
- $ref: https://ogcincubator.github.io/bblocks-cwl/build/annotated/cwl/v1_2_1/ResourceQuantityOrFractional/schema.yaml
- $ref: https://ogcincubator.github.io/bblocks-cwl/build/annotated/cwl/v1_2_1/CWLExpression/schema.yaml
summary: Maximum reserved filesystem based storage for the designated temporary directory
  in mebibytes.
title: ResourceTmpDirMaximum

```

Links to the schema:

* YAML version: [schema.yaml](https://ogcincubator.github.io/bblocks-cwl/build/annotated/cwl/v1_2_1/ResourceTmpDirMaximum/schema.json)
* JSON version: [schema.json](https://ogcincubator.github.io/bblocks-cwl/build/annotated/cwl/v1_2_1/ResourceTmpDirMaximum/schema.yaml)


# For developers

The source code for this Building Block can be found in the following repository:

* URL: [https://github.com/ogcincubator/bblocks-cwl](https://github.com/ogcincubator/bblocks-cwl)
* Path: `_sources/v1_2_1/ResourceTmpDirMaximum`


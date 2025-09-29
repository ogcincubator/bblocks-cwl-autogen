
# ResourceRAMMaximum (Schema)

`ogc.cwl.v1_2_1.ResourceRAMMaximum` *v1.2.1*

Maximum reserved RAM in mebibytes (2**20).
See 'ramMin' for discussion about fractional RAM requests.


[*Status*](http://www.opengis.net/def/status): Under development

## Schema

```yaml
description: 'Maximum reserved RAM in mebibytes (2**20).

  See ''ramMin'' for discussion about fractional RAM requests.

  '
oneOf:
- $ref: https://ogcincubator.github.io/bblocks-cwl/build/annotated/cwl/v1_2_1/ResourceQuantityOrFractional/schema.yaml
- $ref: https://ogcincubator.github.io/bblocks-cwl/build/annotated/cwl/v1_2_1/CWLExpression/schema.yaml
summary: Maximum reserved RAM in mebibytes.
title: ResourceRAMMaximum

```

Links to the schema:

* YAML version: [schema.yaml](https://ogcincubator.github.io/bblocks-cwl/build/annotated/cwl/v1_2_1/ResourceRAMMaximum/schema.json)
* JSON version: [schema.json](https://ogcincubator.github.io/bblocks-cwl/build/annotated/cwl/v1_2_1/ResourceRAMMaximum/schema.yaml)


# For developers

The source code for this Building Block can be found in the following repository:

* URL: [https://github.com/ogcincubator/bblocks-cwl](https://github.com/ogcincubator/bblocks-cwl)
* Path: `_sources/v1_2_1/ResourceRAMMaximum`


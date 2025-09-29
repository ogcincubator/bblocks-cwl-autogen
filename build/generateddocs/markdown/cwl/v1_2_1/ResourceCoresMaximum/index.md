
# ResourceCoresMaximum (Schema)

`ogc.cwl.v1_2_1.ResourceCoresMaximum` *v1.2.1*

Maximum reserved number of CPU cores.
See 'coresMin' for discussion about fractional CPU requests.


[*Status*](http://www.opengis.net/def/status): Under development

## Schema

```yaml
description: 'Maximum reserved number of CPU cores.

  See ''coresMin'' for discussion about fractional CPU requests.

  '
oneOf:
- $ref: https://ogcincubator.github.io/bblocks-cwl/build/annotated/cwl/v1_2_1/ResourceQuantityOrFractional/schema.yaml
- $ref: https://ogcincubator.github.io/bblocks-cwl/build/annotated/cwl/v1_2_1/CWLExpression/schema.yaml
summary: Maximum reserved number of CPU cores.
title: ResourceCoresMaximum

```

Links to the schema:

* YAML version: [schema.yaml](https://ogcincubator.github.io/bblocks-cwl/build/annotated/cwl/v1_2_1/ResourceCoresMaximum/schema.json)
* JSON version: [schema.json](https://ogcincubator.github.io/bblocks-cwl/build/annotated/cwl/v1_2_1/ResourceCoresMaximum/schema.yaml)


# For developers

The source code for this Building Block can be found in the following repository:

* URL: [https://github.com/ogcincubator/bblocks-cwl](https://github.com/ogcincubator/bblocks-cwl)
* Path: `_sources/v1_2_1/ResourceCoresMaximum`


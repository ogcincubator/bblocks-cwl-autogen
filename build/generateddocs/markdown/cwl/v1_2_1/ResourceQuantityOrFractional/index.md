
# ResourceQuantityOrFractional (Schema)

`ogc.cwl.v1_2_1.ResourceQuantityOrFractional` *v1.2.1*

An item quantity that can also represent a proportion of use by resources.

[*Status*](http://www.opengis.net/def/status): Under development

## Description

Technically should be minimum=1, but fractional for scheduling algorithms are allowed.
There is no way to distinguish between float/long simultaneously in JSON schema (multi-match oneOf).
Therefore, only validate that it is greater than zero.

## Schema

```yaml
$comment: 'Technically should be minimum=1, but fractional for scheduling algorithms
  are allowed.

  There is no way to distinguish between float/long simultaneously in JSON schema
  (multi-match oneOf).

  Therefore, only validate that it is greater than zero.

  '
default: 1
description: An item quantity that can also represent a proportion of use by resources.
exclusiveMinimum: 0
type: number

```

Links to the schema:

* YAML version: [schema.yaml](https://ogcincubator.github.io/bblocks-cwl/build/annotated/cwl/v1_2_1/ResourceQuantityOrFractional/schema.json)
* JSON version: [schema.json](https://ogcincubator.github.io/bblocks-cwl/build/annotated/cwl/v1_2_1/ResourceQuantityOrFractional/schema.yaml)


# For developers

The source code for this Building Block can be found in the following repository:

* URL: [https://github.com/ogcincubator/bblocks-cwl](https://github.com/ogcincubator/bblocks-cwl)
* Path: `_sources/v1_2_1/ResourceQuantityOrFractional`


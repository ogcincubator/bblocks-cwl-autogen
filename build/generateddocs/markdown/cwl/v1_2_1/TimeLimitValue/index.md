
# TimeLimitValue (Schema)

`ogc.cwl.v1_2_1.TimeLimitValue` *v1.2.1*

The time limit, in seconds.

A time limit of zero means no time limit.
Negative time limits are an error.


[*Status*](http://www.opengis.net/def/status): Under development

## Schema

```yaml
description: 'The time limit, in seconds.


  A time limit of zero means no time limit.

  Negative time limits are an error.

  '
oneOf:
- minimum: 0.0
  type: number
- $ref: https://ogcincubator.github.io/bblocks-cwl/build/annotated/cwl/v1_2_1/CWLExpression/schema.yaml
title: TimeLimitValue

```

Links to the schema:

* YAML version: [schema.yaml](https://ogcincubator.github.io/bblocks-cwl/build/annotated/cwl/v1_2_1/TimeLimitValue/schema.json)
* JSON version: [schema.json](https://ogcincubator.github.io/bblocks-cwl/build/annotated/cwl/v1_2_1/TimeLimitValue/schema.yaml)


# For developers

The source code for this Building Block can be found in the following repository:

* URL: [https://github.com/ogcincubator/bblocks-cwl](https://github.com/ogcincubator/bblocks-cwl)
* Path: `_sources/v1_2_1/TimeLimitValue`


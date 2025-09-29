
# Scatter (Schema)

`ogc.cwl.v1_2_1.Scatter` *v1.2.1*

The scatter field specifies one or more input parameters which will be scattered.

An input parameter may be listed more than once. The declared type of each
input parameter implicitly becomes an array of items of the input parameter type.
If a parameter is listed more than once, it becomes a nested array. As a result,
upstream parameters which are connected to scattered parameters must be arrays.

All output parameter types are also implicitly wrapped in arrays. Each job
in the scatter results in an entry in the output array.

If any scattered parameter runtime value is an empty array, all outputs are
set to empty arrays and no work is done for the step, according to applicable scattering rules.


[*Status*](http://www.opengis.net/def/status): Under development

## Schema

```yaml
description: 'The scatter field specifies one or more input parameters which will
  be scattered.


  An input parameter may be listed more than once. The declared type of each

  input parameter implicitly becomes an array of items of the input parameter type.

  If a parameter is listed more than once, it becomes a nested array. As a result,

  upstream parameters which are connected to scattered parameters must be arrays.


  All output parameter types are also implicitly wrapped in arrays. Each job

  in the scatter results in an entry in the output array.


  If any scattered parameter runtime value is an empty array, all outputs are

  set to empty arrays and no work is done for the step, according to applicable scattering
  rules.

  '
oneOf:
- $ref: https://ogcincubator.github.io/bblocks-cwl/build/annotated/cwl/v1_2_1/CWLTextPatternID/schema.yaml
- $ref: https://ogcincubator.github.io/bblocks-cwl/build/annotated/cwl/v1_2_1/IdentifierArray/schema.yaml
title: Scatter

```

Links to the schema:

* YAML version: [schema.yaml](https://ogcincubator.github.io/bblocks-cwl/build/annotated/cwl/v1_2_1/Scatter/schema.json)
* JSON version: [schema.json](https://ogcincubator.github.io/bblocks-cwl/build/annotated/cwl/v1_2_1/Scatter/schema.yaml)


# For developers

The source code for this Building Block can be found in the following repository:

* URL: [https://github.com/ogcincubator/bblocks-cwl](https://github.com/ogcincubator/bblocks-cwl)
* Path: `_sources/v1_2_1/Scatter`


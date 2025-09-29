
# WorkReuseRequirement (Schema)

`ogc.cwl.v1_2_1.WorkReuseRequirement` *v1.2.1*

For implementations that support reusing output from past work
(on the assumption that same code and same input produce same results),
control whether to enable or disable the reuse behavior for a particular tool
or step (to accommodate situations where that assumption is incorrect).

A reused step is not executed but instead returns the same output as the original execution.

If 'WorkReuse' is not specified, correct tools should assume it is enabled by default.


[*Status*](http://www.opengis.net/def/status): Under development

## Schema

```yaml
additionalProperties: false
description: 'For implementations that support reusing output from past work

  (on the assumption that same code and same input produce same results),

  control whether to enable or disable the reuse behavior for a particular tool

  or step (to accommodate situations where that assumption is incorrect).


  A reused step is not executed but instead returns the same output as the original
  execution.


  If ''WorkReuse'' is not specified, correct tools should assume it is enabled by
  default.

  '
properties:
  class:
    $comment: Not 'WorkReuseRequirement'.
    enum:
    - WorkReuse
    type: string
  enableReuse:
    $ref: https://ogcincubator.github.io/bblocks-cwl/build/annotated/cwl/v1_2_1/EnableReuseValue/schema.yaml
required:
- enableReuse
title: WorkReuseRequirement
type: object

```

Links to the schema:

* YAML version: [schema.yaml](https://ogcincubator.github.io/bblocks-cwl/build/annotated/cwl/v1_2_1/WorkReuseRequirement/schema.json)
* JSON version: [schema.json](https://ogcincubator.github.io/bblocks-cwl/build/annotated/cwl/v1_2_1/WorkReuseRequirement/schema.yaml)


# For developers

The source code for this Building Block can be found in the following repository:

* URL: [https://github.com/ogcincubator/bblocks-cwl](https://github.com/ogcincubator/bblocks-cwl)
* Path: `_sources/v1_2_1/WorkReuseRequirement`


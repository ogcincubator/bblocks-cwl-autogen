
# ToolTimeLimitRequirement (Schema)

`ogc.cwl.v1_2_1.ToolTimeLimitRequirement` *v1.2.1*

Set an upper limit on the execution time of a CommandLineTool.

A CommandLineTool whose execution duration exceeds the time limit may be preemptively
terminated and considered failed. May also be used by batch systems to make scheduling decisions.

The execution duration excludes external operations, such as staging of files,
pulling a docker image etc., and only counts wall-time for the execution of the command line itself.


[*Status*](http://www.opengis.net/def/status): Under development

## Schema

```yaml
additionalProperties: false
description: 'Set an upper limit on the execution time of a CommandLineTool.


  A CommandLineTool whose execution duration exceeds the time limit may be preemptively

  terminated and considered failed. May also be used by batch systems to make scheduling
  decisions.


  The execution duration excludes external operations, such as staging of files,

  pulling a docker image etc., and only counts wall-time for the execution of the
  command line itself.

  '
properties:
  class:
    $comment: not 'ToolTimeLimitRequirement'
    enum:
    - ToolTimeLimit
    type: string
  timelimit:
    $ref: https://ogcincubator.github.io/bblocks-cwl/build/annotated/cwl/v1_2_1/TimeLimitValue/schema.yaml
required:
- timelimit
title: ToolTimeLimitRequirement
type: object

```

Links to the schema:

* YAML version: [schema.yaml](https://ogcincubator.github.io/bblocks-cwl/build/annotated/cwl/v1_2_1/ToolTimeLimitRequirement/schema.json)
* JSON version: [schema.json](https://ogcincubator.github.io/bblocks-cwl/build/annotated/cwl/v1_2_1/ToolTimeLimitRequirement/schema.yaml)


# For developers

The source code for this Building Block can be found in the following repository:

* URL: [https://github.com/ogcincubator/bblocks-cwl](https://github.com/ogcincubator/bblocks-cwl)
* Path: `_sources/v1_2_1/ToolTimeLimitRequirement`


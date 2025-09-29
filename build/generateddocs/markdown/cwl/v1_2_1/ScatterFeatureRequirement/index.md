
# ScatterFeatureRequirement (Schema)

`ogc.cwl.v1_2_1.ScatterFeatureRequirement` *v1.2.1*

A 'scatter' operation specifies that the associated Workflow step should execute separately over a list of
input elements. Each job making up a scatter operation is independent and may be executed concurrently
(see also: https://www.commonwl.org/v1.2/Workflow.html#WorkflowStep).


[*Status*](http://www.opengis.net/def/status): Under development

## Description

Fields 'scatter' and 'scatterMethod' at the root of a 'WorkflowStep', not within the requirement.
## Schema

```yaml
$comment: Fields 'scatter' and 'scatterMethod' at the root of a 'WorkflowStep', not
  within the requirement.
additionalProperties: false
description: 'A ''scatter'' operation specifies that the associated Workflow step
  should execute separately over a list of

  input elements. Each job making up a scatter operation is independent and may be
  executed concurrently

  (see also: https://www.commonwl.org/v1.2/Workflow.html#WorkflowStep).

  '
properties:
  class:
    description: CWL requirement class specification.
    enum:
    - ScatterFeatureRequirement
    type: string
title: ScatterFeatureRequirement
type: object

```

Links to the schema:

* YAML version: [schema.yaml](https://ogcincubator.github.io/bblocks-cwl/build/annotated/cwl/v1_2_1/ScatterFeatureRequirement/schema.json)
* JSON version: [schema.json](https://ogcincubator.github.io/bblocks-cwl/build/annotated/cwl/v1_2_1/ScatterFeatureRequirement/schema.yaml)


# For developers

The source code for this Building Block can be found in the following repository:

* URL: [https://github.com/ogcincubator/bblocks-cwl](https://github.com/ogcincubator/bblocks-cwl)
* Path: `_sources/v1_2_1/ScatterFeatureRequirement`


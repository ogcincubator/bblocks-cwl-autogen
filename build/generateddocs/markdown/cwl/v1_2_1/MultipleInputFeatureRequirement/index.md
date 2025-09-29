
# MultipleInputFeatureRequirement (Schema)

`ogc.cwl.v1_2_1.MultipleInputFeatureRequirement` *v1.2.1*

Indicates that the 'Workflow' must support multiple inbound data links listed in the 'source'
field of 'WorkflowStepInput'.


[*Status*](http://www.opengis.net/def/status): Under development

## Schema

```yaml
additionalProperties: false
description: 'Indicates that the ''Workflow'' must support multiple inbound data links
  listed in the ''source''

  field of ''WorkflowStepInput''.

  '
properties:
  class:
    description: CWL requirement class specification.
    enum:
    - MultipleInputFeatureRequirement
    type: string
title: MultipleInputFeatureRequirement
type: object

```

Links to the schema:

* YAML version: [schema.yaml](https://ogcincubator.github.io/bblocks-cwl/build/annotated/cwl/v1_2_1/MultipleInputFeatureRequirement/schema.json)
* JSON version: [schema.json](https://ogcincubator.github.io/bblocks-cwl/build/annotated/cwl/v1_2_1/MultipleInputFeatureRequirement/schema.yaml)


# For developers

The source code for this Building Block can be found in the following repository:

* URL: [https://github.com/ogcincubator/bblocks-cwl](https://github.com/ogcincubator/bblocks-cwl)
* Path: `_sources/v1_2_1/MultipleInputFeatureRequirement`


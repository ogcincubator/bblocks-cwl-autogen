
# UnknownRequirement (Schema)

`ogc.cwl.v1_2_1.UnknownRequirement` *v1.2.1*

Generic schema to allow alternative CWL requirements/hints not explicitly defined in schemas.

[*Status*](http://www.opengis.net/def/status): Under development

## Schema

```yaml
additionalProperties: {}
description: Generic schema to allow alternative CWL requirements/hints not explicitly
  defined in schemas.
properties:
  class:
    description: CWL requirement class specification.
    example: UnknownRequirement
    not:
      enum:
      - cwltool:CUDARequirement
      - DockerRequirement
      - SoftwareRequirement
      - ShellCommandRequirement
      - EnvVarRequirement
      - SchemaDefRequirement
      - InitialWorkDirRequirement
      - InlineJavascriptRequirement
      - InplaceUpdateRequirement
      - LoadListingRequirement
      - NetworkAccess
      - ResourceRequirement
      - ScatterFeatureRequirement
      - ToolTimeLimit
      - WorkReuse
      - MultipleInputFeatureRequirement
      - StepInputExpressionRequirement
      - SubworkflowFeatureRequirement
    title: Requirement Class Identifier
    type: string
type: object

```

Links to the schema:

* YAML version: [schema.yaml](https://ogcincubator.github.io/bblocks-cwl/build/annotated/cwl/v1_2_1/UnknownRequirement/schema.json)
* JSON version: [schema.json](https://ogcincubator.github.io/bblocks-cwl/build/annotated/cwl/v1_2_1/UnknownRequirement/schema.yaml)


# For developers

The source code for this Building Block can be found in the following repository:

* URL: [https://github.com/ogcincubator/bblocks-cwl](https://github.com/ogcincubator/bblocks-cwl)
* Path: `_sources/v1_2_1/UnknownRequirement`


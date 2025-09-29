
# CWLRequirementsMap (Schema)

`ogc.cwl.v1_2_1.CWLRequirementsMap` *v1.2.1*

CWLRequirementsMap

[*Status*](http://www.opengis.net/def/status): Under development

## Schema

```yaml
additionalProperties: false
properties:
  DockerRequirement:
    $ref: https://ogcincubator.github.io/bblocks-cwl/build/annotated/cwl/v1_2_1/DockerRequirement/schema.yaml
  EnvVarRequirement:
    $ref: https://ogcincubator.github.io/bblocks-cwl/build/annotated/cwl/v1_2_1/EnvVarRequirement/schema.yaml
  InitialWorkDirRequirement:
    $ref: https://ogcincubator.github.io/bblocks-cwl/build/annotated/cwl/v1_2_1/InitialWorkDirRequirement/schema.yaml
  InlineJavascriptRequirement:
    $ref: https://ogcincubator.github.io/bblocks-cwl/build/annotated/cwl/v1_2_1/InlineJavascriptRequirement/schema.yaml
  InplaceUpdateRequirement:
    $ref: https://ogcincubator.github.io/bblocks-cwl/build/annotated/cwl/v1_2_1/InplaceUpdateRequirement/schema.yaml
  LoadListingRequirement:
    $ref: https://ogcincubator.github.io/bblocks-cwl/build/annotated/cwl/v1_2_1/LoadListingRequirement/schema.yaml
  MultipleInputFeatureRequirement:
    $ref: https://ogcincubator.github.io/bblocks-cwl/build/annotated/cwl/v1_2_1/MultipleInputFeatureRequirement/schema.yaml
  NetworkAccess:
    $comment: Not 'NetworkAccessRequirement'
    $ref: https://ogcincubator.github.io/bblocks-cwl/build/annotated/cwl/v1_2_1/NetworkAccessRequirement/schema.yaml
  ResourceRequirement:
    $ref: https://ogcincubator.github.io/bblocks-cwl/build/annotated/cwl/v1_2_1/ResourceRequirement/schema.yaml
  ScatterFeatureRequirement:
    $ref: https://ogcincubator.github.io/bblocks-cwl/build/annotated/cwl/v1_2_1/ScatterFeatureRequirement/schema.yaml
  SchemaDefRequirement:
    $ref: https://ogcincubator.github.io/bblocks-cwl/build/annotated/cwl/v1_2_1/SchemaDefRequirement/schema.yaml
  ShellCommandRequirement:
    $ref: https://ogcincubator.github.io/bblocks-cwl/build/annotated/cwl/v1_2_1/ShellCommandRequirement/schema.yaml
  SoftwareRequirement:
    $ref: https://ogcincubator.github.io/bblocks-cwl/build/annotated/cwl/v1_2_1/SoftwareRequirement/schema.yaml
  StepInputExpressionRequirement:
    $ref: https://ogcincubator.github.io/bblocks-cwl/build/annotated/cwl/v1_2_1/StepInputExpressionRequirement/schema.yaml
  SubworkflowFeatureRequirement:
    $ref: https://ogcincubator.github.io/bblocks-cwl/build/annotated/cwl/v1_2_1/SubworkflowFeatureRequirement/schema.yaml
  ToolTimeLimit:
    $comment: Not 'ToolTimeLimitRequirement'.
    $ref: https://ogcincubator.github.io/bblocks-cwl/build/annotated/cwl/v1_2_1/ToolTimeLimitRequirement/schema.yaml
  WorkReuse:
    $comment: Not 'WorkReuseRequirement'.
    $ref: https://ogcincubator.github.io/bblocks-cwl/build/annotated/cwl/v1_2_1/WorkReuseRequirement/schema.yaml
  cwltool:CUDARequirement:
    $ref: https://ogcincubator.github.io/bblocks-cwl/build/annotated/cwl/v1_2_1/cwltool:CUDARequirement/schema.yaml
title: CWLRequirementsMap
type: object

```

Links to the schema:

* YAML version: [schema.yaml](https://ogcincubator.github.io/bblocks-cwl/build/annotated/cwl/v1_2_1/CWLRequirementsMap/schema.json)
* JSON version: [schema.json](https://ogcincubator.github.io/bblocks-cwl/build/annotated/cwl/v1_2_1/CWLRequirementsMap/schema.yaml)


# For developers

The source code for this Building Block can be found in the following repository:

* URL: [https://github.com/ogcincubator/bblocks-cwl](https://github.com/ogcincubator/bblocks-cwl)
* Path: `_sources/v1_2_1/CWLRequirementsMap`


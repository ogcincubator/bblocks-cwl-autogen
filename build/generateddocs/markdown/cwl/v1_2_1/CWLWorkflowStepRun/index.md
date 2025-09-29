
# CWLWorkflowStepRun (Schema)

`ogc.cwl.v1_2_1.CWLWorkflowStepRun` *v1.2.1*

Nested CWL definition to run as Workflow step.

[*Status*](http://www.opengis.net/def/status): Under development

## Schema

```yaml
description: Nested CWL definition to run as Workflow step.
oneOf:
- description: File or URL reference to a CWL tool definition.
  type: string
- $ref: https://ogcincubator.github.io/bblocks-cwl/build/annotated/cwl/v1_2_1/CWLAtomicNested/schema.yaml
  description: Nested CWL tool definition for the step.
- $ref: https://ogcincubator.github.io/bblocks-cwl/build/annotated/cwl/v1_2_1/CWLWorkflowNested/schema.yaml
  description: Nested CWL Workflow definition for the step.

```

Links to the schema:

* YAML version: [schema.yaml](https://ogcincubator.github.io/bblocks-cwl/build/annotated/cwl/v1_2_1/CWLWorkflowStepRun/schema.json)
* JSON version: [schema.json](https://ogcincubator.github.io/bblocks-cwl/build/annotated/cwl/v1_2_1/CWLWorkflowStepRun/schema.yaml)


# For developers

The source code for this Building Block can be found in the following repository:

* URL: [https://github.com/ogcincubator/bblocks-cwl](https://github.com/ogcincubator/bblocks-cwl)
* Path: `_sources/v1_2_1/CWLWorkflowStepRun`



# CWLWorkflowStepInputBase (Schema)

`ogc.cwl.v1_2_1.CWLWorkflowStepInputBase` *v1.2.1*

CWLWorkflowStepInputBase

[*Status*](http://www.opengis.net/def/status): Under development

## Schema

```yaml
properties:
  linkMerge:
    $ref: https://ogcincubator.github.io/bblocks-cwl/build/annotated/cwl/v1_2_1/LinkMergeMethod/schema.yaml
  source:
    oneOf:
    - type: string
    - items:
        type: string
      type: array
  valueFrom:
    $ref: https://ogcincubator.github.io/bblocks-cwl/build/annotated/cwl/v1_2_1/CWLExpression/schema.yaml
type: object

```

Links to the schema:

* YAML version: [schema.yaml](https://ogcincubator.github.io/bblocks-cwl/build/annotated/cwl/v1_2_1/CWLWorkflowStepInputBase/schema.json)
* JSON version: [schema.json](https://ogcincubator.github.io/bblocks-cwl/build/annotated/cwl/v1_2_1/CWLWorkflowStepInputBase/schema.yaml)


# For developers

The source code for this Building Block can be found in the following repository:

* URL: [https://github.com/ogcincubator/bblocks-cwl](https://github.com/ogcincubator/bblocks-cwl)
* Path: `_sources/v1_2_1/CWLWorkflowStepInputBase`


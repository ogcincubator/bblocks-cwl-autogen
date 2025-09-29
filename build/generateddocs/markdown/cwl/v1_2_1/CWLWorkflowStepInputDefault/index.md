
# CWLWorkflowStepInputDefault (Schema)

`ogc.cwl.v1_2_1.CWLWorkflowStepInputDefault` *v1.2.1*

CWLWorkflowStepInputDefault

[*Status*](http://www.opengis.net/def/status): Under development

## Description

CWL 'type' is not specified at this level for step inputs
(it is provided by the mapped input of the nested tool instead).
Therefore, cannot validate against 'CWLDefaultTypedConditional'.

## Schema

```yaml
$comment: 'CWL ''type'' is not specified at this level for step inputs

  (it is provided by the mapped input of the nested tool instead).

  Therefore, cannot validate against ''CWLDefaultTypedConditional''.

  '
properties:
  default:
    $ref: https://ogcincubator.github.io/bblocks-cwl/build/annotated/cwl/v1_2_1/CWLDefault/schema.yaml
type: object

```

Links to the schema:

* YAML version: [schema.yaml](https://ogcincubator.github.io/bblocks-cwl/build/annotated/cwl/v1_2_1/CWLWorkflowStepInputDefault/schema.json)
* JSON version: [schema.json](https://ogcincubator.github.io/bblocks-cwl/build/annotated/cwl/v1_2_1/CWLWorkflowStepInputDefault/schema.yaml)


# JSON-LD Context

```jsonld
{
  "@context": {
    "basename": "cwl:basename",
    "nameroot": "cwl:File/nameroot",
    "cwl": "https://w3id.org/cwl/cwl#",
    "@version": 1.1
  }
}
```

You can find the full JSON-LD context here:
[context.jsonld](https://ogcincubator.github.io/bblocks-cwl/build/annotated/cwl/v1_2_1/CWLWorkflowStepInputDefault/context.jsonld)


# For developers

The source code for this Building Block can be found in the following repository:

* URL: [https://github.com/ogcincubator/bblocks-cwl](https://github.com/ogcincubator/bblocks-cwl)
* Path: `_sources/v1_2_1/CWLWorkflowStepInputDefault`


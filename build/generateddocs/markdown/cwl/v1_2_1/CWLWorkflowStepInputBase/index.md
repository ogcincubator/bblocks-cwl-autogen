
# CWLWorkflowStepInputBase (Schema)

`ogc.cwl.v1_2_1.CWLWorkflowStepInputBase` *v1.2.1*

CWLWorkflowStepInputBase

[*Status*](http://www.opengis.net/def/status): Under development

## Schema

```yaml
properties:
  linkMerge:
    $ref: https://ogcincubator.github.io/bblocks-cwl/build/annotated/cwl/v1_2_1/LinkMergeMethod/schema.yaml
    x-jsonld-id: https://w3id.org/cwl/cwl#linkMerge
  source:
    oneOf:
    - type: string
    - items:
        type: string
      type: array
  valueFrom:
    $ref: https://ogcincubator.github.io/bblocks-cwl/build/annotated/cwl/v1_2_1/CWLExpression/schema.yaml
    x-jsonld-id: https://w3id.org/cwl/cwl#valueFrom
type: object
x-jsonld-prefixes:
  cwl: https://w3id.org/cwl/cwl#

```

Links to the schema:

* YAML version: [schema.yaml](https://ogcincubator.github.io/bblocks-cwl/build/annotated/cwl/v1_2_1/CWLWorkflowStepInputBase/schema.json)
* JSON version: [schema.json](https://ogcincubator.github.io/bblocks-cwl/build/annotated/cwl/v1_2_1/CWLWorkflowStepInputBase/schema.yaml)


# JSON-LD Context

```jsonld
{
  "@context": {
    "linkMerge": "cwl:linkMerge",
    "valueFrom": "cwl:valueFrom",
    "cwl": "https://w3id.org/cwl/cwl#",
    "@version": 1.1
  }
}
```

You can find the full JSON-LD context here:
[context.jsonld](https://ogcincubator.github.io/bblocks-cwl/build/annotated/cwl/v1_2_1/CWLWorkflowStepInputBase/context.jsonld)


# For developers

The source code for this Building Block can be found in the following repository:

* URL: [https://github.com/ogcincubator/bblocks-cwl](https://github.com/ogcincubator/bblocks-cwl)
* Path: `_sources/v1_2_1/CWLWorkflowStepInputBase`


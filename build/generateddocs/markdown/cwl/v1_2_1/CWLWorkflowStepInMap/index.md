
# CWLWorkflowStepInMap (Schema)

`ogc.cwl.v1_2_1.CWLWorkflowStepInMap` *v1.2.1*

CWLWorkflowStepInMap

[*Status*](http://www.opengis.net/def/status): Under development

## Schema

```yaml
additionalProperties:
  oneOf:
  - type: string
  - items:
      type: string
    type: array
  - $ref: https://ogcincubator.github.io/bblocks-cwl/build/annotated/cwl/v1_2_1/CWLWorkflowStepInput/schema.yaml
type: object

```

Links to the schema:

* YAML version: [schema.yaml](https://ogcincubator.github.io/bblocks-cwl/build/annotated/cwl/v1_2_1/CWLWorkflowStepInMap/schema.json)
* JSON version: [schema.json](https://ogcincubator.github.io/bblocks-cwl/build/annotated/cwl/v1_2_1/CWLWorkflowStepInMap/schema.yaml)


# JSON-LD Context

```jsonld
{
  "@context": {
    "linkMerge": "cwl:linkMerge",
    "valueFrom": "cwl:valueFrom",
    "basename": "cwl:basename",
    "nameroot": "cwl:File/nameroot",
    "cwl": "https://w3id.org/cwl/cwl#",
    "@version": 1.1
  }
}
```

You can find the full JSON-LD context here:
[context.jsonld](https://ogcincubator.github.io/bblocks-cwl/build/annotated/cwl/v1_2_1/CWLWorkflowStepInMap/context.jsonld)


# For developers

The source code for this Building Block can be found in the following repository:

* URL: [https://github.com/ogcincubator/bblocks-cwl](https://github.com/ogcincubator/bblocks-cwl)
* Path: `_sources/v1_2_1/CWLWorkflowStepInMap`


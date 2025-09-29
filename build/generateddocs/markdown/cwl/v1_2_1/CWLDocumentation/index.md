
# CWLDocumentation (Schema)

`ogc.cwl.v1_2_1.CWLDocumentation` *v1.2.1*

CWLDocumentation

[*Status*](http://www.opengis.net/def/status): Under development

## Schema

```yaml
properties:
  doc:
    oneOf:
    - type: string
    - items:
        type: string
      type: array
  label:
    type: string
    x-jsonld-id: http://www.w3.org/2000/01/rdf-schema#label
type: object
x-jsonld-prefixes:
  cwl: https://w3id.org/cwl/cwl#

```

Links to the schema:

* YAML version: [schema.yaml](https://ogcincubator.github.io/bblocks-cwl/build/annotated/cwl/v1_2_1/CWLDocumentation/schema.json)
* JSON version: [schema.json](https://ogcincubator.github.io/bblocks-cwl/build/annotated/cwl/v1_2_1/CWLDocumentation/schema.yaml)


# JSON-LD Context

```jsonld
{
  "@context": {
    "label": "http://www.w3.org/2000/01/rdf-schema#label",
    "cwl": "https://w3id.org/cwl/cwl#",
    "@version": 1.1
  }
}
```

You can find the full JSON-LD context here:
[context.jsonld](https://ogcincubator.github.io/bblocks-cwl/build/annotated/cwl/v1_2_1/CWLDocumentation/context.jsonld)


# For developers

The source code for this Building Block can be found in the following repository:

* URL: [https://github.com/ogcincubator/bblocks-cwl](https://github.com/ogcincubator/bblocks-cwl)
* Path: `_sources/v1_2_1/CWLDocumentation`


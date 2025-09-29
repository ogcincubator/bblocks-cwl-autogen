
# CWLDefaultLocation (Schema)

`ogc.cwl.v1_2_1.CWLDefaultLocation` *v1.2.1*

CWLDefaultLocation

[*Status*](http://www.opengis.net/def/status): Under development

## Schema

```yaml
additionalProperties: false
oneOf:
- required:
  - path
- required:
  - location
properties:
  basename:
    type: string
    x-jsonld-id: https://w3id.org/cwl/cwl#basename
  class:
    enum:
    - File
    - Directory
    type: string
  location:
    type: string
  nameroot:
    type: string
    x-jsonld-id: https://w3id.org/cwl/cwl#File/nameroot
  path:
    type: string
required:
- class
type: object
x-jsonld-prefixes:
  cwl: https://w3id.org/cwl/cwl#

```

Links to the schema:

* YAML version: [schema.yaml](https://ogcincubator.github.io/bblocks-cwl/build/annotated/cwl/v1_2_1/CWLDefaultLocation/schema.json)
* JSON version: [schema.json](https://ogcincubator.github.io/bblocks-cwl/build/annotated/cwl/v1_2_1/CWLDefaultLocation/schema.yaml)


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
[context.jsonld](https://ogcincubator.github.io/bblocks-cwl/build/annotated/cwl/v1_2_1/CWLDefaultLocation/context.jsonld)


# For developers

The source code for this Building Block can be found in the following repository:

* URL: [https://github.com/ogcincubator/bblocks-cwl](https://github.com/ogcincubator/bblocks-cwl)
* Path: `_sources/v1_2_1/CWLDefaultLocation`


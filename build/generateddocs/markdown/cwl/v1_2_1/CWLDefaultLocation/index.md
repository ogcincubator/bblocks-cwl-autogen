
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
  class:
    enum:
    - File
    - Directory
    type: string
  location:
    type: string
  nameroot:
    type: string
  path:
    type: string
required:
- class
type: object

```

Links to the schema:

* YAML version: [schema.yaml](https://ogcincubator.github.io/bblocks-cwl/build/annotated/cwl/v1_2_1/CWLDefaultLocation/schema.json)
* JSON version: [schema.json](https://ogcincubator.github.io/bblocks-cwl/build/annotated/cwl/v1_2_1/CWLDefaultLocation/schema.yaml)


# For developers

The source code for this Building Block can be found in the following repository:

* URL: [https://github.com/ogcincubator/bblocks-cwl](https://github.com/ogcincubator/bblocks-cwl)
* Path: `_sources/v1_2_1/CWLDefaultLocation`


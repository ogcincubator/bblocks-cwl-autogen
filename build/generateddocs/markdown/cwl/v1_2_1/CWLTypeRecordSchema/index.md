
# CWLTypeRecordSchema (Schema)

`ogc.cwl.v1_2_1.CWLTypeRecordSchema` *v1.2.1*

CWLTypeRecordSchema

[*Status*](http://www.opengis.net/def/status): Under development

## Schema

```yaml
properties:
  fields:
    $ref: https://ogcincubator.github.io/bblocks-cwl/build/annotated/cwl/v1_2_1/CWLTypeRecordFields/schema.yaml
  name:
    type: string
  type:
    enum:
    - record
    type: string
required:
- type
type: object

```

Links to the schema:

* YAML version: [schema.yaml](https://ogcincubator.github.io/bblocks-cwl/build/annotated/cwl/v1_2_1/CWLTypeRecordSchema/schema.json)
* JSON version: [schema.json](https://ogcincubator.github.io/bblocks-cwl/build/annotated/cwl/v1_2_1/CWLTypeRecordSchema/schema.yaml)


# For developers

The source code for this Building Block can be found in the following repository:

* URL: [https://github.com/ogcincubator/bblocks-cwl](https://github.com/ogcincubator/bblocks-cwl)
* Path: `_sources/v1_2_1/CWLTypeRecordSchema`


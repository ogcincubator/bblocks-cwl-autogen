
# CWLMetadata (Schema)

`ogc.cwl.v1_2_1.CWLMetadata` *v1.2.1*

CWLMetadata

[*Status*](http://www.opengis.net/def/status): Under development

## Schema

```yaml
properties:
  s:keywords:
    $ref: https://ogcincubator.github.io/bblocks-cwl/build/annotated/cwl/v1_2_1/CWLKeywordList/schema.yaml
  version:
    description: Version of the process.
    example: 1.2.3
    pattern: ^\d+(\.\d+(\.\d+(\.[A-Za-z0-9\-_]+)*)*)*$
    title: version
    type: string
type: object

```

Links to the schema:

* YAML version: [schema.yaml](https://ogcincubator.github.io/bblocks-cwl/build/annotated/cwl/v1_2_1/CWLMetadata/schema.json)
* JSON version: [schema.json](https://ogcincubator.github.io/bblocks-cwl/build/annotated/cwl/v1_2_1/CWLMetadata/schema.yaml)


# For developers

The source code for this Building Block can be found in the following repository:

* URL: [https://github.com/ogcincubator/bblocks-cwl](https://github.com/ogcincubator/bblocks-cwl)
* Path: `_sources/v1_2_1/CWLMetadata`



# CWLVersion (Schema)

`ogc.cwl.v1_2_1.CWLVersion` *v1.2.1*

CWLVersion

[*Status*](http://www.opengis.net/def/status): Under development

## Schema

```yaml
properties:
  clwVersion:
    description: CWL version of the described application package.
    pattern: ^v\d+(\.\d+(\.\d+)*)*$
    title: cwlVersion
    type: string
required:
- cwlVersion
type: object

```

Links to the schema:

* YAML version: [schema.yaml](https://ogcincubator.github.io/bblocks-cwl/build/annotated/cwl/v1_2_1/CWLVersion/schema.json)
* JSON version: [schema.json](https://ogcincubator.github.io/bblocks-cwl/build/annotated/cwl/v1_2_1/CWLVersion/schema.yaml)


# For developers

The source code for this Building Block can be found in the following repository:

* URL: [https://github.com/ogcincubator/bblocks-cwl](https://github.com/ogcincubator/bblocks-cwl)
* Path: `_sources/v1_2_1/CWLVersion`


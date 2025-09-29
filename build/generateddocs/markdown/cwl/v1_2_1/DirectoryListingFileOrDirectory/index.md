
# DirectoryListingFileOrDirectory (Schema)

`ogc.cwl.v1_2_1.DirectoryListingFileOrDirectory` *v1.2.1*

DirectoryListingFileOrDirectory

[*Status*](http://www.opengis.net/def/status): Under development

## Schema

```yaml
additionalProperties: false
properties:
  checksum:
    $ref: https://ogcincubator.github.io/bblocks-cwl/build/annotated/cwl/v1_2_1/Checksum/schema.yaml
  class:
    enum:
    - File
    - Directory
    type: string
  location:
    type: string
  size:
    minimum: 0
    type: integer
required:
- class
- location
type: object

```

Links to the schema:

* YAML version: [schema.yaml](https://ogcincubator.github.io/bblocks-cwl/build/annotated/cwl/v1_2_1/DirectoryListingFileOrDirectory/schema.json)
* JSON version: [schema.json](https://ogcincubator.github.io/bblocks-cwl/build/annotated/cwl/v1_2_1/DirectoryListingFileOrDirectory/schema.yaml)


# For developers

The source code for this Building Block can be found in the following repository:

* URL: [https://github.com/ogcincubator/bblocks-cwl](https://github.com/ogcincubator/bblocks-cwl)
* Path: `_sources/v1_2_1/DirectoryListingFileOrDirectory`


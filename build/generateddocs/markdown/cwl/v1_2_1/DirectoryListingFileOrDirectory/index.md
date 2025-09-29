
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
    x-jsonld-id: https://w3id.org/cwl/cwl#File/checksum
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
    x-jsonld-id: https://w3id.org/cwl/cwl#File/size
required:
- class
- location
type: object
x-jsonld-prefixes:
  cwl: https://w3id.org/cwl/cwl#

```

Links to the schema:

* YAML version: [schema.yaml](https://ogcincubator.github.io/bblocks-cwl/build/annotated/cwl/v1_2_1/DirectoryListingFileOrDirectory/schema.json)
* JSON version: [schema.json](https://ogcincubator.github.io/bblocks-cwl/build/annotated/cwl/v1_2_1/DirectoryListingFileOrDirectory/schema.yaml)


# JSON-LD Context

```jsonld
{
  "@context": {
    "checksum": "cwl:File/checksum",
    "size": "cwl:File/size",
    "cwl": "https://w3id.org/cwl/cwl#",
    "@version": 1.1
  }
}
```

You can find the full JSON-LD context here:
[context.jsonld](https://ogcincubator.github.io/bblocks-cwl/build/annotated/cwl/v1_2_1/DirectoryListingFileOrDirectory/context.jsonld)


# For developers

The source code for this Building Block can be found in the following repository:

* URL: [https://github.com/ogcincubator/bblocks-cwl](https://github.com/ogcincubator/bblocks-cwl)
* Path: `_sources/v1_2_1/DirectoryListingFileOrDirectory`


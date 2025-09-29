
# DirectoryListingDirent (Schema)

`ogc.cwl.v1_2_1.DirectoryListingDirent` *v1.2.1*

DirectoryListingDirent

[*Status*](http://www.opengis.net/def/status): Under development

## Description

Called 'Dirent' in documentation.
## Schema

```yaml
$comment: Called 'Dirent' in documentation.
additionalProperties: false
properties:
  entry:
    $ref: https://ogcincubator.github.io/bblocks-cwl/build/annotated/cwl/v1_2_1/CWLExpression/schema.yaml
  entryname:
    $ref: https://ogcincubator.github.io/bblocks-cwl/build/annotated/cwl/v1_2_1/CWLExpression/schema.yaml
  writable:
    type: boolean
    x-jsonld-id: https://w3id.org/cwl/cwl#Dirent/writable
required:
- entry
title: DirectoryListingDirent
type: object
x-jsonld-prefixes:
  cwl: https://w3id.org/cwl/cwl#

```

Links to the schema:

* YAML version: [schema.yaml](https://ogcincubator.github.io/bblocks-cwl/build/annotated/cwl/v1_2_1/DirectoryListingDirent/schema.json)
* JSON version: [schema.json](https://ogcincubator.github.io/bblocks-cwl/build/annotated/cwl/v1_2_1/DirectoryListingDirent/schema.yaml)


# JSON-LD Context

```jsonld
{
  "@context": {
    "writable": "cwl:Dirent/writable",
    "cwl": "https://w3id.org/cwl/cwl#",
    "@version": 1.1
  }
}
```

You can find the full JSON-LD context here:
[context.jsonld](https://ogcincubator.github.io/bblocks-cwl/build/annotated/cwl/v1_2_1/DirectoryListingDirent/context.jsonld)


# For developers

The source code for this Building Block can be found in the following repository:

* URL: [https://github.com/ogcincubator/bblocks-cwl](https://github.com/ogcincubator/bblocks-cwl)
* Path: `_sources/v1_2_1/DirectoryListingDirent`


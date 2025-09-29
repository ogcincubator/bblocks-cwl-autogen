
# SoftwarePackage (Schema)

`ogc.cwl.v1_2_1.SoftwarePackage` *v1.2.1*

SoftwarePackage

[*Status*](http://www.opengis.net/def/status): Under development

## Schema

```yaml
additionalProperties: false
properties:
  package:
    type: string
    x-jsonld-id: https://w3id.org/cwl/cwl#SoftwarePackage/package
  specs:
    items:
      $ref: https://ogcincubator.github.io/bblocks-cwl/build/annotated/cwl/v1_2_1/ReferenceURL/schema.yaml
    type: array
  version:
    items:
      type: string
    type: array
    x-jsonld-id: https://w3id.org/cwl/cwl#SoftwarePackage/version
required:
- package
type: object
x-jsonld-prefixes:
  cwl: https://w3id.org/cwl/cwl#

```

Links to the schema:

* YAML version: [schema.yaml](https://ogcincubator.github.io/bblocks-cwl/build/annotated/cwl/v1_2_1/SoftwarePackage/schema.json)
* JSON version: [schema.json](https://ogcincubator.github.io/bblocks-cwl/build/annotated/cwl/v1_2_1/SoftwarePackage/schema.yaml)


# JSON-LD Context

```jsonld
{
  "@context": {
    "package": "cwl:SoftwarePackage/package",
    "version": "cwl:SoftwarePackage/version",
    "cwl": "https://w3id.org/cwl/cwl#",
    "@version": 1.1
  }
}
```

You can find the full JSON-LD context here:
[context.jsonld](https://ogcincubator.github.io/bblocks-cwl/build/annotated/cwl/v1_2_1/SoftwarePackage/context.jsonld)


# For developers

The source code for this Building Block can be found in the following repository:

* URL: [https://github.com/ogcincubator/bblocks-cwl](https://github.com/ogcincubator/bblocks-cwl)
* Path: `_sources/v1_2_1/SoftwarePackage`


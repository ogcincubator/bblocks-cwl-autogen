
# SoftwareRequirement (Schema)

`ogc.cwl.v1_2_1.SoftwareRequirement` *v1.2.1*

SoftwareRequirement

[*Status*](http://www.opengis.net/def/status): Under development

## Schema

```yaml
additionalProperties: false
properties:
  class:
    enum:
    - SoftwareRequirement
    type: string
  packages:
    oneOf:
    - items:
        $ref: https://ogcincubator.github.io/bblocks-cwl/build/annotated/cwl/v1_2_1/SoftwarePackage/schema.yaml
      type: array
    - additionalProperties:
        oneOf:
        - $ref: https://ogcincubator.github.io/bblocks-cwl/build/annotated/cwl/v1_2_1/SoftwarePackageSpecs/schema.yaml
        - $ref: https://ogcincubator.github.io/bblocks-cwl/build/annotated/cwl/v1_2_1/SoftwarePackage/schema.yaml
      description: Mapping of 'package' name to its specifications.
      type: object
required:
- packages
type: object

```

Links to the schema:

* YAML version: [schema.yaml](https://ogcincubator.github.io/bblocks-cwl/build/annotated/cwl/v1_2_1/SoftwareRequirement/schema.json)
* JSON version: [schema.json](https://ogcincubator.github.io/bblocks-cwl/build/annotated/cwl/v1_2_1/SoftwareRequirement/schema.yaml)


# For developers

The source code for this Building Block can be found in the following repository:

* URL: [https://github.com/ogcincubator/bblocks-cwl](https://github.com/ogcincubator/bblocks-cwl)
* Path: `_sources/v1_2_1/SoftwareRequirement`


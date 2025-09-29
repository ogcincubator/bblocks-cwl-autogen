
# DockerRequirement (Schema)

`ogc.cwl.v1_2_1.DockerRequirement` *v1.2.1*

DockerRequirement

[*Status*](http://www.opengis.net/def/status): Under development

## Schema

```yaml
additionalProperties: false
oneOf:
- required:
  - dockerPull
- required:
  - dockerImport
- required:
  - dockerLoad
- required:
  - dockerFile
properties:
  class:
    enum:
    - DockerRequirement
    type: string
  dockerFile:
    type: string
  dockerImageId:
    type: string
  dockerImport:
    type: string
  dockerLoad:
    type: string
  dockerOutputDirectory:
    type: string
  dockerPull:
    description: Reference package that will be retrieved and executed by CWL.
    example: docker-registry.host.com/namespace/image:1.2.3
    title: Docker pull reference
    type: string
title: DockerRequirement
type: object

```

Links to the schema:

* YAML version: [schema.yaml](https://ogcincubator.github.io/bblocks-cwl/build/annotated/cwl/v1_2_1/DockerRequirement/schema.json)
* JSON version: [schema.json](https://ogcincubator.github.io/bblocks-cwl/build/annotated/cwl/v1_2_1/DockerRequirement/schema.yaml)


# For developers

The source code for this Building Block can be found in the following repository:

* URL: [https://github.com/ogcincubator/bblocks-cwl](https://github.com/ogcincubator/bblocks-cwl)
* Path: `_sources/v1_2_1/DockerRequirement`


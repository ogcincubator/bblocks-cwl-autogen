
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
    x-jsonld-id: https://w3id.org/cwl/cwl#DockerRequirement/dockerFile
  dockerImageId:
    type: string
    x-jsonld-id: https://w3id.org/cwl/cwl#DockerRequirement/dockerImageId
  dockerImport:
    type: string
    x-jsonld-id: https://w3id.org/cwl/cwl#DockerRequirement/dockerImport
  dockerLoad:
    type: string
    x-jsonld-id: https://w3id.org/cwl/cwl#DockerRequirement/dockerLoad
  dockerOutputDirectory:
    type: string
    x-jsonld-id: https://w3id.org/cwl/cwl#DockerRequirement/dockerOutputDirectory
  dockerPull:
    description: Reference package that will be retrieved and executed by CWL.
    example: docker-registry.host.com/namespace/image:1.2.3
    title: Docker pull reference
    type: string
    x-jsonld-id: https://w3id.org/cwl/cwl#DockerRequirement/dockerPull
title: DockerRequirement
type: object
x-jsonld-prefixes:
  cwl: https://w3id.org/cwl/cwl#

```

Links to the schema:

* YAML version: [schema.yaml](https://ogcincubator.github.io/bblocks-cwl/build/annotated/cwl/v1_2_1/DockerRequirement/schema.json)
* JSON version: [schema.json](https://ogcincubator.github.io/bblocks-cwl/build/annotated/cwl/v1_2_1/DockerRequirement/schema.yaml)


# JSON-LD Context

```jsonld
{
  "@context": {
    "dockerFile": "cwl:DockerRequirement/dockerFile",
    "dockerImageId": "cwl:DockerRequirement/dockerImageId",
    "dockerImport": "cwl:DockerRequirement/dockerImport",
    "dockerLoad": "cwl:DockerRequirement/dockerLoad",
    "dockerOutputDirectory": "cwl:DockerRequirement/dockerOutputDirectory",
    "dockerPull": "cwl:DockerRequirement/dockerPull",
    "cwl": "https://w3id.org/cwl/cwl#",
    "@version": 1.1
  }
}
```

You can find the full JSON-LD context here:
[context.jsonld](https://ogcincubator.github.io/bblocks-cwl/build/annotated/cwl/v1_2_1/DockerRequirement/context.jsonld)


# For developers

The source code for this Building Block can be found in the following repository:

* URL: [https://github.com/ogcincubator/bblocks-cwl](https://github.com/ogcincubator/bblocks-cwl)
* Path: `_sources/v1_2_1/DockerRequirement`


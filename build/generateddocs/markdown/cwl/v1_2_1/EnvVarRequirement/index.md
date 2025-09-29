
# EnvVarRequirement (Schema)

`ogc.cwl.v1_2_1.EnvVarRequirement` *v1.2.1*

EnvVarRequirement

[*Status*](http://www.opengis.net/def/status): Under development

## Schema

```yaml
additionalProperties: false
properties:
  class:
    enum:
    - EnvVarRequirement
    type: string
  envDef:
    oneOf:
    - items:
        $ref: https://ogcincubator.github.io/bblocks-cwl/build/annotated/cwl/v1_2_1/EnvironmentDef/schema.yaml
      type: array
    - additionalProperties:
        oneOf:
        - $ref: https://ogcincubator.github.io/bblocks-cwl/build/annotated/cwl/v1_2_1/CWLExpression/schema.yaml
          description: The 'envValue' specified directly
        - $ref: https://ogcincubator.github.io/bblocks-cwl/build/annotated/cwl/v1_2_1/EnvironmentDef/schema.yaml
      description: Mapping of 'envName' to environment value or definition.
      type: object
required:
- envDef
type: object

```

Links to the schema:

* YAML version: [schema.yaml](https://ogcincubator.github.io/bblocks-cwl/build/annotated/cwl/v1_2_1/EnvVarRequirement/schema.json)
* JSON version: [schema.json](https://ogcincubator.github.io/bblocks-cwl/build/annotated/cwl/v1_2_1/EnvVarRequirement/schema.yaml)


# JSON-LD Context

```jsonld
{
  "@context": {
    "envName": "cwl:EnvironmentDef/envName",
    "envValue": "cwl:EnvironmentDef/envValue",
    "cwl": "https://w3id.org/cwl/cwl#",
    "@version": 1.1
  }
}
```

You can find the full JSON-LD context here:
[context.jsonld](https://ogcincubator.github.io/bblocks-cwl/build/annotated/cwl/v1_2_1/EnvVarRequirement/context.jsonld)


# For developers

The source code for this Building Block can be found in the following repository:

* URL: [https://github.com/ogcincubator/bblocks-cwl](https://github.com/ogcincubator/bblocks-cwl)
* Path: `_sources/v1_2_1/EnvVarRequirement`


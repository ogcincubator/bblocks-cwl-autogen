
# OutputBinding (Schema)

`ogc.cwl.v1_2_1.OutputBinding` *v1.2.1*

Defines how to retrieve the output result from the command.

[*Status*](http://www.opengis.net/def/status): Under development

## Schema

```yaml
additionalProperties: {}
description: Defines how to retrieve the output result from the command.
properties:
  glob:
    description: Glob pattern to find the output on disk or mounted docker volume.
    oneOf:
    - $ref: https://ogcincubator.github.io/bblocks-cwl/build/annotated/cwl/v1_2_1/CWLExpression/schema.yaml
    - items:
        $ref: https://ogcincubator.github.io/bblocks-cwl/build/annotated/cwl/v1_2_1/CWLExpression/schema.yaml
      type: array
title: OutputBinding
type: object

```

Links to the schema:

* YAML version: [schema.yaml](https://ogcincubator.github.io/bblocks-cwl/build/annotated/cwl/v1_2_1/OutputBinding/schema.json)
* JSON version: [schema.json](https://ogcincubator.github.io/bblocks-cwl/build/annotated/cwl/v1_2_1/OutputBinding/schema.yaml)


# For developers

The source code for this Building Block can be found in the following repository:

* URL: [https://github.com/ogcincubator/bblocks-cwl](https://github.com/ogcincubator/bblocks-cwl)
* Path: `_sources/v1_2_1/OutputBinding`


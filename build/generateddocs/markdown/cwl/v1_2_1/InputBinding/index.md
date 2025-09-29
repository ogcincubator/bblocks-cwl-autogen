
# InputBinding (Schema)

`ogc.cwl.v1_2_1.InputBinding` *v1.2.1*

Defines how to specify the input for the command.

[*Status*](http://www.opengis.net/def/status): Under development

## Schema

```yaml
additionalProperties: false
description: Defines how to specify the input for the command.
properties:
  itemSeparator:
    type: string
    x-jsonld-id: https://w3id.org/cwl/cwl#CommandLineBinding/itemSeparator
  position:
    oneOf:
    - type: integer
    - $ref: https://ogcincubator.github.io/bblocks-cwl/build/annotated/cwl/v1_2_1/CWLExpression/schema.yaml
    x-jsonld-id: https://w3id.org/cwl/cwl#CommandLineBinding/position
  prefix:
    type: string
    x-jsonld-id: https://w3id.org/cwl/cwl#CommandLineBinding/prefix
  shellQuote:
    type: boolean
    x-jsonld-id: https://w3id.org/cwl/cwl#CommandLineBinding/shellQuote
  valueFrom:
    $ref: https://ogcincubator.github.io/bblocks-cwl/build/annotated/cwl/v1_2_1/CWLExpression/schema.yaml
    x-jsonld-id: https://w3id.org/cwl/cwl#valueFrom
title: Input Binding
type: object
x-jsonld-prefixes:
  cwl: https://w3id.org/cwl/cwl#

```

Links to the schema:

* YAML version: [schema.yaml](https://ogcincubator.github.io/bblocks-cwl/build/annotated/cwl/v1_2_1/InputBinding/schema.json)
* JSON version: [schema.json](https://ogcincubator.github.io/bblocks-cwl/build/annotated/cwl/v1_2_1/InputBinding/schema.yaml)


# JSON-LD Context

```jsonld
{
  "@context": {
    "itemSeparator": "cwl:CommandLineBinding/itemSeparator",
    "position": "cwl:CommandLineBinding/position",
    "prefix": "cwl:CommandLineBinding/prefix",
    "shellQuote": "cwl:CommandLineBinding/shellQuote",
    "valueFrom": "cwl:valueFrom",
    "cwl": "https://w3id.org/cwl/cwl#",
    "@version": 1.1
  }
}
```

You can find the full JSON-LD context here:
[context.jsonld](https://ogcincubator.github.io/bblocks-cwl/build/annotated/cwl/v1_2_1/InputBinding/context.jsonld)


# For developers

The source code for this Building Block can be found in the following repository:

* URL: [https://github.com/ogcincubator/bblocks-cwl](https://github.com/ogcincubator/bblocks-cwl)
* Path: `_sources/v1_2_1/InputBinding`



# LoadListingRequirement (Schema)

`ogc.cwl.v1_2_1.LoadListingRequirement` *v1.2.1*

Specify the desired behavior for loading the listing field of a 'Directory' object for use by expressions
(see also: https://www.commonwl.org/v1.2/CommandLineTool.html#LoadListingRequirement).


[*Status*](http://www.opengis.net/def/status): Under development

## Schema

```yaml
additionalProperties: false
description: 'Specify the desired behavior for loading the listing field of a ''Directory''
  object for use by expressions

  (see also: https://www.commonwl.org/v1.2/CommandLineTool.html#LoadListingRequirement).

  '
properties:
  class:
    enum:
    - LoadListingRequirement
    type: string
  loadListing:
    $ref: https://ogcincubator.github.io/bblocks-cwl/build/annotated/cwl/v1_2_1/LoadListingEnum/schema.yaml
    x-jsonld-id: https://w3id.org/cwl/cwl#loadListing
required:
- loadListing
title: LoadListingRequirement
type: object
x-jsonld-prefixes:
  cwl: https://w3id.org/cwl/cwl#

```

Links to the schema:

* YAML version: [schema.yaml](https://ogcincubator.github.io/bblocks-cwl/build/annotated/cwl/v1_2_1/LoadListingRequirement/schema.json)
* JSON version: [schema.json](https://ogcincubator.github.io/bblocks-cwl/build/annotated/cwl/v1_2_1/LoadListingRequirement/schema.yaml)


# JSON-LD Context

```jsonld
{
  "@context": {
    "loadListing": "cwl:loadListing",
    "cwl": "https://w3id.org/cwl/cwl#",
    "@version": 1.1
  }
}
```

You can find the full JSON-LD context here:
[context.jsonld](https://ogcincubator.github.io/bblocks-cwl/build/annotated/cwl/v1_2_1/LoadListingRequirement/context.jsonld)


# For developers

The source code for this Building Block can be found in the following repository:

* URL: [https://github.com/ogcincubator/bblocks-cwl](https://github.com/ogcincubator/bblocks-cwl)
* Path: `_sources/v1_2_1/LoadListingRequirement`


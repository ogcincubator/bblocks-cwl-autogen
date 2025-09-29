
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
required:
- loadListing
title: LoadListingRequirement
type: object

```

Links to the schema:

* YAML version: [schema.yaml](https://ogcincubator.github.io/bblocks-cwl/build/annotated/cwl/v1_2_1/LoadListingRequirement/schema.json)
* JSON version: [schema.json](https://ogcincubator.github.io/bblocks-cwl/build/annotated/cwl/v1_2_1/LoadListingRequirement/schema.yaml)


# For developers

The source code for this Building Block can be found in the following repository:

* URL: [https://github.com/ogcincubator/bblocks-cwl](https://github.com/ogcincubator/bblocks-cwl)
* Path: `_sources/v1_2_1/LoadListingRequirement`


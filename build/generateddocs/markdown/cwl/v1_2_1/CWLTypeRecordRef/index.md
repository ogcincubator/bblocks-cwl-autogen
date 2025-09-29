
# CWLTypeRecordRef (Schema)

`ogc.cwl.v1_2_1.CWLTypeRecordRef` *v1.2.1*

An IRI with minimally a '{Record}' identifier to look for a schema definition locally or remotely.

The identifier resolution is performed accordingly to the specified reference and as described in
https://www.commonwl.org/v1.2/SchemaSalad.html#Identifier_resolution.


[*Status*](http://www.opengis.net/def/status): Under development

## Description

Avoid 'oneOf' conflict of valid strings between this CWL record reference and the generic CWL types.
## Schema

```yaml
$comment: Avoid 'oneOf' conflict of valid strings between this CWL record reference
  and the generic CWL types.
allOf:
- not:
    $ref: https://ogcincubator.github.io/bblocks-cwl/build/annotated/cwl/v1_2_1/CWLTypeDefinition/schema.yaml
- not:
    $ref: https://ogcincubator.github.io/bblocks-cwl/build/annotated/cwl/v1_2_1/CWLInputStdInDefinition/schema.yaml
- not:
    $ref: https://ogcincubator.github.io/bblocks-cwl/build/annotated/cwl/v1_2_1/CWLOutputStdOutDefinition/schema.yaml
- not:
    $ref: https://ogcincubator.github.io/bblocks-cwl/build/annotated/cwl/v1_2_1/CWLOutputStdErrDefinition/schema.yaml
- $ref: https://ogcincubator.github.io/bblocks-cwl/build/annotated/cwl/v1_2_1/CWLTypeRecordRefPattern/schema.yaml
description: 'An IRI with minimally a ''{Record}'' identifier to look for a schema
  definition locally or remotely.


  The identifier resolution is performed accordingly to the specified reference and
  as described in

  https://www.commonwl.org/v1.2/SchemaSalad.html#Identifier_resolution.

  '

```

Links to the schema:

* YAML version: [schema.yaml](https://ogcincubator.github.io/bblocks-cwl/build/annotated/cwl/v1_2_1/CWLTypeRecordRef/schema.json)
* JSON version: [schema.json](https://ogcincubator.github.io/bblocks-cwl/build/annotated/cwl/v1_2_1/CWLTypeRecordRef/schema.yaml)


# For developers

The source code for this Building Block can be found in the following repository:

* URL: [https://github.com/ogcincubator/bblocks-cwl](https://github.com/ogcincubator/bblocks-cwl)
* Path: `_sources/v1_2_1/CWLTypeRecordRef`


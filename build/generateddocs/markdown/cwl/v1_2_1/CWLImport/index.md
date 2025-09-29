
# CWLImport (Schema)

`ogc.cwl.v1_2_1.CWLImport` *v1.2.1*

Represents an '$import' directive that should point toward another compatible CWL file to import where specified.
The contents of the imported file should be relevant contextually where it is being imported.


[*Status*](http://www.opengis.net/def/status): Under development

## Description

The schema validation of the CWL will not itself perform the '$import' to resolve and validate its contents.
Therefore, the complete schema will not be validated entirely, and could still be partially malformed.
To ensure proper and exhaustive validation of a CWL definition with this schema, all '$import' directives
should be resolved and extended beforehand.

## Schema

```yaml
$comment: 'The schema validation of the CWL will not itself perform the ''$import''
  to resolve and validate its contents.

  Therefore, the complete schema will not be validated entirely, and could still be
  partially malformed.

  To ensure proper and exhaustive validation of a CWL definition with this schema,
  all ''$import'' directives

  should be resolved and extended beforehand.

  '
additionalProperties: false
description: 'Represents an ''$import'' directive that should point toward another
  compatible CWL file to import where specified.

  The contents of the imported file should be relevant contextually where it is being
  imported.

  '
properties:
  $import:
    type: string
required:
- $import
type: object

```

Links to the schema:

* YAML version: [schema.yaml](https://ogcincubator.github.io/bblocks-cwl/build/annotated/cwl/v1_2_1/CWLImport/schema.json)
* JSON version: [schema.json](https://ogcincubator.github.io/bblocks-cwl/build/annotated/cwl/v1_2_1/CWLImport/schema.yaml)


# For developers

The source code for this Building Block can be found in the following repository:

* URL: [https://github.com/ogcincubator/bblocks-cwl](https://github.com/ogcincubator/bblocks-cwl)
* Path: `_sources/v1_2_1/CWLImport`


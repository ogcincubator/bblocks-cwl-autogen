
# CWLTypeDefinition (Schema)

`ogc.cwl.v1_2_1.CWLTypeDefinition` *v1.2.1*

Field type definition.

[*Status*](http://www.opengis.net/def/status): Under development

## Description

Note that 'Any' is equivalent to any of the non-null types.
Therefore, a nullable 'Any' explicitly specified by 'Any?' or its array-nullable form 'Any[]?' are not equivalent.

## Schema

```yaml
$comment: 'Note that ''Any'' is equivalent to any of the non-null types.

  Therefore, a nullable ''Any'' explicitly specified by ''Any?'' or its array-nullable
  form ''Any[]?'' are not equivalent.

  '
description: Field type definition.
enum:
- 'null'
- Any
- Any?
- Any[]
- Any[]?
- Directory
- Directory?
- Directory[]
- Directory[]?
- File
- File?
- File[]
- File[]?
- boolean
- boolean?
- boolean[]
- boolean[]?
- double
- double?
- double[]
- double[]?
- enum?
- enum[]
- enum[]?
- float
- float?
- float[]
- float[]?
- int
- int?
- int[]
- int[]?
- integer
- integer?
- integer[]
- integer[]?
- long
- long?
- long[]
- long[]?
- string
- string?
- string[]
- string[]?
summary: CWL type string definition.
title: CWL type string definition
type: string

```

Links to the schema:

* YAML version: [schema.yaml](https://ogcincubator.github.io/bblocks-cwl/build/annotated/cwl/v1_2_1/CWLTypeDefinition/schema.json)
* JSON version: [schema.json](https://ogcincubator.github.io/bblocks-cwl/build/annotated/cwl/v1_2_1/CWLTypeDefinition/schema.yaml)


# For developers

The source code for this Building Block can be found in the following repository:

* URL: [https://github.com/ogcincubator/bblocks-cwl](https://github.com/ogcincubator/bblocks-cwl)
* Path: `_sources/v1_2_1/CWLTypeDefinition`


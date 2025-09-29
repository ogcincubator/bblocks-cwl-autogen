
# Checksum (Schema)

`ogc.cwl.v1_2_1.Checksum` *v1.2.1*

Checksum

[*Status*](http://www.opengis.net/def/status): Under development

## Description

Minimal pattern check to know which hash algorithm to apply,
but don't check too harshly for the rest (length, allowed characters, etc.).

## Schema

```yaml
$comment: 'Minimal pattern check to know which hash algorithm to apply,

  but don''t check too harshly for the rest (length, allowed characters, etc.).

  '
pattern: ^[a-z0-9\-]+\$[\w\-.]+$
type: string

```

Links to the schema:

* YAML version: [schema.yaml](https://ogcincubator.github.io/bblocks-cwl/build/annotated/cwl/v1_2_1/Checksum/schema.json)
* JSON version: [schema.json](https://ogcincubator.github.io/bblocks-cwl/build/annotated/cwl/v1_2_1/Checksum/schema.yaml)


# For developers

The source code for this Building Block can be found in the following repository:

* URL: [https://github.com/ogcincubator/bblocks-cwl](https://github.com/ogcincubator/bblocks-cwl)
* Path: `_sources/v1_2_1/Checksum`



# CWLAtomicNested (Schema)

`ogc.cwl.v1_2_1.CWLAtomicNested` *v1.2.1*

CWLAtomicNested

[*Status*](http://www.opengis.net/def/status): Under development

## Description

Same as 'CWLAtomic', but 'cwlVersion' not repeated (only at root).
## Schema

```yaml
$comment: Same as 'CWLAtomic', but 'cwlVersion' not repeated (only at root).
allOf:
- $ref: https://ogcincubator.github.io/bblocks-cwl/build/annotated/cwl/v1_2_1/CWLMetadata/schema.yaml
- $ref: https://ogcincubator.github.io/bblocks-cwl/build/annotated/cwl/v1_2_1/CWLDocumentation/schema.yaml
- $ref: https://ogcincubator.github.io/bblocks-cwl/build/annotated/cwl/v1_2_1/CWLAtomicBase/schema.yaml

```

Links to the schema:

* YAML version: [schema.yaml](https://ogcincubator.github.io/bblocks-cwl/build/annotated/cwl/v1_2_1/CWLAtomicNested/schema.json)
* JSON version: [schema.json](https://ogcincubator.github.io/bblocks-cwl/build/annotated/cwl/v1_2_1/CWLAtomicNested/schema.yaml)


# For developers

The source code for this Building Block can be found in the following repository:

* URL: [https://github.com/ogcincubator/bblocks-cwl](https://github.com/ogcincubator/bblocks-cwl)
* Path: `_sources/v1_2_1/CWLAtomicNested`


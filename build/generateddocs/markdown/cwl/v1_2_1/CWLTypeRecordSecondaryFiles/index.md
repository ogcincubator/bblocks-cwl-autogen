
# CWLTypeRecordSecondaryFiles (Schema)

`ogc.cwl.v1_2_1.CWLTypeRecordSecondaryFiles` *v1.2.1*

CWLTypeRecordSecondaryFiles

[*Status*](http://www.opengis.net/def/status): Under development

## Schema

```yaml
oneOf:
- $comment: Either an expression or the regex pattern directly.
  $ref: https://ogcincubator.github.io/bblocks-cwl/build/annotated/cwl/v1_2_1/CWLExpression/schema.yaml
- $ref: https://ogcincubator.github.io/bblocks-cwl/build/annotated/cwl/v1_2_1/CWLTypeRecordSecondaryFileSchema/schema.yaml
- items:
    $comment: Either an expression or the regex pattern directly.
    $ref: https://ogcincubator.github.io/bblocks-cwl/build/annotated/cwl/v1_2_1/CWLExpression/schema.yaml
  type: array
- items:
    $ref: https://ogcincubator.github.io/bblocks-cwl/build/annotated/cwl/v1_2_1/CWLTypeRecordSecondaryFileSchema/schema.yaml
  type: array

```

Links to the schema:

* YAML version: [schema.yaml](https://ogcincubator.github.io/bblocks-cwl/build/annotated/cwl/v1_2_1/CWLTypeRecordSecondaryFiles/schema.json)
* JSON version: [schema.json](https://ogcincubator.github.io/bblocks-cwl/build/annotated/cwl/v1_2_1/CWLTypeRecordSecondaryFiles/schema.yaml)


# JSON-LD Context

```jsonld
{
  "@context": {
    "pattern": "cwl:SecondaryFileSchema/pattern",
    "required": "cwl:SecondaryFileSchema/required",
    "cwl": "https://w3id.org/cwl/cwl#",
    "@version": 1.1
  }
}
```

You can find the full JSON-LD context here:
[context.jsonld](https://ogcincubator.github.io/bblocks-cwl/build/annotated/cwl/v1_2_1/CWLTypeRecordSecondaryFiles/context.jsonld)


# For developers

The source code for this Building Block can be found in the following repository:

* URL: [https://github.com/ogcincubator/bblocks-cwl](https://github.com/ogcincubator/bblocks-cwl)
* Path: `_sources/v1_2_1/CWLTypeRecordSecondaryFiles`


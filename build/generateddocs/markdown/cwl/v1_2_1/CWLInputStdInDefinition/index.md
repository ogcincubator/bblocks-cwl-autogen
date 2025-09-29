
# CWLInputStdInDefinition (Schema)

`ogc.cwl.v1_2_1.CWLInputStdInDefinition` *v1.2.1*

Indicates that the value passed to this CWL input will be redirected to the standard input stream of the command.
Can be defined for only one input and must not be combined with 'stdin' at the root of the CWL document.


[*Status*](http://www.opengis.net/def/status): Under development

## Schema

```yaml
description: 'Indicates that the value passed to this CWL input will be redirected
  to the standard input stream of the command.

  Can be defined for only one input and must not be combined with ''stdin'' at the
  root of the CWL document.

  '
enum:
- stdin
type: string

```

Links to the schema:

* YAML version: [schema.yaml](https://ogcincubator.github.io/bblocks-cwl/build/annotated/cwl/v1_2_1/CWLInputStdInDefinition/schema.json)
* JSON version: [schema.json](https://ogcincubator.github.io/bblocks-cwl/build/annotated/cwl/v1_2_1/CWLInputStdInDefinition/schema.yaml)


# For developers

The source code for this Building Block can be found in the following repository:

* URL: [https://github.com/ogcincubator/bblocks-cwl](https://github.com/ogcincubator/bblocks-cwl)
* Path: `_sources/v1_2_1/CWLInputStdInDefinition`


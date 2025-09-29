
# EnableReuseValue (Schema)

`ogc.cwl.v1_2_1.EnableReuseValue` *v1.2.1*

Indicates if reuse is enabled for this tool.

Can be an expression when combined with 'InlineJavascriptRequirement'
(see also: https://www.commonwl.org/v1.2/CommandLineTool.html#Expression).


[*Status*](http://www.opengis.net/def/status): Under development

## Schema

```yaml
description: 'Indicates if reuse is enabled for this tool.


  Can be an expression when combined with ''InlineJavascriptRequirement''

  (see also: https://www.commonwl.org/v1.2/CommandLineTool.html#Expression).

  '
oneOf:
- type: boolean
- $ref: https://ogcincubator.github.io/bblocks-cwl/build/annotated/cwl/v1_2_1/CWLExpression/schema.yaml
title: EnableReuseValue

```

Links to the schema:

* YAML version: [schema.yaml](https://ogcincubator.github.io/bblocks-cwl/build/annotated/cwl/v1_2_1/EnableReuseValue/schema.json)
* JSON version: [schema.json](https://ogcincubator.github.io/bblocks-cwl/build/annotated/cwl/v1_2_1/EnableReuseValue/schema.yaml)


# For developers

The source code for this Building Block can be found in the following repository:

* URL: [https://github.com/ogcincubator/bblocks-cwl](https://github.com/ogcincubator/bblocks-cwl)
* Path: `_sources/v1_2_1/EnableReuseValue`


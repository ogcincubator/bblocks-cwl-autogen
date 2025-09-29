
# CWLExpression (Schema)

`ogc.cwl.v1_2_1.CWLExpression` *v1.2.1*

When combined with 'InlineJavascriptRequirement', this field allows runtime parameter references
(see also: https://www.commonwl.org/v1.2/CommandLineTool.html#Expression).


[*Status*](http://www.opengis.net/def/status): Under development

## Description

Whenever this option is applicable for a parameter, any other 'normal' string should not be specified.
For JSON schema validation, there is no easy way to distinguish them unless using complicated string patterns.

## Schema

```yaml
$comment: 'Whenever this option is applicable for a parameter, any other ''normal''
  string should not be specified.

  For JSON schema validation, there is no easy way to distinguish them unless using
  complicated string patterns.

  '
description: 'When combined with ''InlineJavascriptRequirement'', this field allows
  runtime parameter references

  (see also: https://www.commonwl.org/v1.2/CommandLineTool.html#Expression).

  '
title: CWLExpression
type: string

```

Links to the schema:

* YAML version: [schema.yaml](https://ogcincubator.github.io/bblocks-cwl/build/annotated/cwl/v1_2_1/CWLExpression/schema.json)
* JSON version: [schema.json](https://ogcincubator.github.io/bblocks-cwl/build/annotated/cwl/v1_2_1/CWLExpression/schema.yaml)


# For developers

The source code for this Building Block can be found in the following repository:

* URL: [https://github.com/ogcincubator/bblocks-cwl](https://github.com/ogcincubator/bblocks-cwl)
* Path: `_sources/v1_2_1/CWLExpression`


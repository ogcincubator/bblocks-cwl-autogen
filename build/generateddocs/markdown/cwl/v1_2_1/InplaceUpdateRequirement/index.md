
# InplaceUpdateRequirement (Schema)

`ogc.cwl.v1_2_1.InplaceUpdateRequirement` *v1.2.1*

If 'inplaceUpdate' is true, then an implementation supporting this feature may permit tools to directly
update files with 'writable: true' in 'InitialWorkDirRequirement'. That is, as an optimization,
files may be destructively modified in place as opposed to copied and updated
(see also: https://www.commonwl.org/v1.2/CommandLineTool.html#InplaceUpdateRequirement).


[*Status*](http://www.opengis.net/def/status): Under development

## Schema

```yaml
additionalProperties: false
description: 'If ''inplaceUpdate'' is true, then an implementation supporting this
  feature may permit tools to directly

  update files with ''writable: true'' in ''InitialWorkDirRequirement''. That is,
  as an optimization,

  files may be destructively modified in place as opposed to copied and updated

  (see also: https://www.commonwl.org/v1.2/CommandLineTool.html#InplaceUpdateRequirement).

  '
properties:
  class:
    enum:
    - InplaceUpdateRequirement
    type: string
  inplaceUpdate:
    title: inplaceUpdate
    type: boolean
    x-jsonld-id: https://w3id.org/cwl/cwl#InplaceUpdateRequirement/inplaceUpdate
required:
- inplaceUpdate
title: InplaceUpdateRequirement
type: object
x-jsonld-prefixes:
  cwl: https://w3id.org/cwl/cwl#

```

Links to the schema:

* YAML version: [schema.yaml](https://ogcincubator.github.io/bblocks-cwl/build/annotated/cwl/v1_2_1/InplaceUpdateRequirement/schema.json)
* JSON version: [schema.json](https://ogcincubator.github.io/bblocks-cwl/build/annotated/cwl/v1_2_1/InplaceUpdateRequirement/schema.yaml)


# JSON-LD Context

```jsonld
{
  "@context": {
    "inplaceUpdate": "cwl:InplaceUpdateRequirement/inplaceUpdate",
    "cwl": "https://w3id.org/cwl/cwl#",
    "@version": 1.1
  }
}
```

You can find the full JSON-LD context here:
[context.jsonld](https://ogcincubator.github.io/bblocks-cwl/build/annotated/cwl/v1_2_1/InplaceUpdateRequirement/context.jsonld)


# For developers

The source code for this Building Block can be found in the following repository:

* URL: [https://github.com/ogcincubator/bblocks-cwl](https://github.com/ogcincubator/bblocks-cwl)
* Path: `_sources/v1_2_1/InplaceUpdateRequirement`


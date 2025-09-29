
# ScatterMethod (Schema)

`ogc.cwl.v1_2_1.ScatterMethod` *v1.2.1*

If 'scatter' declares more than one input parameter, 'scatterMethod'
describes how to decompose the input into a discrete set of jobs.

- dotproduct: specifies that each of the input arrays are aligned and
  one element taken from each array to construct each job. It is an
  error if all input arrays are not the same length.

- nested_crossproduct: specifies the Cartesian product of the inputs, producing 
  a job for every combination of the scattered inputs. The output must be nested 
  arrays for each level of scattering, in the order that the input arrays
  are listed in the 'scatter' field.

- flat_crossproduct: specifies the Cartesian product of the inputs, producing a 
  job for every combination of the scattered inputs. The output arrays must be 
  flattened to a single level, but otherwise listed in the order that the input 
  arrays are listed in the 'scatter' field.


[*Status*](http://www.opengis.net/def/status): Under development

## Schema

```yaml
additionalProperties: false
default: dotproduct
description: "If 'scatter' declares more than one input parameter, 'scatterMethod'\ndescribes
  how to decompose the input into a discrete set of jobs.\n\n- dotproduct: specifies
  that each of the input arrays are aligned and\n  one element taken from each array
  to construct each job. It is an\n  error if all input arrays are not the same length.\n\n-
  nested_crossproduct: specifies the Cartesian product of the inputs, producing \n
  \ a job for every combination of the scattered inputs. The output must be nested
  \n  arrays for each level of scattering, in the order that the input arrays\n  are
  listed in the 'scatter' field.\n\n- flat_crossproduct: specifies the Cartesian product
  of the inputs, producing a \n  job for every combination of the scattered inputs.
  The output arrays must be \n  flattened to a single level, but otherwise listed
  in the order that the input \n  arrays are listed in the 'scatter' field.\n"
enum:
- dotproduct
- nested_crossproduct
- flat_crossproduct
required:
- timelimit
- class
title: scatterMethod
type: string

```

Links to the schema:

* YAML version: [schema.yaml](https://ogcincubator.github.io/bblocks-cwl/build/annotated/cwl/v1_2_1/ScatterMethod/schema.json)
* JSON version: [schema.json](https://ogcincubator.github.io/bblocks-cwl/build/annotated/cwl/v1_2_1/ScatterMethod/schema.yaml)


# For developers

The source code for this Building Block can be found in the following repository:

* URL: [https://github.com/ogcincubator/bblocks-cwl](https://github.com/ogcincubator/bblocks-cwl)
* Path: `_sources/v1_2_1/ScatterMethod`


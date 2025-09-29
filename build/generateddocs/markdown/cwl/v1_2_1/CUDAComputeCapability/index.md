
# CUDAComputeCapability (Schema)

`ogc.cwl.v1_2_1.CUDAComputeCapability` *v1.2.1*

The compute capability supported by the GPU hardware.

* If this is a single value, it defines only the minimum compute capability.
  GPUs with higher capability are also accepted.
* If it is an array value, then only select GPUs with compute capabilities that explicitly
  appear in the array.
  See https://docs.nvidia.com/deploy/cuda-compatibility/#faq and
  https://docs.nvidia.com/cuda/cuda-c-best-practices-guide/index.html#cuda-compute-capability
  for details.


[*Status*](http://www.opengis.net/def/status): Under development

## Schema

```yaml
description: "The compute capability supported by the GPU hardware.\n\n* If this is
  a single value, it defines only the minimum compute capability.\n  GPUs with higher
  capability are also accepted.\n* If it is an array value, then only select GPUs
  with compute capabilities that explicitly\n  appear in the array.\n  See https://docs.nvidia.com/deploy/cuda-compatibility/#faq
  and\n  https://docs.nvidia.com/cuda/cuda-c-best-practices-guide/index.html#cuda-compute-capability\n
  \ for details.\n"
oneOf:
- description: The compute capability supported by the GPU hardware.
  pattern: ^\d+\.\d+$
  title: CUDA compute capability
  type: string
- $ref: https://ogcincubator.github.io/bblocks-cwl/build/annotated/cwl/v1_2_1/CUDAComputeCapabilityArray/schema.yaml
title: CUDA compute capability

```

Links to the schema:

* YAML version: [schema.yaml](https://ogcincubator.github.io/bblocks-cwl/build/annotated/cwl/v1_2_1/CUDAComputeCapability/schema.json)
* JSON version: [schema.json](https://ogcincubator.github.io/bblocks-cwl/build/annotated/cwl/v1_2_1/CUDAComputeCapability/schema.yaml)


# For developers

The source code for this Building Block can be found in the following repository:

* URL: [https://github.com/ogcincubator/bblocks-cwl](https://github.com/ogcincubator/bblocks-cwl)
* Path: `_sources/v1_2_1/CUDAComputeCapability`


# BFloat16 draft Charter

The BFloat16 Task Group (BF16 TG) shall create extensions for vector and scalar floating-point functionality. These extensions include a common set of basic details on the BF16 format and behaviors. There will be
minimal extensions for scalar and for vector BF16 support that provide the basic instructions to allow BF16 to be used as an interchange format wherein floating-point numbers can be converted between BF16 and a
fully-supported floating-point format such as binary32 (aka single precision, FP32). The group will also create an extension for RISC-V vectors that adds widening multiply-add type instructions where one or more
operands are in the BF16 format and the result is in the FP32 format.

The BF16 specifications will include new opcodes and encodings that are specific to BF16 and do not rely on any state --- new or preexisting --- to specify the format for the instructions.

For each of these extensions, The BF16TG will produce complete prose-based written specifications as well as RISC-V SAIL formal specifications. The TG will update the SPIKE model to support these extensions and will
produce other deliverables as required by its ISA Status Checklist as part of the 2022 New Acceptance Criteria. 

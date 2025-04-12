# Convert nf4 to Triton
 Convert a nf4 quantized tensor into fp16 or bf16 into a single Triton kernel The double dequant of the absmax and weight forming must be done in 1 Triton kernel. Must work on Tesla T4.

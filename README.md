# Convert nf4 to Triton
 Convert a nf4 quantized tensor into fp16 or bf16 into a single Triton kernel The double dequant of the absmax and weight forming must be done in 1 Triton kernel. Must work on Tesla T4.

(https://colab.research.google.com/drive/1wIiE3rv0HPVKNKgyd3fqSSgcTTYuE_zD?usp=sharing)

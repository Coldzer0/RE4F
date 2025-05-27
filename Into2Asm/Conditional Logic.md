##### CMP, TEST & (JZ = JE, JNZ = JNE), JL, JLE, JG, JGE etc...

```C
BITS 64
default rel  
section .text

main:
    mov rsi, A
    mov rdi, B
    mov rbx, Result
    clc
    mov rcx, 2
.addLoop:
    mov rax, [rsi + rcx * 8]
    adc rax, [rdi + rcx * 8]
    mov [rbx + rcx * 8], rax
    loop .addLoop
  
section .data
A      dq 0x1122334455667788, 0x8877665544332211
B      dq 0x8877665544332211, 0x1122334455667788
Result times 4 dd 0 
```

# TODO (MORE EXAMPLES)
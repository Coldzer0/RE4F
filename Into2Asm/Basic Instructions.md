##### MOV, ADD, SUB, INC, DEC, JMP (FLAGS)

```C
int main(){
    int x = 5;
    int y = 10;
    int sum = x + y;
    sum = sum - 1;
    sum +=1;
    sum -= 1;
    goto exit;
    sum = 100;
exit:
    return 0;
}
```

- Data Types
	- Signed 
		- One's complement
		- two's complement 
	- Unsigned

- MOV
	- MOVSX
		- move with sign extend
	- MOVZX
		- move with zero extend


# TODO (MORE EXAMPLES)
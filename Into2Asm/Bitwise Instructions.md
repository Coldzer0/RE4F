##### AND, OR, XOR, NOT, SHL, SHR, ROL, ROR

```C
const READ = 1;
const WRITE = 1;
const EXECUTE = 1;

int main(){
	int prem = READ | EXECUTE;
	if ( (prem & READ) == READ ){
		printf("We can read\n");
	}
	if ( (prem & WRITE) == WRITE ){
		printf("We can write\n");
	}
	if ( (prem & EXECUTE) == EXECUTE ){
		printf("We can execute\n");
	}
	return 0;
}
```



# TODO (MORE EXAMPLES)
#### PUSH, POP, CALL, RET & Stack / Functions Prolog - Epilog | Params  -> Call Convention 

```C
int add(int a, int b) {
    return a + b;
}
int main(){

    int x = 5;
    int y = 10;
    int sum = add(x , y);
    sum = sum - 1;
    
    sum +=1;
    sum -= 1;

    goto exit;
    sum = 100;
exit:
    
    return sum;
}
```

# TODO (MORE EXAMPLES)
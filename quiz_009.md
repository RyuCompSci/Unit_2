```.py
def missingNumber(inp):
    len_inp = len(inp)
    inp1 = inp[0]
    x = 0
    for i in range(len_inp):
        if inp[i] != inp1+i:
            x = inp[i]-1
            break
    return x
```

### wordlength

```.py
def wordlength(inp):
    len_inp = len(inp)
    sum = 0
    for i in range(len_inp):
        sum += len(inp[i])
    avr = sum/len_inp
    return avr
```

```.py
def BigNeighbour(inp):
    len_inp = len(inp)
    x = abs(inp[1]-inp[0])
    for i in range(len_inp-2):
        if x <= abs(inp[i+2]-inp[i+1]):
            x = abs(inp[i+2]-inp[i+1])
    return x
```

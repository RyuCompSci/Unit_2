```.py
def maxAbs(inp):
    x = abs(inp[0])
    for i in range(len(inp)-1):
        if x >= abs(inp[i+1]):
            x = inp[i]
        else:
            x = inp[i+1]
    return x
```

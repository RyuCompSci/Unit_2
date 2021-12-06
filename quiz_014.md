### evenlySpaced

```.py
def evenlySpaced(inp1, inp2, inp3):
    answer = ""
    if abs(inp1-inp2) == abs(inp2-inp3) or abs(inp2-inp3) == abs(inp3-inp1) or abs(inp3-inp1) == abs(inp1-2):
        answer = "True"
    else:
        answer = "False"
    return answer
```

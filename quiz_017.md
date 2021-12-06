### ValidTriangle

```.py
def ValidTriangle(inp1, inp2, inp3):
    Output = ""
    if inp1 >= inp2 and inp1 >= inp3:
        if inp1 < inp2+inp3:
            Output = "True"
        else:
            Output = "False"
    elif inp2 >= inp1 and inp2 >= inp3:
        if inp2 < inp1+inp3:
            Output = "True"
        else:
            Output = "False"
    else:
        if inp3 < inp2+inp1:
            Output = "True"
        else:
            Output = "False"
    return Output
```
